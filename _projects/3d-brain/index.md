---
layout: post
title: 3D Printing an MRI Brain Scan
description:  A friend of mine got an MRI of their brain so I offered to 3D print it for them.

skills: 
- 3D Printing
- 3D Slicer
- MeshMixer

main-image: /3d-brain.jpg
main-image-class: img-cover
---

---
## Objectives

The goal of this project was to 3D print a detailed model of my friend's brain for their enjoyment and a desk decoration.

## Outcomes

{% include image-gallery.html images="./images/3d-brain.jpg, ./images/3d-brain2.jpg, ./images/brain-bottom.jpg" height="300" alignment="center" %} 

## Methods Used

The MRI data came in a DICOM format which I had to slice using 3D slicer. The scan data also imaged my friend's skull so I had to use the software to also segment the images and separate the brain from the rest of the head. After some model cleaning and refining, I exported the data to MeshMixer where I did some further cleaning to reduce the file size as the scan data had a much higher resolution than needed. Finally, I exported the brain model in 3 layers so I can 3D print each piece individually before assembling it into a single, high-quality model.

{% include image-gallery.html images="./images/printing.jpg, ./images/brain-top-half.jpg" height="300" alignment="center" %} 
