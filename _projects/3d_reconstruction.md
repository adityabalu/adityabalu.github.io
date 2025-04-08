---
layout: page
title: 3D Reconstruction of Plants
description: Novel techniques for 3D reconstruction of plants using computer vision and machine learning
img: assets/img/plant_reconstruction.jpg
importance: 4
category: research
---

# 3D Reconstruction of Plants

Our research in 3D plant reconstruction aims to develop novel methods for accurately capturing and representing plant geometry in field conditions. These reconstructions are essential for various applications including phenotyping, growth monitoring, and precision agriculture.

## Neural Radiance Fields (NeRFs) for Plant Reconstruction (2024)

In our most recent work, we've applied Neural Radiance Fields (NeRFs) to the challenging problem of 3D plant reconstruction in field conditions:

- Advanced neural rendering techniques for complex plant structures
- Robust to challenging outdoor lighting conditions
- Detailed capture of fine plant features like stems and leaves
- Evaluation of reconstruction quality against ground truth measurements

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/nerf_plants.jpg' | relative_url }}" alt="NeRF Plant Reconstruction" title="NeRF-based Plant Reconstruction"/>
    </div>
</div>
<div class="caption">
    3D reconstruction of plants using Neural Radiance Fields (NeRFs) in field conditions, published in Plant Phenomics, 2024.
</div>

## 3D Reconstruction with Probabilistic Voxel Carving (2023)

We developed a probabilistic voxel carving approach for 3D plant reconstruction that:

- Uses multi-view images to reconstruct complete plant structures
- Incorporates uncertainty quantification in the reconstruction process
- Achieves higher accuracy compared to traditional methods
- Works effectively in real-world agricultural settings

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/voxel_carving.jpg' | relative_url }}" alt="Probabilistic Voxel Carving" title="Probabilistic Voxel Carving Results"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/plant_models.jpg' | relative_url }}" alt="Reconstructed Plant Models" title="3D Plant Models from Voxel Carving"/>
    </div>
</div>
<div class="caption">
    Left: Visualization of our probabilistic voxel carving process for 3D plant reconstruction. Right: Resulting 3D plant models.
</div>

## Publications

Key publications in this area include:

1. Arshad, M.A., Jubery, T., Afful, J., Jignasu, A., Balu, A., Ganapathysubramanian, B., Sarkar, S., & Krishnamurthy, A. (2024). Evaluating neural radiance fields (NeRFs) for 3D plant geometry reconstruction in field conditions. Plant Phenomics, 6(0235), 1-17.

2. Feng, J., Saadati, M., Jubery, T., Jignasu, A., Balu, A., Li, Y., Attigala, L., Schnable, P., Sarkar, S., Ganapathysubramanian, B., & Krishnamurthy, A. (2023). 3D reconstruction of plants using probabilistic voxel carving. Computers and Electronics in Agriculture, 213, 108248.

## Applications

The 3D plant reconstruction methods we've developed have applications in:

- High-throughput plant phenotyping
- Crop monitoring and growth analysis
- Precision agriculture
- Disease detection and stress monitoring
- Yield prediction and optimization

## Current and Future Work

We are continuing to advance this research in several directions:

- Temporal modeling of plant growth using 4D reconstruction
- Integration with genetic and environmental data
- Deployment on mobile platforms for in-field use
- Fusion of multiple sensing modalities (RGB, hyperspectral, thermal)
- Automated trait extraction from 3D models

For more information or collaboration opportunities in plant reconstruction, please reach out.