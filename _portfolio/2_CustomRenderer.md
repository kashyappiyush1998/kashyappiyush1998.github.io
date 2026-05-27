---
title: "Custom Renderer"
excerpt: "I have created a personal Path tracer based renderer.<br/><br/><img src='/images/rendered_image.png'>"
collection: portfolio
---

I have created a personal custom renderer for my own learning purpose. I have been working on it and will try to keep making it better throughout my studies at University of Zaragoza, and probably even after that.
<br><br>
At the moment it is a path tracer written in OpenGL and computer shader in which gltf model can be loaded. The gltf 2.0 model is created in blender and then exported for use in the renderer. The image visible is rendered from model that has 80,000 triangles with ray-triangle intersection. This renderer is temporally denoised, meaning the renders will accumulate frames over time to reduce noise. It also has monte carlo sampling for noise reduction. The light used in area light which makes more sense than a point light to enable physically based rendering.
