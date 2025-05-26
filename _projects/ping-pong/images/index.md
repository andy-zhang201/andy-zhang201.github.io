---
layout: post
title: PMMA Weight Optimization Project
description:  Optimizing the strength of a PMMA part using the minimum amount of material.

skills: 
- FEA/FEM
- Topology Optimization
- Solidworks CAD
- Mechanics of Solids
main-image: /finalAssembly_A.jpg
main-image-class: img-scale-down
---

---
## Objectives

The goal of this project was to design a part that had the highest strength-to-weight ratio in an engineering class competition. The competition also had requirements to include several holes which purposefully weaken the part, making the task more challenging. Our task was to design around those requirements and to construct a part that could support the most load with the least amount of material. 
{% include image-gallery.html images="./images/sample_unbroken.png" height="300" alignment="center" %} 

## Outcomes

My teammate and I created a part which achieved a strength-to-weight ratio of 75.86 N/g, winning second place in our in-class competition. Our part weighed just 16 grams and held 1161 N of force before it broke.
{% include image-gallery.html images="./images/s2w_result.png" height="400" alignment="center" %}



## Methods Used

We used Solidworks to create CAD models for the part and ANSYS FEA to conduct simulations. Starting with a base part, we used simulation results from ANSYS to find areas where material could be removed. By iterating on the design, we were able to continue improving the strength-to-weight ratio until we reached our final result. Once that was done, some topology optimization studies using Solidworks Simulations to refine our results. 

A design report describing our design process can be found here: https://drive.google.com/file/d/12lWFRJd0-iverU7mvI7Xfldi00CzyBaF/view?usp=sharing

After testing the design, we also analyzed the validation results and wrote another report here: https://drive.google.com/file/d/1e2snMPQgfWGdiTGvvVNwI_jXVA4hODLv/view?usp=sharing 

{% include image-gallery.html images="./images/part_dims.png" height="350" alignment="center" %} 
