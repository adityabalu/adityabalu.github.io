---
layout: page
title: Neural PDE Solvers
description: Deep learning solutions for partial differential equations with theoretical bounds
img: assets/img/neural_pde.jpg
importance: 1
category: research
---

# Neural PDE Solvers for Engineering Applications

This research focuses on developing neural network-based solutions for partial differential equations (PDEs) that are common in engineering applications. Our work aims to combine the flexibility and computational efficiency of deep learning with the physical accuracy of traditional numerical methods.

## NeuFENet & Neural PDE Solvers for Irregular Domains (2024)

Our most recent contributions to this field include two major advances published in 2024:

### NeuFENet: Neural Finite Element Solutions with Theoretical Bounds

We developed NeuFENet, a neural network framework that provides finite element solutions with theoretical bounds for parametric PDEs. This approach offers several advantages over traditional numerical methods:

- **Theoretical Guarantees**: Our method provides rigorous error bounds, ensuring reliability in engineering applications
- **Fast Inference**: Once trained, models can generate solutions orders of magnitude faster than traditional FEM solvers
- **Parameter Space Exploration**: Efficient solving across a range of problem parameters

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/neu_fe_net.jpg' | relative_url }}" alt="NeuFENet Architecture" title="NeuFENet Architecture"/>
    </div>
</div>
<div class="caption">
    Architectural overview of our Neural Finite Element Network (NeuFENet), combining traditional FEM with neural networks.
</div>

### Neural PDE Solvers for Irregular Domains

Another significant challenge in computational engineering is handling irregular domains. We've developed neural PDE solvers specifically designed to handle complex geometries with:

- Automatic mesh generation capabilities
- Boundary condition enforcement
- Domain adaptation techniques

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/irregular_domains.jpg' | relative_url }}" alt="Irregular Domain Solutions" title="Neural PDE Solutions for Irregular Domains"/>
    </div>
</div>
<div class="caption">
    Examples of neural network solutions for PDEs on irregular domains, demonstrating the flexibility of our approach.
</div>

## Differentiable Spline Approximations (2021)

Before our work on NeuFENet, we developed a method for differentiable spline approximations, which provides:

- Smooth, differentiable representations of complex functions
- Integration with automatic differentiation frameworks
- Applications in surrogate modeling for engineering simulations

## Publications

Related publications from our group include:

1. Khara, B., Balu, A., Joshi, A., Sarkar, S., Hegde, C., Krishnamurthy, A., & Ganapathysubramanian, B. (2024). NeuFENet: Neural finite element solutions with theoretical bounds for parametric PDEs. Engineering with Computers, 1-23.

2. Khara, B., Herron, E., Jiang, Z., Balu, A., Yang, C. H., Saurabh, K., Jignasu, A., Sarkar, S., Hegde, C., Ganapathysubramanian, B., & Krishnamurthy, A. (2024). Neural PDE solvers for irregular domains. Computer-Aided Design, 172, 103709.

3. Cho, M., Balu, A., Joshi, A., Prasad, A.D., Khara, B., Sarkar, S., Ganapathysubramanian, B., Krishnamurthy, A., & Hegde, C. (2021). Differentiable Spline Approximations. Proceedings of the Neural Information Processing Systems.

## Current and Future Directions

We are continuing to expand this work in several directions:

- Multi-physics coupling
- Uncertainty quantification in neural PDE solutions
- Integration with traditional CAE workflows
- Real-time digital twins leveraging neural PDE solvers
- Application to large-scale engineering problems

For more information about our research or collaboration opportunities, feel free to contact me.