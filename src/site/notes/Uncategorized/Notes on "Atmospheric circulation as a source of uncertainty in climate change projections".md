---
{"dg-publish":true,"permalink":"/uncategorized/notes-on-atmospheric-circulation-as-a-source-of-uncertainty-in-climate-change-projections/"}
---

#climate-science #notes 

*[[Uncategorized/Attention Conservation Notice\|Attention Conservation Notice]]: This is literally the first real scientific article I've read about climate change so I probably understand nothing or worse, I think I understand but actually don't.*

[link](https://www.nature.com/articles/ngeo2253)

author: Theodore G. Shepherd
year: 2014

# Summary

Even in absence of any external force, liquids move giving rise to so-called natural fluctuations. The earth follows roughly the same path around the sun (does it?) and while a lot of variability can be predicted, there is also quite a bit of seasonal variability. Interestingly, the predictable variability is often thermodynamic in nature, e.g. temperature whereas the unpredictable variability if often dynamic in nature, e.g. precipitation. This same observation applies to climate change. Our models are mostly in agreement when it comes to the temperature changes that to expect in the coming decades but not so for precipitation. All we can say is that the distribution of precipitation does shift which means that the extreme events, while not necessarily more likely, are more extreme.

To predict the changes in precipitation due to climate change we need to figure out better dynamics models. Perhaps theory can help us, perhaps statistical models. We need uncertainty estimates to what turns out to be genuinely difficult modeling error.

Can ML help? Can Bayesian ML help? Purely statistical models suffer from a lack of data but pure physics models suffer from being wrong (this seems to be what the author is saying). Perhaps hybrid modeling is the answer.

# Annotations  
(2/27/2023, 4:13:09 PM)

“large-scale precipitation patterns (especially as reflected in ocean salinity)” (Shepherd, 2014, p. 703) What -- ocean salinity is related to how much it rains?

“quantification and prediction of its manifestations at the regional scale, together with an increasing demand for uncertainties.” (Shepherd, 2014, p. 703)

“planetary waves” (Shepherd, 2014, p. 703) What is a planetary wave?

“In contrast, we have much less confidence in atmospheric circulation aspects of climate change, which are primarily controlled by dynamics and exert a strong control on regional climate.” (Shepherd, 2014, p. 703) Right -- we are always talking about the average temperature of the entire planet, not the regional variations.

“Climate models are much less consistent in their predicted changes in precipitation than in temperature8 (Fig.  2); as precipitation is controlled by both temperature and circulation, the implication is that the inconsistencies arise from circulation.” (Shepherd, 2014, p. 703) Aha so here's a thing: Suppose we are able to predict regional temperature changes, this still doesn't necessarily help with understanding how the "air moves," and thus how precipitation works since precipitation is dominated by how the clouds get pushed around.

“Every aspect of climate change in which there is strong confidence, including not only the surface-temperature-related quantities mentioned above, but also certain global-scale patterns (for example, land–sea contrast, weakened tropical overturning), is based on thermodynamics. Circulation, on the other hand, is also governed by dynamics. Therefore the earlier dichotomy can be re-stated as saying there” (Shepherd, 2014, p. 703) Why are they ignores the "physics" e.g. parameterizations of clouds? No matter --  
  
Thermodynamics -- understood, dynamics (e.g. fluid motion = Newton's second law) -- not understood.

“Changes in radiative forcing, such as from increased greenhouse gases, directly perturb the thermodynamic balance of the climate system, and the first-order response is a change in atmospheric temperature and associated quantities such as humidity.” (Shepherd, 2014, p. 703) Right so this actually filters down into our everyday lives. Everyone knows about temperature and humidity increasing, but no one knows about, say, expected regional precipitation changes.

“2014” (Shepherd, 2014, p. 703)

“Outside the tropics, the dynamic balance between eddy momentum fluxes in the free atmosphere and boundary-layer friction provides a strong constraint on circulation10, which is not directly impacted by radiative forcing. The dominant circulation response to changes in radiative forcing thus occurs indirectly, through eddy feedbacks, and projects strongly onto the patterns of internal variability11,12” (Shepherd, 2014, p. 704) Somehow, in the tropics the temperature flux is the dominant forcing which makes that region easier to understand. The temperature flux only comes to affect other regions through interaction with the tropics, i.e. second-order interactions. This second-order interaction may be significant, but is difficult to distinguish from internal variability.  
  
  
But, how does this last part make sense -- if it makes a difference, shouldn't it show a different variability? Why is it swallowed up by internal variability?

“Whether climate change dominates over the variability for a given time horizon depends very much on the field in question.” (Shepherd, 2014, p. 704) Right -- so the thing is that we don't observe changes in a given field (e.g. preciptation) relative to the internal variability -- until suddenly we do. This is the tipping point that people are talking about. But to figure this out, we need climate models.

“However, the situation for both precipitation and sea-level pressure (a measure of circulation) is markedly different; while the distributions of the two ensembles are statistically distinct, they are strongly overlapping, meaning that climate change would not be reliably detectable from a single realization20. Indeed there is a reasonable likelihood (roughly 30%) that the long-term change from a single realization would be opposite in sign to the anthropogenic signal (the mean of the climate change distribution).” (Shepherd, 2014, p. 705) So what -- it just depends on how (un)lucky we are?!

“the Intergovernmental Panel on Climate Change’s confidence language” (Shepherd, 2014, p. 705) wow

“However, the impact of climate change on the distribution of possible 55-year changes in precipitation shown in Fig. 3 is quite large, roughly a factor of two, for the upper and lower thirds of the distribution. Although there is inherently low confidence in any single prediction, and one cannot expect the observed behaviour to be a robust indicator of climate change, there is a significant change in risk related to extremes22.” (Shepherd, 2014, p. 705) Subtle -- the mean is only shifted say, by 30%, but the tails are shifted quite a lot more. Thus it is the extreme events that become more likely.

“the temperature changes (for this forcing scenario and time horizon) are robust everywhere” (Shepherd, 2014, p. 705)

“Although much of the non-robustness is attributable to natural variability — the hatching attempts to indicate where this is likely to be the case — most likely reflects systematic discrepancies between models and is thus linked in some way to model error.” (Shepherd, 2014, p. 705) Hatching indicates where the natural variability is larger than the predicted variation. But for some reason, it seems that this is due to model error -- Why?? How do we know this?

“unresolved (sub-gridscale) processes such as clouds, convection, and boundary-layer and gravity-wave drag, and its sensitive interaction with large-scale dynamics” (Shepherd, 2014, p. 706) Ok this is a hypothesis but how is this "supported by the data," e.g. the actual simulation outputs?

“In statistical physics, the fluctuation–dissipation theorem (FDT)32 relates the response of a system to an applied perturbation to the intrinsic timescales of its internal modes of variability, with the longer-timescale modes responding more strongly.” (Shepherd, 2014, p. 706)

“However, the climate system is not in equilibrium and what appear to be internal timescales may themselves reflect a response to forcing” (Shepherd, 2014, p. 706)

“Nevertheless the broader concept that the circulation response to forcing is related to the variability of the system seems well grounded. In which case, errors in one should be related in some way to errors in the other.” (Shepherd, 2014, p. 706) i.e. it is the larger scale phenomena (= long timescale) which are more prone to respond to external forcing.

“The limited observational record implies that estimates of variability must mainly come from models.” (Shepherd, 2014, p. 706)

“There is evidence that the Coupled Model Intercomparison Project Phase 5 (CMIP5) models overall do not show enough variability in their past regional temperature and precipitation trends, hence their ensemble forecasts are not reliable in a probabilistic sense42. However, a purely statistical comparison between models and observations may reflect sampling errors because of the short” (Shepherd, 2014, p. 706) So the models are wrong because they don't show enough variability (how do we know?) but pure statistical methods are not sufficient either because we just don't have enough data.

“All this highlights the importance of identifying the physical mechanisms behind climate variability, rather than characterizing variability purely empirically as is generally the current practice1 (ENSO being the notable exception).” (Shepherd, 2014, p. 707)

“collaboration between the weather and climate communities” (Shepherd, 2014, p. 707)

“In the meantime it is necessary to work with ensembles of imperfect models” (Shepherd, 2014, p. 707) Why not Bayesian models? Other methods of estimating uncertainty?

“Weather predictions can be calibrated from past forecasts, but this is clearly not possible for climate projections because the relevant timescales are much too long.” (Shepherd, 2014, p. 707)

“Yet the potential change in weather-related risk associated with circulation aspects of climate change may be considerable. To discuss climate change under these circumstances, it seems necessary to move from a confidence-based approach to a more explicitly probabilistic, risk-based approach.” (Shepherd, 2014, p. 707)