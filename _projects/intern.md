---
title: "Estimating Configuration Space Belief from Collision Checks for Motion Planning"
excerpt: "Intership, Carnegie Mellon University"
collection: projects
permalink: /projects/intern
---

For motion planning in high dimensional configuration spaces, a significant computational bottleneck is collision detection. This project aimed at reducing the expected number of collision checks by creating a belief model of the configuration space using results from collision tests. The robot's configuration space is assumed to be a continuous ambient space whereby neighbouring points tend to share the same collision state. This enabled the formulation of a probabilistic model that assigned to unevaluated configurations a belief estimate of being collision-free. We performed a detailed comparative analysis of various kNN methods and distance metrics used to evaluate C-space belief. We also proposed a weighting matrix in C-space to improve the performance of kNN methods. Moreover, we proposed a topological method that exploits the higher order structure of the C-space to generate a belief model. Our proposed topological method outperformed traditional kNN methods by achieving higher accuracy while being  computationally efficient. 

The project report is available <a href="/files/intern.pdf"> here</a>.