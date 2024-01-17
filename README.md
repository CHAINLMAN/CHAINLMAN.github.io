# Ph.D. Candidate	

Phone: (+86) 188-0012-6636
College of Engineering	
Email: jcq@pku.edu.cn 
Peking University, China	


#### Research Interest: 
Cooperative State Estimation,	Algebraic Riccati Equation,	Multi-Agent System,

Cooperative Control,	Data-Driven Control	


## Education
- Ph.D. Candidate,	Dynamical Systems and Control | College of Engineering, Peking University, September 2019 - present.
Supervisor: Prof. Zhisheng Duan.
- B.S.,	Theoretical and Applied Mechanics | College of Engineering, Peking University, September 2015 - July 2019.

## Work Experience
**Data Scientist @ Toyota Financial Services (_June 2022 - Present_)**
- Uncovered and corrected missing step in production data pipeline which impacted over 70% of active accounts
- Redeveloped loan originations model which resulted in 50% improvement in model performance and saving 1 million dollars in potential losses

**Data Science Consultant @ Shawhin Talebi Ventures LLC (_December 2020 - Present_)**
- Conducted data collection, processing, and analysis for novel study evaluating the impact of over 300 biometrics variables on human performance in hyper-realistic, live-fire training scenarios
- Applied unsupervised deep learning approaches to longitudinal ICU data to discover novel sepsis sub-phenotypes

## Projects
### Data-Driven EEG Band Discovery with Decision Trees
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Decoding Physical and Cognitive Impacts of Particulate Matter Concentrations at Ultra-Fine Scales
[Publication](https://www.mdpi.com/1424-8220/22/11/4240)

Used **Matlab** to train over 100 machine learning models which estimated particulate matter concentrations based on a suite of over 300 biometric variables. We found biometric variables can be used to accurately estimate particulate matter concentrations at ultra-fine spatial scales with high fidelity (r2 = 0.91) and that smaller particles are better estimated than larger ones. Inferring environmental conditions solely from biometric measurements allows us to disentangle key interactions between the environment and the body.

![Bike Study](/assets/img/bike_study.jpeg)

## Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019

- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)
![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)
## Publications
**Journal Paper**
1.	J. Qian, P. Duan, and Z. Duan, Harmonic-copuled Riccati equations and its applications in distributed filtering. (Provisionally accepted as Regular Paper by IEEE TAC)
2.	J. Qian, Z. Duan, P. Duan, and Z. Li, Observation of periodic systems: Bridge centralized Kalman filtering and consensus-based distributed filtering, IEEE Transactions on Automatic Control, in press, Jun. 2023.
3.	J. Qian, P. Duan, Z. Duan, and L. Shi, Event-triggered distributed state estimation: A conditional expectation method, IEEE Transactions on Automatic Control, vol.68, no.10, pp. 6361-6368, Oct. 2023.
4.	J. Qian, P. Duan, Z. Duan, G. Chen, and L. Shi, Consensus-based distributed filtering with fusion step analysis, Automatica, vol. 142, pp. 110408, 2022.
5.	P. Duan, J. Qian, Q. Wang, Z. Duan and L. Shi, Distributed state estimation for continuous-time linear systems with correlated measurement noise, IEEE Transactions on Automatic Control, vol. 67, no. 9, pp. 4614-4628, 2022. (Full paper)
6.	J. Qian, P. Duan and Z. Duan, Fully distributed filtering with a stochastic event-triggered mechanism, IEEE Transactions on Control of Network Systems, vol. 9, no. 2, pp. 753-762, 2022.
 
**Conference Paper**
1.	P. Duan, J. Qian, Y. Lv, and T. Liu, Self-organization output regulation control, The 5th IEEE International Conference on Unmanned Systems, Guangzhou, China, 2022. (Best Paper Award)
2.	Z. Li, J. Qian and Z. Duan, Distributed multi-layer time-varying output formation tracking control for heterogeneous linear multiagent systems, Proceedings of the 33rd Chinese Control and Decision Conference, Yunnan, 2021.
3.	J. Qian, P. Duan, and Z. Duan, Optimal observation geometry analysis for multi-Sensor system in 3D case, International Conference on Guidance, Navigation and Control, Tianjin, 2020. 

## Awards
-	Best Paper Award, IEEE ICUS 2022
-	National Scholarship, 2023
-	President Scholarship, Peking University
- Top Ten Student Scholars, College of Engineering, Peking University
-	Benz Scholarship, Peking University
-	May Fourth Scholarship, Peking University



## Journal Review

- Automatica
- IEEE Transactions on Automatic Control
- IEEE Transactions on Control of Network Systems
- IEEE Transactions on Cybernetics
- IEEE Transactions on Systems, Man, and Cybernetics: Systems
- International Journal of Robust and Nonlinear Control



## Main Research

**Harmonic-Coupled Riccati Equations and its Applications in Distributed Filtering**

One of the common problems in distributed filtering is the lack of mathematical tools to reveal the steady-state performance of filtering algorithm with weak local observability. In this work, we managed to formulate a novel kind of matrix equations called harmonic-coupled Riccati equations (HCRE), which contains multiple Riccati-like matrix equations with solutions coupled using harmonic means. We first manage to discover conditions for the existence and uniqueness of solutions to HCRE, then find an iterative law with low computation-complexity to obtain the unique group of solutions. Based on this newly established mathematical tool, we further formulate the closed-form expression of the steady-state estimation error covariance of consensus-on-information-based distributed filtering (CIDF) algorithm into the solution to a discrete-time Lyapunov equation (DLE). This leads to a significant conservativeness reduction of traditional performance evaluation techniques for CIDF. The obtained results are remarkable since they not only enrich the theory of coupled Riccati equations, but also provide a novel insight into the synthesis and analysis of distributed filtering algorithms. 

**Optimality Analysis: Bridging the Centralized Kalman Filtering and Consensus-based Distributed Filtering**

For consensus-based distributed filtering, one common view is that through infinite consensus fusion operations during each sampling interval, each node in the sensor network can achieve optimal filtering performance with centralized filtering. However, due to the limited communication resources in physical systems, the number of fusion steps cannot be infinite. Due to the lack of enough mathematical tools, the literature is not able to clearly describe the effect of finite fusion step on the performance of distributed filtering algorithm, especially on the gap between distributed and centralized filtering. In this work, we concentrate on the optimality analysis of consensus-based filtering, especially the performance degradation analysis of consensus-on-measurement-based filtering (CMDF) algorithm with finite consensus fusion operations. First, by introducing a modified discrete-time algebraic Riccati equation and several novel techniques, we demonstrate that the convergence of the estimation error covariance matrix with the increase of time step is guaranteed under a collective observability condition. In particular, the steady-state covariance matrix can be simplified as the solution to a discrete-time Lyapunov equation. Moreover, we manage to formulate the performance degradation induced by reduced fusion frequency in the infinite series form, which establishes an analytical gap between the performance of the CMDF with finite fusion steps and that of centralized filtering. Meanwhile, this gap also provides a trade-off between the filtering performance and the communication cost. We further show that the steady-state estimation error covariance matrix exponentially converges to the centralized optimal steady-state performance with fusion operations tending to infinity during each sampling interval, and the convergence speed is not slower than the norm of the second largest eigenvalue of the adjacency matrix corresponding to the communication topology. 

## Future Work
**Data-Driven Cooperative Control**

**The Information Fusion social network**

- [Data Science Blog](https://medium.com/@shawhin)
