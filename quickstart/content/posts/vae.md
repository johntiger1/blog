---
title: "Variational Auto Encoder"
date: 2019-10-27T21:31:36-04:00
draft: false
tags: 
- todo
- deep learning
- variational auto encoders
---

VAEs are autoencoders with some added randomness. The encoder network (also called recognition or inference network) outputs parameters of a probability distribution for each data point. Then, for each data point, we sample from this parametrized distribution, and feed the SAMPLE to the decoder network, which then is tasked with reconstructing the output. The training objective involves changing from an integral, into just doing optimization, hence the VAE variational objective. In particular, all we do is maximize the ELBO, which helps push up our p(x) which normally would require an integral! 

Todo:
Go over amortized inference; explain it in relation to inference networks, as well as efficiency (why exactly we can train a VAE, posterior inference, likelihood of the image p(x), and relation to ELBO [relation to variational methods; in particular, how we are in a sense avoiding integration over all the latent variables])
