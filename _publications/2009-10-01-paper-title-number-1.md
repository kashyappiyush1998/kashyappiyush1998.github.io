---
title: "We Never Go Out of Style: Motion Disentanglement by Subspace Decomposition of Latent Space"
collection: publications
permalink: /publication/we-never-go-out-of-style
date: 2023-07-01
venue: "CVPR 2023 Workshops (CVPRW)"
paperurl: "https://arxiv.org/pdf/2306.00559.pdf"
citation: "Rishubh Parihar, Raghav Magazine, Piyush Tiwari, R. Venkatesh Babu. We Never Go Out of Style: Motion Disentanglement by Subspace Decomposition of Latent Space. IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023."
excerpt: "A method for discovering disentangled motion subspaces in the latent space of style-based GANs for controllable motion editing."
---

[📄 Read Paper (arXiv)](https://arxiv.org/pdf/2306.00559.pdf)

### Abstract

Real-world objects exhibit complex motion composed of multiple independent components. For example, during speech a person simultaneously changes facial expressions, head orientation, and body pose. Disentangling these motion components is important for controllable video synthesis and editing.

In this work, we propose a method for **motion disentanglement using a pretrained image GAN**. Our approach discovers **semantically meaningful motion subspaces** in the latent space of widely used style-based GAN architectures. Each discovered subspace controls a single interpretable motion component.

The proposed method requires only a **small number of ground-truth video sequences** to identify these motion directions. We evaluate the disentanglement properties of the learned motion subspaces on **face and car datasets** through both quantitative and qualitative experiments.

Finally, we demonstrate several downstream applications enabled by the discovered motion subspaces, including:

- Motion editing  
- Selective motion transfer  
- Expression transfer without additional training