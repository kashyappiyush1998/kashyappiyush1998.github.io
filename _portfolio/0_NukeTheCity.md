---
title: "Nuke The City"
excerpt: "Volumetric path tracer built on top of Nori with emissive media.<br/><br/> <iframe width='100%' height='350' src='https://www.youtube.com/embed/JS_OkhReueE' title='YouTube video player' frameborder='0'  allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share' allowfullscreen>< iframe>"
collection: portfolio
---

I rendered this video frame-by-frame using my custom **NORI renderer** for my course project at the **University of Zaragoza** in *Modelling and Simulation of Appearance*.

The volumetric media is loaded using **OpenVDB**, including **temperature** and **density fields**. The emission and color of the medium are inferred using a **logarithmic temperature scale**.

To make emission more prominent, **Next Event Estimation (NEE)** is used by inserting **point lights at the centers of octree leaf nodes**. The octree provides a tight spatial bounding structure for efficient volumetric rendering.