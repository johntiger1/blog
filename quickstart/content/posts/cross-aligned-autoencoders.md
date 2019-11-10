---
title: "Cross Aligned Autoencoders"
date: 2019-10-31T11:36:52-04:00
draft: False
---

How does Shen's paper work? Well it tries to fit a cross-aligned autoencoder. This is simply an autoencoder that is also guided adversarially by a discriminator. In terms of the basics/nitty gritty technical details, we have the following:

1. We have a sequential autoencoder. This is "simply" a recurrent autoencoder: i.e. an autoencoder where the encoder accepts a sequence of states, and the decoder also generates a sequence of states. 
2.  This sequential autoencoder is aligned by an adversary. Essentially, this adversary ensures that the autoencoder learns a reconstruction mapping that is both stylistically different, as well as faithful to the original content 

dec inputs are the GROUND TRUTH, used for training! 

Some confusing things: in the paper, z refers to the "latent" output of the encoder at certain points, while it refers to the content in other areas. 

Long term plans: if this PANS OUT then, we have our pick of MIT, CMU, Stanford etc.





