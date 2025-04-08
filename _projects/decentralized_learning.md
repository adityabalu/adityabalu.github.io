---
layout: page
title: Decentralized Learning
description: Communication-efficient distributed machine learning for edge computing
img: assets/img/decentralized_learning.jpg
importance: 3
category: research
---

# Decentralized Learning for Edge Computing Applications

The increasing deployment of edge devices and the need for privacy-preserving machine learning have made decentralized learning an important research area. Our work focuses on developing communication-efficient algorithms for training deep learning models across distributed nodes without requiring a central coordinator.

## DIMAT: Decentralized Iterative Merging-and-Training (2024)

Our latest work, DIMAT (Decentralized Iterative Merging-and-Training), provides a novel framework for efficient decentralized deep learning:

- Iterative model merging with local training phases
- Theoretical convergence guarantees
- Adaptability to various network topologies
- Significant reduction in communication overhead

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dimat.jpg' | relative_url }}" alt="DIMAT Architecture" title="DIMAT Architecture"/>
    </div>
</div>
<div class="caption">
    Architectural overview of our Decentralized Iterative Merging-and-Training (DIMAT) approach presented at CVPR 2024.
</div>

## Cross-Gradient Aggregation for Non-IID Data (2021)

A significant challenge in decentralized learning is dealing with non-Independent and Identically Distributed (non-IID) data. We've addressed this with Cross-Gradient Aggregation:

- Handles data heterogeneity across distributed nodes
- Maintains model accuracy despite data distribution differences
- Supports personalization while enabling collaborative learning

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cross_gradient.jpg' | relative_url }}" alt="Cross-Gradient Aggregation" title="Cross-Gradient Aggregation Process"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/convergence.jpg' | relative_url }}" alt="Convergence Comparison" title="Convergence Comparison with Baseline Methods"/>
    </div>
</div>
<div class="caption">
    Left: Visualization of our Cross-Gradient Aggregation approach for non-IID data. Right: Convergence comparison with baseline decentralized learning methods.
</div>

## Momentum-Based Decentralized Policy Gradient Tracking (2022)

We have developed MDPGT (Momentum-based Decentralized Policy Gradient Tracking), a novel algorithm for reinforcement learning in decentralized settings:

- **Communication efficiency**: Reduces network bandwidth requirements
- **Faster convergence**: Leverages momentum to accelerate training
- **Robustness**: Maintains performance even with unreliable network connections

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/mdpgt.jpg' | relative_url }}" alt="MDPGT Architecture" title="MDPGT Architecture"/>
    </div>
</div>
<div class="caption">
    Architectural overview of our Momentum-based Decentralized Policy Gradient Tracking (MDPGT) approach.
</div>

## Publications

Key publications in this research area include:

1. Saadati, N., Pham, M., Saleem, N., Waite, J.R., Balu, A., Jiang, Z., Hegde, C., & Sarkar, S. (2024). DIMAT: Decentralized Iterative Merging-and-Training for Deep Learning Models. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 27517-27527.

2. Jiang, Z., Lee, X.Y., Tan, S.Y., Tan, K.L., Balu, A., Lee, Y.M., Hegde, C., & Sarkar, S. (2022). MDPGT: Momentum-based Decentralized Policy Gradient Tracking. Proceeding of AAAI Conference on Artificial Intelligence.

3. Esfandiari, Y., Tan, S.Y., Jiang, Z., Balu, A., Herron, E., Hegde, C., & Sarkar, S. (2021). Cross-gradient Aggregation for Decentralized Learning from Non-IID Data. Proceedings of the 38th International Conference on Machine Learning, 3036-3046.

## Applications and Future Work

Our decentralized learning research has applications in:

- Agricultural IoT networks
- Federated medical image analysis
- Privacy-preserving collaborative AI
- Edge computing for autonomous systems

We are currently extending this work to incorporate differential privacy guarantees, adaptive communication protocols, and heterogeneous device capabilities.