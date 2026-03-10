---
title: "Nuke The City"
collection: portfolio
excerpt: "Volumetric path tracer built on top of Nori with emissive media."
---

<div markdown="0" style="margin-bottom: 1.5em;">
  <iframe width="100%" height="350"
    src="https://www.youtube.com/embed/JS_OkhReueE"
    frameborder="0"
    allowfullscreen>
  </iframe>
</div>

I rendered this video frame-by-frame using my custom **NORI renderer** for my course project at the **University of Zaragoza** in *Modelling and Simulation of Appearance*.

The volumetric media is loaded using **OpenVDB**, including **temperature** and **density fields**.

The emission and color of the medium are inferred using a **logarithmic temperature scale**.

To make emission more prominent, **Next Event Estimation (NEE)** is used by inserting **point lights at the centers of octree leaf nodes**. The octree provides a tight spatial bounding structure for efficient volumetric rendering.