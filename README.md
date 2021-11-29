This repository presents our data on inverse rendering with light field camera

[Paper preprint (PDF)](paper-preprint.pdf) | [Visualisation 1](TBD) | [Visualisation 2](TBD) | [Visualisation 3](TBD) | [Visualisation 4](TBD) 

# Abstract 
We propose an inverse rendering model for light fields to recover surface normals, depth, reflectance and natural illumination. Our setting is fully uncalibrated, with the reflectance modeled with a spatially-constant Blinn-Phong model and illumination as an environment map. While previous work makes strong assumptions in this difficult scenario, focusing solely on specific types of objects like faces or imposing very strong priors, our approach leverages only the light field structure, where a solution consistent across all subaperture views is sought. The optimization is based primarily on shading, which is sensitive to fine geometric details which are propagated to the initial coarse depth map. Despite the problem being inherently ill-posed, we achieve encouraging results on synthetic as well as real-world data.

# Supplementary

All videos show a series of images where the left top image is the input image and ground truth, the right top re-rendered image with the estimated parameters (normals, BRDF and illumination). The left bottom image shows a sphere that is rendered with ground truth illumination and BRDF and the right image shows the same sphere geometry as the right but rendered with estimated BRDF and illumination. Each consecutive frame is rendered with a sliding envmap.

## Arria, gold-paint BRDF, envmap natural illumination 
![Visualisation 1](supplementary/thumbnails/Visualisation1.png "Visualisation")

[Visualisation 1](supplementary/Visualisation1.mp4)

  ## Arria, pure-rubber BRDF, terrace natural illumination 
![Visualisation 2](supplementary/thumbnails/Visualisation2.png)

[Visualisation 2](supplementary/Visualisation2.mp4)

# Lochardil, silver-metallic-paint BRDF, terrace illumination
![Visualisation 3](supplementary/thumbnails/Visualisation3.png)

[Visualisation 3](supplementary/Visualisation3.mp4)

# Lochardil, teflon BRDF, doge2 illumination
![Visualisation 4](supplementary/thumbnails/Visualisation4.png)

[Visualisation 4](supplementary/Visualisation4.mp4)


# Data 
💪 TBD
