# awesome_diffusion_mani_humans
This repo is a collection of works in the intersection of diffusion, dexterous manipulation, human action synthesis works mostly for the purpose of transferring skills to embodied agents. The author of this repo sees some intimate links between them, and subsequently decided to make a github page with these.

## Table of Contents

- [Awesome diffusion manipulation and human action synthesis works](#awesome_diffusion_mani_humans)
  - [Table of Contents](#table-of-contents)
  - [Dexterous manipulation](#Dexterous manipulation)
    - [2024](#2024)
  - [Diffusion policy](#Diffusion policy)
    - [2024](#2024) 
  - [License](#license)

![image info](./welcome.png)

---
## Dexterous manipulation

### 2024

- [](https://arxiv.org/abs/2403.03954)
  - Tsung-Wei Ke† Nikolaos Gkanatsios† Katerina Fragkiadaki
  - Key: 3D Diffuser Actor, visual imitation learning
  - Github: 3d-diffuser-actor.github.io
  - ExpEnv: RLBench, CALVIN

## Diffusion Policy

### 2024

- [3D Diffuser Actor: Policy Diffusion with 3D Scene Representations](https://arxiv.org/abs/2403.03954)
  - Tsung-Wei Ke† Nikolaos Gkanatsios† Katerina Fragkiadaki
  - Key: 3D Diffuser Actor, visual imitation learning
  - Github: 3d-diffuser-actor.github.io
  - ExpEnv: RLBench, CALVIN
  - Abstract: Diffusion policies are conditional diffusion models that learn robot action distributions conditioned on the robot and environment state. They have recently shown to outperform both deterministic and alternative action distribution learning formulations. 3D robot policies use 3D scene feature representations aggregated from a single or multiple camera views using sensed depth. They have shown to generalize better than their 2D counterparts across camera viewpoints. We unify these two lines of work and present 3D Diffuser Actor, a neural policy equipped with a novel 3D denoising transformer that fuses information from the 3D visual scene, a language instruction and proprioception to predict the noise in noised 3D robot pose trajectories. 3D Diffuser Actor sets a new state-of-the-art on RLBench with an absolute performance gain of 18.1% over the current SOTA on a multi-view setup and an absolute gain of 13.1% on a single-view setup. On the CALVIN benchmark, it improves over the current SOTA by a 9% relative increase. It also learns to control a robot manipulator in the real world from a handful of demonstrations. Through thorough comparisons with the current SOTA policies and ablations of our model, we show 3D Diffuser Actor’s design choices dramatically outperform 2D representations, regression and classification objectives, absolute attentions, and holistic non-tokenized 3D scene embeddings.
    
- [3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations](https://arxiv.org/abs/2403.03954)

## License

Awesome Diffusion Model in RL is released under the Apache 2.0 license.
