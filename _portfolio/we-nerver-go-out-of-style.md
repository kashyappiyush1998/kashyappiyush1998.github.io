---
title: "We never go out of Style"
excerpt: "Motion Disentanglement by Subspace Decomposition of Latent Space.<br/><br/><img src='/images/cvprw2023.gif'>"
collection: portfolio
---

Our work published in CVPRW 2024: [We never go out of Style](https://rishubhpar.github.io/motionstyle/).<br>
Real-world objects perform complex motions that involve multiple decomposable motion components. For example, while talking, a person continuously changes their expressions, head pose, and body pose.
<br>
Recently, a range of methods have been proposed for unconditional video generation. However, these approaches provide limited control for manipulating an object’s motion in the generated video. In this work, we propose object motion decomposition in videos using a pretrained image GAN model. We generate disentangled linear motion subspaces in the latent space of widely used StyleGAN2 models that are semantically meaningful and control a single explainable motion component. We evaluate the disentanglement properties of motion subspaces on faces and car datasets with extensive quantitative and qualitative experiments.
<br>
Furthermore, we show results of the proposed motion decomposition on downstream video editing tasks of selective motion transfer, e.g., transferring only facial expressions and video stabilization without explicitly training for these tasks. As we are utilizing pretrained StyleGAN2 models, our method seamlessly integrates with latent-based editing and stylization methods.
