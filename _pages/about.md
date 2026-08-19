---
permalink: /
title: "Arjav Poudel"
author_profile: true
redirect_from:
  - /about/
  - /about.html
classes: wide
---

# AI/ML Engineer & Researcher

BSc Artificial Intelligence (First Class Honours) graduate from the University of Edinburgh, specialising in Diffusion Models and Computational Cognitive Science.

## Education

**BSc Artificial Intelligence (First Class Honours)** — University of Edinburgh, 2026

## Research

### Honours Project: Diffusion Modelling of Dynamical Systems
**September 2025 – May 2026** | University of Edinburgh

Investigated whether diffusion models can recover the underlying physical laws of a system, rather than merely generating data that looks plausible. Studied in a controlled setting — the Ornstein-Uhlenbeck process, a model of any quantity that fluctuates randomly while being pulled toward a resting value (e.g. a particle's velocity in a fluid, or a neuron's membrane potential) — where the governing physics are known exactly, encoded in a single relaxation matrix, A.

- Identified and proved analytically that naively combining a diffusion model with a dynamical-system component causes an **Invariance Problem**: the diffusion model absorbs the system's physics into its own weights, rendering the true dynamics unrecoverable — a failure invisible to standard training diagnostics.
- Demonstrated this failure empirically across a range of physical systems and data dimensionalities
- Proposed a restructured architecture that constrains what information the diffusion model receives as input, reliably recovering the governing dynamics with no additional computational cost and no assumptions about the form of the data distribution

## Professional Experience

### ML Engineer Summer Intern — UKAEA
**June 2024 – August 2024** | Culham, UK

Developed innovative machine learning solutions for experimental validation in fusion technology, focusing on emerging physics-informed approaches.

- Engineered and deployed **Icarus-Fusion**, an open-source ML tool on PyPI that revolutionizes experimental validation processes
- Implemented 4 diverse model architectures (MLPs, CNNs, GANs, PINNs) to predict discrepancies between simulations and ground truth data
- Achieved **95% reduction in validation time** and **30% improvement in prediction accuracy** compared to traditional methods
- Co-authoring scientific paper on physics-informed ML techniques, enabling UKAEA to reduce physical testing by 40%
- Accelerated fusion reactor component development by 3-6 months, contributing to sustainable fusion energy goals

### Head of Computer Vision — HumanEd
**September 2024 – August 2026** | Edinburgh, UK

Led development of an advanced bio-mimetic hand using computer vision and deep reinforcement learning to autonomously solve Rubik's cubes.

- Managed Computer Vision team leveraging image classification, object detection, and scene segmentation
- Deployed generalized infrastructure capable of solving cube puzzles without specialized sensors
- Built upon OpenAI's previous sensor-embedded approach to push boundaries of autonomous manipulation

## Selected Projects

### Nepali Handwritten Character Recognition System
Developed a CNN-based model in PyTorch achieving **97% accuracy** on handwritten Nepali character recognition with limited training data. Built real-time recognition software to support language learning for underserved Nepali communities in the UK.

### Facial Recognition ML Voice Assistant
Designed AI voice assistant integrating OpenCV facial recognition with GPT-3 and Flask. Implemented computer vision with NLP using asynchronous request methods for smooth user experience.

### Brain-Computer Interface Research
Conducted research with University of St. Andrews HCI team evaluating BCI applications. Performed comparative analysis using metrics including neuronal recording scale, spatio-temporal resolution, and surgical invasiveness. Earned Distinction for Scottish Baccalaureate in Science.

## Technical Expertise

**Languages:** Python, Java, C, SQL, Swift, JavaScript
**Frameworks:** PyTorch, OpenCV, Pandas, NumPy, Django, Matplotlib
**Specializations:** Diffusion Models, Deep Learning, Computer Vision, Physics-Informed ML, Computational Neuroscience, Dynamical Systems, GANs, CNNs, Foundation Models, Scientific Computing, High-Performance Computing

---

I occasionally write about AI, machine learning, and technology on my [blog](/year-archive/).
