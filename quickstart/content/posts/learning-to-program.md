---
title: "Learning to Program"
date: 2019-11-01T18:40:45-04:00
draft: False
tags:
- csc2547
- cutting-edge
- seminar
---

This week, we covered a wide variety of approaches to *neural methods* to program synthesis and program induction. 

The first batch of presentations:
Romila, Eric and Henri
Romila: we have synthesis; the most naive way is indeed one way that CAN be used to form programs:
get the input space, the program space, the action space, and then try all possible combinations. Her paper talked about some sort of Monte Carlo tree search based method; alpha zero but applied to program synthesis, and she was critical as they don't update the policy network every time.  

My project partner Eric presented during this batch. 
Compositional neural nets: multi-level lstm that does planning at different abstraction levels!

Henri: we can use computational linguistics and a type of CFG (excel flash fill DSL is a CFG) to build up a more causal and synactical program. 



The second batch:
Interesting talk about Neural Turing Machines, which are just Turing Machines made with differentiable kludges and hacks. We also have a reinforcement learning approach to them as well; the principal issue with these machines are that the memory addressing is not a differentiable procedure! Interestingly, we talked about a programming language whose memory represents the program state; hence there is a direct mapping from state of the memory to the program instructions (Forth programming language). Is it Turing complete, can it be extendable to Python?



The third batch:
We covered Explore, Compress and Explore Compress 2 (compile), which are approaches for library synthesis. 
This seminar presentation was surprisingly heavy on principles of programming languages: the lambda calculus, and the combinatory logic. It was a well-done overview of the topic, and evoked fond memories of CSC324 for me. 

The conclusion:
We are also applying neural networks to learning how to make programs. The field is not quite mind-blowing yet; we generally need to have already solved the program (i.e. deduced the algorithm) in order to get the data for our neural net to solve it. 

Tips:
Alpha Zero algo is actually quite ubiquitous; we should take care to review it!