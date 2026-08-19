---
permalink: /
title: "Arjav Poudel"
author_profile: true
redirect_from:
  - /about/
  - /about.html
classes: wide
---

 Hi, I'm Arjav!

I recently graduated with first class honours in Artificial Intelligence from the University of Edinburgh. My work/interests sit at the intersection of deep learning and computational cognitive science. I am fascinated by how we can build models that don't just generate plausible data, but actually understand the underlying physical laws of the systems they represent.

During my Honours research, I asked a fundamental question: *Can diffusion models recover the actual physical laws of a dynamical system, or do they merely mimic the output?* Using the Ornstein-Uhlenbeck process as a controlled testbed, I discovered and analytically proved an *Invariance Problem*. I found that naively combining a diffusion model with a dynamical-system component causes the model to secretly absorb the physics into its own weights, making the true dynamics unrecoverable. Crucially, this was a failure entirely invisible to standard training diagnostics such as train test loss curves. 

To solve this, I proposed a restructured architecture that constrains the information the diffusion model receives, allowing us to reliably extract the governing dynamics with zero added computational cost and no assumptions about the data distribution.

Beyond theoretical research, I love taking machine learning concepts and applying them to high-impact engineering and physical challenges:

*   **Accelerating Fusion Energy (UKAEA):** As an ML Engineer Intern at the UK Atomic Energy Authority, I focused on experimental validation for fusion technology. I engineered and deployed *Icarus-Fusion* (now an open-source tool on PyPI), implementing diverse architectures like PINNs, GANs, and CNNs to predict simulation discrepancies. This physics-informed approach reduced validation time by 95%, improved accuracy by 30%, and contributed directly to accelerating fusion reactor component development.
*   **Autonomous Robotic Manipulation (HumanEd):** As Head of Computer Vision at HumanEd, I led the development of an advanced bio-mimetic hand. By combining image classification, object detection, and deep reinforcement learning, my team built generalized infrastructure capable of autonomously solving a Rubik's cube using purely visual inputs, bypassing the need for specialized embedded sensors.


Also, I am always exploring new ways AI can intersect with human interaction and accessibility. 

*  I Developed a devanagari recognition tool achieving 97% accuracy on handwritten Nepali characters. I built this as a real-time interface to support language learning for underserved Nepali communities in the UK.
*  I Conducted comparative research on Brain-Computer Interfaces (BCIs) with the University of St. Andrews HCI team, evaluating neuronal recording scales, spatio-temporal resolution, and surgical invasiveness.



I also have a [blog](/year-archive/) where i share a mixture of technical posts and general musings.