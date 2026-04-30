---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

📄 A PDF version of this CV is available [here](/files/Nazanin_Amini_CV.pdf).

Education
======
* **Ph.D. in Computer Science**, University of Texas at San Antonio (UTSA), 2025 – Present
  * Advisor: Dr. Kevin Desai
  * Research: diffusion models, vision-language integration, human motion generation
* **M.Sc. in Electrical Engineering (Communication Systems)**, Shiraz University, 2022
  * Thesis: *Background Subtraction in Video under Challenging Real-World Conditions*
* **B.Sc. in Electrical Engineering**, Shiraz University, 2018
  * Ranked 3rd in graduating cohort by GPA

Research Interests
======
* **Generative modeling** — diffusion models, score-based methods, controllable & conditional generation
* **Vision-language models** — CLIP-style multimodal representations, text-conditioned generation
* **Human motion generation** — text-to-3D-motion synthesis, motion style transfer
* **Computer vision** — semantic segmentation, object detection, video understanding
* **Knowledge distillation** — teacher-student frameworks, self-distillation

Research Experience
======
* **2025 – Present** &nbsp;&nbsp; *Graduate Research Assistant*, [Klab](https://klab.cs.utsa.edu/), University of Texas at San Antonio
  * Working with Dr. Kevin Desai on diffusion-based generative models and vision-language integration for controllable 3D content generation.
* **2020 – 2022** &nbsp;&nbsp; *Graduate Researcher*, Image Processing & Machine Vision Lab, Shiraz University
  * M.Sc. thesis on background subtraction; designed pipelines robust to dynamic backgrounds, illumination changes, and shadow artifacts.
* **2019 – 2020** &nbsp;&nbsp; *Research Assistant*, Communication Systems Lab, Shiraz University
  * Investigated signal-processing methods for wireless and adaptive communication.
* **2018 – 2019** &nbsp;&nbsp; *Undergraduate Researcher*, Transportation Research Group, Shiraz University
  * Applied data analysis and modeling techniques to traffic and transportation datasets.

Selected Projects
======
* **Text-conditioned 3D human motion generation with diffusion + style transfer** — Designing diffusion models trained on the [HumanML3D](https://github.com/EricGuo5513/HumanML3D) dataset to synthesize 3D motion from natural-language prompts; exploring CLIP-conditioned guidance and motion style transfer.
* **WGAN-GP for image generation** — Implemented Wasserstein GAN with gradient penalty in PyTorch; studied training stability and mode coverage on standard image benchmarks.
* **Semantic segmentation with DeepLabV3+** — Trained and evaluated DeepLabV3+ for dense scene labeling; analyzed atrous spatial pyramid pooling and encoder-decoder design choices.
* **Vision Transformer (ViT) from scratch** — Built a Vision Transformer in PyTorch and benchmarked it against CNN baselines on image classification.
* **YOLOv3 object detection** — Implemented and fine-tuned YOLOv3 for real-time object detection; explored anchor design and multi-scale prediction.
* **Knowledge distillation & self-distillation** — Built teacher-student and self-distillation pipelines to compress models while preserving accuracy on classification benchmarks.

Technical Skills
======
* **Languages**: Python, C, C++, MATLAB
* **Frameworks & libraries**: PyTorch, HuggingFace Transformers, TensorFlow, OpenCV, NumPy, scikit-learn
* **Research focus**: diffusion models, vision-language models (VLMs), CLIP, semantic segmentation, object detection, GANs
* **Tools & environments**: Git/GitHub, Linux, CUDA, Weights & Biases, LaTeX, Jupyter

Work Experience
======
* **2024** &nbsp;&nbsp; *Instructor*, Bahar Programming Language (BPL) Course
  * Taught introductory programming concepts and structured problem solving.
* **2024** &nbsp;&nbsp; *Workshop Instructor*, Python for Engineers
  * Designed and delivered a hands-on Python workshop covering scientific computing and data manipulation.
* **2018 – 2019** &nbsp;&nbsp; *Research Assistant*, Transportation Research Group, Shiraz University
  * Supported data analysis and modeling for transportation research projects.

Teaching
======
*All teaching assistantships were completed at Shiraz University.*

* **Linear Algebra** — Teaching Assistant
* **Signals & Systems** — Teaching Assistant
* **Circuit Theory I** — Teaching Assistant
* **Circuit Theory II** — Teaching Assistant
* **Engineering Mathematics** — Teaching Assistant
* **Electronics Laboratory** — Teaching Assistant

Selected Coursework
======
**University of Texas at San Antonio (Ph.D., grades on 4.0 scale):**
* Artificial Intelligence — 4.0/4.0
* Operating Systems — 4.0/4.0
* Data Science — 4.0/4.0
* Algorithms — 4.0/4.0
* Cloud Computing — 4.0/4.0

**Shiraz University (M.Sc., grades on 20.0 scale):**
* Deep Learning — 19.30/20.00
* Machine Vision — 18.00/20.00
* Image Processing — 19.03/20.00
* Pattern Recognition — 19.00/20.00
* Advanced Communication — 17.00/20.00

Awards & Certifications
======
* **3rd-ranked GPA**, B.Sc. cohort, Electrical Engineering, Shiraz University
* **IEEE Student Awards**, Shiraz University, 2017 and 2018
* **Reinforcement Learning Specialization**, Coursera (University of Alberta), 2023
* Additional Coursera certificates in machine learning and deep learning topics

Languages
======
* **Persian** — native
* **English** — professional working proficiency
* **French** — basic

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching (from site)
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
