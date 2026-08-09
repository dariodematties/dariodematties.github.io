---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Engineering, [ Faculty of Engineering ](https://www.uba.ar/), University of Buenos Aires, 2020
  * Thesis: Early Language Acquisition in Cortical Dynamics, a Computational Approach.
  * Biologically inspired modelling for early language acquisition phenomena explanation.
  * High Performance Computing (HPC) for science. Project running on [ Cooley ](https://www.alcf.anl.gov/alcf-resources/cooley) resource at Argonne Leadership Computing Facility ([ ALCF ](https://www.alcf.anl.gov/)).
* B.S. in [ Mendoza Regional Faculty ](https://www.linkedin.com/company/utn-facultad-regional-mendoza/), National Technological University, 2012
  * Senior Thesis: Kalman Filter Implementation in FPGA, Reconfigurable Computation Laboratory.

Work experience
======
* May 2025 - present: AI Software Developer, Active Inference Team
  * StanhopeAI, London, United Kingdom
  * Duties include:
    * Developing probabilistic autonomy software for drone systems operating in GNSS-denied environments.
    * Applying Active Inference and the Free Energy Principle to perception, belief updating, planning, and action selection under uncertainty.
    * Designing state-space representations and generative models that integrate sensory evidence with predictive dynamics.
    * Implementing and evaluating autonomy algorithms in Python, MATLAB, and C/C++.
    * Contributing to multi-agent and swarm autonomy concepts for information sharing, coordinated decision making, and mission behavior under incomplete observations.

* Nov 2021 - Apr 2025: Postdoctoral researcher
  * Northwestern‑Argonne Institute of Science and Engineering ([ NAISE ](https://naise.northwestern.edu/))
  * Duties included: 
    * Self-supervised learning through Vision Transformers applied to label-scarce edge computing environments.
    * Self-supervised learning for full-sky cloud image characterization and ecosystem activity monitoring.
    * Federated and distributed learning workflows across edge devices and leadership-class HPC resources.
    * Development of PTZJEPA, a closed-loop active perception framework that combines a predictive world model with reinforcement-learning control of a pan-tilt-zoom (PTZ) camera.
    * Deployment of multimodal vision-language models, including Florence-2 and LLaVA, on Dell XR2 servers with NVIDIA T4 GPUs for edge inference.
  * Supervisor: [ Nicola J. Ferrier ](https://www.anl.gov/profile/nicola-j-ferrier)

* Apr 2020 ‑ Nov 2021: Postdoctoral researcher
  * [ CONICET ](https://www.conicet.gov.ar/scientific-and-technological-centers/) Mendoza Technological Scientific Center
  * Duties included:
    * Use of Deep Learning Frameworks for the implementation of self‑supervised contrastive learning of visual features through active foveated saccades.
    * Biologically inspired active foveated saccade visual system utilizing Transformers, ResNet and Deep Reinforcement Learning architectures.
    * Application of CNN and ResNet architectures for Nanopore Translocation feature extraction from noisy signals.
    * Application and adaptation of End‑to‑end object detection with Transformers (DETR) for detection of events in noisy signals
  * Supervisor: [ Alejandro Wainselboim ](https://scholar.google.com.ar/citations?user=CdVkS2cAAAAJ&hl=es)

* Apr 2012 ‑ Apr 2013: Research Intern
  * National Technological University
  * Duties included: Kalman Filter Numerical Tests in Matlab. Implementation in VHDL of resource and delay efficient matrix multiplication algorithms.
  * Technical Skills: Very High Speed Integrated Circuit (VHSIC) Hardware Description Language (VHDL), Matlab.
  * Supervisor: [ Rodrigo Gonzalez ](https://scholar.google.com/citations?user=xbQKMZsAAAAJ&hl=en)
  
Skills
======
* Autonomy and Robotics
  * Autonomous perception, GNSS-denied navigation, active vision
  * Predictive world models, uncertainty-aware decision making, embodied intelligence
  * Active Inference, Free Energy Principle, reinforcement learning
* Programming
  * Python (PyTorch, NumPy, Scikit‑learn, Pandas, DistributedDataParallel, h5py, etc.)
  * C/C++, MATLAB, Nvidia DALI
  * OpenMP, MPI, HDF5
* Deep Learning and Vision
  * Vision Transformers, CNNs, ResNet, DETR, DINO, VICReg, I-JEPA/JEPA
  * Florence-2, LLaVA, object detection, multimodal learning
* Distributed, Edge, and HPC Systems
  * PyTorch DistributedDataParallel, mpi4py, multi-GPU training
  * ALCF Polaris, ThetaGPU, Cooley
  * Edge inference on NVIDIA GPU platforms, Dell XR2/T4, CPU fallback deployment
* Miscellaneous
  * Linux, Shell (Bash)
  * LATEX(Overleaf/Markdown)
  * Git, GitHub, GitLab, CMake
  * Docker, Singularity/Apptainer, Venv
* Soft Skills
  * Time Management, Teamwork, Problem‑solving
  * Documentation, Engaging Presentation
  * Student advising

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Selected projects
======
* Predictive active vision: designed PTZJEPA, integrating joint-embedding predictive learning with autonomous pan-tilt-zoom control.
* GNSS-denied drone autonomy: developing Active Inference models for perception and decision making in aerial systems operating with uncertain or unavailable satellite positioning.
* Self-supervised vision at scale: implemented DINO, VICReg, and I-JEPA pipelines using Vision Transformers, distributed multi-GPU training, and environmental image datasets collected at edge sensing sites.
* Edge multimodal AI: deployed Florence-2 and LLaVA-based vision-language inference pipelines on constrained edge GPU systems for semantic interpretation of RGB and infrared imagery.
* Active foveated perception: built a reinforcement-learning visual agent that acquired self-supervised representations through sequential foveated observations.
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Nov 2023 - Feb 2025: Moderator and scientific coordinator for the [ Trillion Parameter Consortium (TPC) ](https://tpc.dev/tpc-seminar-series/) seminar series. [ TPC ](https://tpc.dev/) is an international community of nearly 1,000 participants from over 100 organizations including universities, research laboratories and institutes, and industry. TPC fosters collaborations toward the creation and responsible use of generative artificial intelligence in an open community and aspires to create a global network of resources and expertise that can help to grow that community.
