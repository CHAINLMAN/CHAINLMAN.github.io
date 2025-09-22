---  
layout: default
title: Research
nav_order: 3
permalink: /research/
---

## Main Research

**Harmonic-Coupled Riccati Equations and its Applications in Distributed Filtering**

One of the common problems in distributed filtering is the lack of mathematical tools to reveal the steady-state performance of filtering algorithms with weak local observability. In this work, we managed to formulate a novel kind of matrix equations called harmonic-coupled Riccati equations (HCRE), which contains multiple Riccati-like matrix equations with solutions coupled using harmonic means. We first manage to discover conditions for the existence and uniqueness of solutions to HCRE, then find an iterative law with low computational complexity to obtain the unique group of solutions. Based on this newly established mathematical tool, we further formulate the closed-form expression of the steady-state estimation error covariance of the consensus-on-information-based distributed filtering (CIDF) algorithm into the solution to a discrete-time Lyapunov equation (DLE). This leads to a significant reduction in the conservativeness of traditional performance evaluation techniques for CIDF. The obtained results are remarkable since they not only enrich the theory of coupled Riccati equations but also provide a novel insight into the synthesis and analysis of distributed filtering algorithms. 
![Communication Topology](/assets/img/HCRE.png)

**Optimality Analysis: Bridging the Centralized Kalman Filtering and Consensus-based Distributed Filtering**

For consensus-based distributed filtering, one standard view is that through infinite consensus fusion operations during each sampling interval, each node in the sensor network can achieve optimal filtering performance with centralized filtering. However, due to the limited communication resources in physical systems, the number of fusion steps cannot be infinite. Due to the lack of sufficient mathematical tools, the literature is unable to clearly describe the effect of a finite fusion step on the performance of the distributed filtering algorithm, especially on the gap between distributed and centralized filtering. In this work, we concentrate on the optimality analysis of consensus-based filtering, especially the performance degradation analysis of the consensus-on-measurement-based filtering (CMDF) algorithm with finite consensus fusion operations. First, by introducing a modified discrete-time algebraic Riccati equation and several novel techniques, we demonstrate that the convergence of the estimation error covariance matrix with the increase of time step is guaranteed under a collective observability condition. In particular, the steady-state covariance matrix can be simplified as the solution to a discrete-time Lyapunov equation. Moreover, we manage to formulate the performance degradation induced by reduced fusion frequency in the infinite series form, which establishes an analytical gap between the performance of the CMDF with finite fusion steps and that of centralized filtering. Meanwhile, this gap also provides a trade-off between the filtering performance and the communication cost. We further show that the steady-state estimation error covariance matrix exponentially converges to the centralized optimal steady-state performance with fusion operations tending to infinity during each sampling interval, and the convergence speed is not slower than the norm of the second largest eigenvalue of the adjacency matrix corresponding to the communication topology. 
![Ratio](/assets/img/Optimal.png)
