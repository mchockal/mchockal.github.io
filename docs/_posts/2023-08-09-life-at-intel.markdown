---
layout: post
title:  "Life at Intel as MLE"
date:   2023-08-09 16:04:37 -0500
categories: jekyll update
---

In the summer of 2022, I got an amazing opportunity to intern with Intel as a Machine Learning Engineer. Little did I know back then that the next year of my life would be extremely chaotic navigating through multiple reorgs, moving into different teams, thereby getting to work on different projects while figuring out how I can add value to the company! 

While I may be a novice in the world of machine learning, I learned through my internship at Intel that my current strengths lie in understanding and addressing the challenges involved in building and deploying in-house models, understand the hardware-software interplay that affect the latency and throughput of a model and I learned the fact that I understand image processing and convolutions better than language understanding via equivalent embeddings.

Ok, Ok. I know I just admitted my understanding of large language models was not as good as image processing. BUT that was in the summer of 2022. Here’s what I did to overcome that limitation.

In August 2022, Stability AI open-sourced Stable Diffusion v1 and it was EVERYWHERE. This was around two months into internship, and I was waiting on a next good project to work on. I reached out to my awesome mentor and told her I am interested in understanding the working of Stable diffusion and since it was open-sourced, I offered to take on the task to benchmark and optimize stable diffusion inference because it was all the rage back then! My mentor, being as cool as she is, agreed it was a good project and so began my two-month deep dive into all about diffusion models, the components that made up the architecture, why it works, how it differed from GAN’s. I studied this model in the context of ‘text-to-image’ generation. Now, given the novice I am, I do not want to sound pedantic, but the original Stable Diffusion used pre-training CLIP for text embeddings. Aha! There it is.. Word embeddings. At this point of time, the only thing I remembered about embeddings is that they are some latent representations of their high dimensional equivalent in lower dimension space and that similarity = cosine distance between the embedding vectors. So, I went back to the basics of CS-7643 (Deep Learning at Georgia Tech) and revisited word-2-vec, RNN, LSTM’s and finally Transformers. You know how when you first read something, you don’t fully understand, but when you revisit the same after going through a character training arc, you start to see things you didn’t see before and understand better? Well, that’s exactly what happened. The two months of Stable Diffusion were brutal, yet it was THE most rewarding learning experience ever! As a result of my research, I presented a tech talk / presentation at the Intel AI Everywhere Conference and of course wrote an optimized inference pipeline using the original Stable Diffusion github repo as my starter code.  



