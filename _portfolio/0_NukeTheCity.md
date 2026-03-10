---
title: "Nuke The City"
collection: portfolio
excerpt: "Volumetric path tracer built on top of Nori with emissive media.<br/><br/><img src='/images/nuke_the_city.gif'>"

---

<div style="position:relative;padding-bottom:56.25%;height:0;">
<iframe src="https://www.youtube.com/embed/JS_OkhReueE"
style="position:absolute;top:0;left:0;width:100%;height:100%;"
frameborder="0" allowfullscreen></iframe>
</div>


I rendered this video frame-by-frame using my custom **NORI renderer** for my course project at the **University of Zaragoza** in *Modelling and Simulation of Appearance*.

The volumetric media is loaded using **OpenVDB**, including **temperature** and **density fields**.

The emission and color of the medium are inferred using a **logarithmic temperature scale**.

To make emission more prominent, **Next Event Estimation (NEE)** is used by inserting **point lights at the centers of octree leaf nodes**. The octree provides a tight spatial bounding structure for efficient volumetric rendering.