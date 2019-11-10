---
title: "Reinforcement Learning"
date: 2019-10-31T23:44:55-04:00
draft: false
---

Today marks my first foray into reinforcement learning territory!

Although I have studied the topic extensively academically (well, kind of) I have not had a chance to actually sit down and play around with some implementations. So without further ado, here goes!

Observation #1: past classifications affect future performance.

A regular ol' CNN classifier is one-shot: it makes the prediction and then that's it. Same with a RNN, sequential though it may be. But a reinforcement learning agent (under certain formulations) might necessarily be a dynamical, feedback loop system:

Consider a simple cartpole testbed. You have a simple pole attached to a cart, and you want to control the cart to go left or right, in order to keep the pole upright. Imagine you start from scratch, i.e. you have no past experience of the world, and no prior on your policy. Then, you have training data to start off with! 

So what to do? 

Well, you run a random policy, play for an episode (one run through of the game until you reach a terminal state), and then see what happens.