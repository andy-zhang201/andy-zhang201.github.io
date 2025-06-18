---
layout: post
title: PMMA Weight Optimization Project
description:  Optimizing the strength of a PMMA part using the minimum amount of material.

skills: 
- FEA/FEM
- Topology Optimization
- Solidworks CAD
- Mechanics of Solids
main-image: /s2w_header_photo.png
main-image-class: img-scale-down
---

---
## Situation

For an in-class engineering competition, I need to create a part that could hold the most weight per gram of part material. The competition also had a requirement to include a rectangular hole along the bottom half of the sample which purposefully weakened the part. Along with my partner Chetanya, our task was to design an acrylic sample with the maximum strength-to-weight ratio given the requirements of the competition.

{% include image-gallery.html images="./images/sample_unbroken.png" height="300" alignment="center" %} 
<span style="display: block; font-style: italic; text-align: center;"> The final part that got tested. </span>

## Methods Used

We used Solidworks to create CAD models for the part and ANSYS FEA to conduct simulations. Starting with a base part, we used simulation results from ANSYS to find areas where material could be removed. By iterating on the design, we were able to continue improving the strength-to-weight ratio until we reached our final result. Once that was done, some topology optimization studies using Solidworks Simulations to refine our results. 

{% include image-gallery.html images="./images/part_dims.png, ./images/fea.png" height="350" alignment="center" %} 
<span style="display: block; font-style: italic; text-align: center;"> Left: The design drawing for the part. / Right: Analysis results for where the part is predicted to fail. </span>


## Outcomes

My teammate and I created a part which weighed just **16 grams** and held **118 kg of weight (1161 N)** before it broke. We achieved a **strength-to-weight ratio of 75.86 N/g** and won **Second Place**.

{% include image-gallery.html images="./images/s2w_results.png" height="400" alignment="center" %}
<span style="display: block; font-style: italic; text-align: center;"> We achieved great results in the competition! </span>


Our design process is described in this report: <a href="https://drive.google.com/file/d/12lWFRJd0-iverU7mvI7Xfldi00CzyBaF/view?usp=sharing"><b>PMMA Design Report</b></a>

After testing, our analysis of the results is described in this report: <a href="https://drive.google.com/file/d/1e2snMPQgfWGdiTGvvVNwI_jXVA4hODLv/view?usp=sharing "><b>PMMA Test Results Analysis</b></a>

