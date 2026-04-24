---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

## Learning Hierarchical Policies in Dynamic Environments

**Advisor: Prof. Ruslan Salakhutdinov, School of Computer Science, CMU**

<img src="/images/drl.png" alt="Hierarchical RL locomotion environment" style="max-width: 500px; display: block; margin: 20px auto;">

This project tackled the challenge of solving sparse-reward locomotion tasks in dynamic environments where terrain friction and agent morphology vary unpredictably. We proposed a hierarchical meta-RL framework that combines MAML-based skill learning at the lower level with a high-level master policy that selects and composes these skills. The lower-level sub-policies are meta-trained across a distribution of environment configurations, enabling rapid adaptation to new dynamics at test time. The high-level policy learns to sequence these skills to navigate complex maze-like environments. We demonstrated that MAML-trained sub-policies achieve up to 2x higher task success rate and significantly fewer steps compared to pre-trained policies across challenging environment configurations.

[<a href="/files/drl_report.pdf">Report</a>]

---

## Deep Reinforcement Learning for Sparse-Reward Manipulation Problems

**Advisor: Prof. Matt Mason, School of Computer Science, CMU**

<img src="/images/pher.png" alt="Fetch robot manipulation with Hindsight Experience Replay" style="max-width: 500px; display: block; margin: 20px auto;">

In multi-goal robotic manipulation tasks, sparse reward signals make learning extremely difficult — the agent receives no useful feedback until it accidentally achieves a goal. Hindsight Experience Replay (HER) addresses this by relabeling failed trajectories with achieved goals, but treats all replayed transitions equally. We proposed Prioritized Hindsight Experience Replay (PHER), which combines HER with TD-error-based transition prioritization and importance sampling to focus learning on the most informative transitions. We evaluated PHER on 7-DOF Fetch robot manipulation tasks in OpenAI Gym, including pick-and-place and push, demonstrating improved learning speed and higher task success rates compared to standard HER.

[<a href="/files/pher_report.pdf">Report</a>]
