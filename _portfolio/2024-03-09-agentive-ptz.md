---
title: "PTZJEPA: Predictive Active Vision for Autonomous Visual Data Collection"
excerpt: "A closed-loop active perception framework that combines self-supervised predictive world models with reinforcement-learning control of pan-tilt-zoom (PTZ) cameras.<br/><img src='/images/Agentive_PTZ.png'>"
collection: portfolio
---

PTZJEPA is a closed-loop active perception framework that combines a predictive world model with reinforcement-learning control of a pan-tilt-zoom camera. The goal is to give visual sensing systems agency: instead of passively processing a fixed stream of images, the camera learns where to look next and adapts its data acquisition strategy to the visual environment.

The project integrates image-based joint-embedding predictive learning ([I-JEPA](https://arxiv.org/abs/2301.08243)) with reinforcement-learning control inspired by [Dreamer](https://arxiv.org/abs/2206.14176). The agent learns predictive latent dynamics and uses them to choose camera movements that acquire informative observations. This links perception, prediction, and action in a single autonomous visual data collection loop.

Applications include autonomous high-resolution scanning, environmental sensing, edge AI, robotic perception, and other domains where an embodied sensor must collect useful data under bandwidth, compute, or field-of-view constraints.

<video controls preload="metadata" style="width: 100%; max-width: 900px;">
  <source src="/files/Dario_Dematties_Towards_Self_Supervised_Learning_at_the_Edge.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
