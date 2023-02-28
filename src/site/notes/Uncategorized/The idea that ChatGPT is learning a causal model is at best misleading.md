---
{"dg-publish":true,"permalink":"/uncategorized/the-idea-that-chat-gpt-is-learning-a-causal-model-is-at-best-misleading/"}
---

*[[Uncategorized/Attention Conservation Notice\|Attention Conservation Notice]]: A friend of mine is afraid of the singularity and sent me a [lesswrong article](https://www.lesswrong.com/posts/sbaQv8zmRncpmLNKv/the-idea-that-chatgpt-is-simply-predicting-the-next-word-is). I am skeptical and so jotted down a few notes. Barely intelligible. While I do have a PhD in ML, I don't know shit about LLMs.*

Feb. 28, 2023 10:28

[original lesswrong article](https://www.lesswrong.com/posts/sbaQv8zmRncpmLNKv/the-idea-that-chatgpt-is-simply-predicting-the-next-word-is)

> If you think of the LLM as a complex dynamical system, then the trajectory is a valley in the system’s attractor landscape.

The real argument here is that you can construct simple dynamical systems, in the sense that the equation is quite simple, that have complex behavior. For example, the Lorenz system though there should be an even more simple example of say, ergodic behavior.

> We’re all more or less doing that when we speak or write, though there are times when we may set out to be deliberately surprising – but we can set such complications aside

We're all more or less doing that when we speak or write?

> If ChatGPT visits every parameter each time it generates a token, that sure looks “global” to me.

Bullshit

> Likewise, LLMs are produced by a relatively simple training process (minimizing loss on next-token prediction, using a large training set from the internet, Github, Wikipedia etc.) but the resulting 175 billion parameter model is extremely inscrutable.
> 
> _So the author is confusing the training process with the model._ It’s like saying “although it may appear that humans are telling jokes and writing plays, all they are actually doing is optimizing for survival and reproduction”. This fallacy occurs throughout the paper.

The train/test framework is not helpful for understanding this. The dynamical system view is more useful (though beware that this starts to get close to the term "emergent behavior" which we must be wary of). The interesting thing about chaos is that, while the behavior is not perfectly predictable, maybe even surprising, it has well-defined properties and mathematical constraints. It is not that "everything is possible." The Lorenz System has finite support. In the same spirit, we need to take a step back and realize that the kind of "real AI" that people are afraid of would require causal modeling which is mathematically impossible to construct using correlation only. If the model is able to start making interventions in the world, then we need to consider the possibility that it will be able to construct a casual model. But this goes beyond predicting the next word, which is the scope of this article.