---
layout: page
title: Deep Learning for CAE
description: Machine learning frameworks to enhance computer-aided engineering workflows
img: assets/img/deep_learning_cae.jpg
importance: 2
category: research
---

# Deep Learning for Computer-Aided Engineering

Computer-Aided Engineering (CAE) has traditionally relied on physics-based solvers that, while accurate, can be computationally intensive. Our research aims to integrate deep learning methodologies into CAE workflows to enhance efficiency, enable new capabilities, and streamline the design process.

## Recent Advances (2023-2024)

### Latent Diffusion Models for Structural Component Design (2024)

Our recent work has explored using latent diffusion models for generating novel structural component designs:

- Conditional generation based on performance requirements
- Exploration of design spaces not accessible with traditional methods
- Integration with manufacturing constraints

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ldm_design.jpg' | relative_url }}" alt="Latent Diffusion Design Results" title="Latent Diffusion Models for Structural Design"/>
    </div>
</div>
<div class="caption">
    Examples of structural component designs generated using our latent diffusion model approach, published in Computer-Aided Design, 2024.
</div>

### Deep Learning-Based Topology Optimization (2023)

Topology optimization is a critical aspect of modern engineering design. We've developed deep learning approaches to accelerate this process:

- Multigrid topology optimization using convolutional neural networks
- Manufacturable designs with manufacturing constraints embedded in the optimization
- Significant speed improvements over traditional methods

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/topo_opt.jpg' | relative_url }}" alt="Topology Optimization Results" title="Deep Learning Topology Optimization Results"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/topo_process.jpg' | relative_url }}" alt="Optimization Process" title="Optimization Process Visualization"/>
    </div>
</div>
<div class="caption">
    Left: Results from our deep learning-based topology optimization showing different design outcomes. Right: Visualization of the optimization process over iterations.
</div>

### Direct Flow Simulation Using Point Clouds (2023)

We've developed methods for direct flow simulation using point cloud representations:

- Immersogeometric fluid flow and heat transfer analysis
- Enables simulation directly from scanned data without mesh generation
- GPU acceleration for real-time performance

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/point_cloud_flow.jpg' | relative_url }}" alt="Point Cloud Flow Simulation" title="Flow Simulation on Point Clouds"/>
    </div>
</div>
<div class="caption">
    Visualization of our direct immersogeometric fluid flow and heat transfer analysis on point cloud representations.
</div>

## Earlier Work (2021)

### Machine Learning Framework for Design and Manufacturing

We developed a comprehensive machine learning framework that supports decision-making in design and manufacturing processes. This framework leverages:

- **Deep learning models** for geometry representation and analysis
- **GPU acceleration** for real-time processing and visualization
- **Knowledge integration** to combine domain expertise with data-driven approaches

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/ml_framework.jpg' | relative_url }}" alt="ML Framework Architecture" title="Machine Learning Framework Architecture"/>
    </div>
</div>
<div class="caption">
    Overview of our machine learning framework for design and manufacturing, showing data flow and processing steps.
</div>

## Publications

Key publications in this area include:

1. Herron, E., Rade, J., Jignasu, A., Ganapathysubramanian, B., Balu, A., Sarkar, S., & Krishnamurthy, A. (2024). Latent diffusion models for structural component design. Computer-Aided Design, 171, 103707.

2. Balu, A., Rajanna, M.R., Khristy, J., Xu, F., Krishnamurthy, A., & Hsu, M.C. (2023). Direct immersogeometric fluid flow and heat transfer analysis of objects represented by point clouds. Computer Methods in Applied Mechanics and Engineering, 404(115742).

3. Rade, J., Jignasu, A., Herron, E., Corpuz, A., Ganapathysubramanian, B., Sarkar, S., Balu, A., & Krishnamurthy, A. (2023). Deep learning-based 3D multigrid topology optimization of manufacturable designs. Engineering Applications of Artificial Intelligence.

4. Balu, A., Ghadai, S., Young, G., Sarkar, S., & Krishnamurthy, A. (2021). A machine learning framework for decision support in design and manufacturing. Advances in Computing and Information in Engineering (ACIER), 2, 479-498.

5. Hsu, M.C., & Balu, A. (2023). Direct flow simulation of objects represented by point clouds. Frontiers in Computational Fluid-Structure Interaction and Flow Simulation: Research from Lead Investigators Under Forty-2023, 119-153.

## Current and Future Work

We continue to develop this research in several exciting directions:

- Integration with AR/VR for interactive design
- Multi-objective optimization with user preferences
- Adaptive learning systems for manufacturing process control
- Uncertainty quantification in ML-enhanced CAE
- Real-time digital twins for manufacturing processes

For more information or collaboration opportunities, please reach out.
