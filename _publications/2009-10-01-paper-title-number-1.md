---
title: "We Never Go Out of Style: Motion Disentanglement by Subspace Decomposition of Latent Space"
collection: publications
permalink: /publication/we-never-go-out-of-style
layout: publication
date: 2023-07-01
venue: "CVPR 2023 Workshops (CVPRW)"
paperurl: "https://arxiv.org/pdf/2306.00559.pdf"
citation: "Rishubh Parihar, Raghav Magazine, Piyush Tiwari, R. Venkatesh Babu. We Never Go Out of Style: Motion Disentanglement by Subspace Decomposition of Latent Space. CVPR Workshops (CVPRW), 2023."
---

Real-world objects exhibit complex motion composed of multiple independent motion components. For example, while speaking a person simultaneously changes facial expressions, head orientation, and body pose.

In this work, we propose a method for **motion disentanglement using a pretrained image GAN**. Our approach discovers **semantically meaningful motion subspaces** in the latent space of widely used style-based GAN architectures. Each discovered subspace controls a single interpretable motion component.

The proposed method requires only a **small number of ground-truth video sequences** to identify these motion directions. We evaluate the disentanglement properties of the learned motion subspaces on **face and car datasets**, both quantitatively and qualitatively.

Finally, we demonstrate several downstream applications enabled by the discovered motion subspaces, including:

- Motion editing  
- Selective motion transfer  
- Expression transfer without additional training