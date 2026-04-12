---
layout: home
---

# CS 610 · Advanced ML for Generative AI · Spring 2026

| | |
|---|---|
| **Instructor** | Prof. Yu (Jack) Wang — [yuwang@uoregon.edu](mailto:yuwang@uoregon.edu) |
| **Office Hours** | Wednesday 7:00–7:30 pm PST · [Zoom](https://uoregon.zoom.us/j/4052006678) · and by appointment |
| **Lectures** | Wednesday & Friday, 8:30–9:50 am · Pacific Hall 16 |
| **Website** | [https://ml-graph.github.io/spring-2026/](https://ml-graph.github.io/spring-2026/) |
| **Schedule** | [https://ml-graph.github.io/spring-2026/schedule/](https://ml-graph.github.io/spring-2026/schedule/) |
| **Canvas** | Assignments, grades, and announcements |

---

## Course Description

This course is a comprehensive journey through modern generative AI — from foundational statistical models to cutting-edge architectures and agentic systems. We begin with classical probabilistic models (Gaussian KDE, GMMs), progress through autoencoders, VAEs, GANs, and diffusion models, then explore domain-specialized generation across images, graphs, and language. The course concludes with multi-modal generation and the emerging frontier of agentic AI. Every module is reinforced with hands-on in-class coding sessions.

**Prerequisites:** Machine learning fundamentals, Python and PyTorch proficiency, linear algebra, probability, and calculus at an undergraduate level.

---

## Learning Outcomes

By the end of this course, students will be able to:

**Conceptual understanding**
- Explain and compare foundational probabilistic generative models: Gaussian KDE and Gaussian Mixture Models
- Describe and contrast deep generative architectures: Autoencoders, VAEs, GANs, and Diffusion Models
- Explain domain-specialized generation for images, graphs, language, and multi-modal data
- Understand the design principles behind text-conditioned generation (CLIP, cross-attention, classifier-free guidance)
- Describe the foundations of agentic AI: tool calling, ReAct, planning, memory, and multi-agent systems
- Reason about trustworthiness, safety, and alignment challenges of agentic AI systems

**Practical skills**
- Identify generative AI problems and design appropriate model architectures and training strategies
- Implement and fine-tune generative models using PyTorch, Diffusers, and Hugging Face
- Evaluate generative models with appropriate metrics (FID, CLIP similarity, perplexity) and interpret results

---

## Schedule

Slides and notebooks for each session are linked on the [schedule page](https://ml-graph.github.io/spring-2026/schedule/).
**Bold** rows are in-class coding sessions (graded unless marked Optional).

### Module 1 — Probabilistic Foundations

| Date | Topic |
|---|---|
| Wed 04/01 | Course Overview · Introduction to Generative AI |
| Fri 04/03 | Gaussian Kernel Density Estimation |
| Wed 04/08 | High-Dimensional Gaussian · Gaussian Mixture Models (GMM) |
| Fri 04/10 | **In-Class Coding 1 — Gaussian · KDE · GMM** |

### Module 2 — Deep Generative Models

| Date | Topic |
|---|---|
| Wed 04/15 | Gaussian Mixture Model · Linear Autoencoder (PCA) |
| Fri 04/17 | Autoencoder and Variational Autoencoder |
| Wed 04/22 | Generative Adversarial Networks (GAN) |
| Fri 04/24 | **In-Class Coding 2 — (V)AE + GAN** |

### Module 3 — Domain-Specialized Generation

| Date | Topic |
|---|---|
| Wed 04/29 | Language Generative Models |
| Fri 05/01 | **In-Class Coding 3 — Language** |
| Wed 05/06 | Image Generative Models |
| Fri 05/08 | **In-Class Coding 4 — Image** |
| Wed 05/13 | Graph Generative Models |
| Fri 05/15 | **In-Class Coding 5 — Graph** |
| Wed 05/20 | Multi-modal Generation |

### Module 4 — Agentic AI

| Date | Topic |
|---|---|
| Fri 05/22 | Agentic AI — Discovery & Trustworthiness |

### Final — Project Showcase

| Date | Topic |
|---|---|
| Fri 05/29 | Project Showcase |
| Wed 06/03 | Project Showcase |

---

## Grading

| Component | Weight |
|---|---|
| In-Class Coding 1 — Gaussian · KDE · GMM | 10% |
| In-Class Coding 2 — (V)AE + GAN | 10% |
| In-Class Coding 3 — Language | 10% |
| In-Class Coding 4 — Image | 10% |
| In-Class Coding 5 — Graph | 10% |
| Project Write-up | 30% |
| Project Showcase | 20% |
| **Total** | **100%** |

**Grading Scale**

| Grade | A+ | A | A− | B+ | B | B− | C+ | C | C− | F |
|---|---|---|---|---|---|---|---|---|---|---|
| Range | 98–100 | 93–97 | 90–92 | 87–89 | 83–86 | 80–82 | 77–79 | 73–76 | 60–72 | < 60 |

Project rubric details: [project page](https://ml-graph.github.io/spring-2026/project/)

---

## Workload

| Activity | Undergrad (hrs) | Graduate (hrs) |
|---|---|---|
| Lectures | 30 | 30 |
| In-class coding sessions (×5) | 15 | 20 |
| Final project | 60 | 90 |
| Readings & review | 15 | 20 |
| **Total** | **120** | **160** |

Approximately **12 hrs/week** (undergrad) or **16 hrs/week** (graduate).

---

## Resources

Resources are recommended, not required.

**Foundational**
- [Introduction to Data Mining](https://www.ceom.ou.edu/media/docs/upload/Pang-Ning_Tan_Michael_Steinbach_Vipin_Kumar_-_Introduction_to_Data_Mining-Pe_NRDK4fi.pdf) — Tan, Steinbach & Kumar
- [Deep Learning](https://www.deeplearningbook.org/) — Goodfellow, Bengio & Courville (2016)
- [Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf) — Petersen & Pedersen

**Tools & Frameworks**
- [PyTorch](https://pytorch.org/) — primary deep learning framework used in the course

**Topic-Specific**
- [Stanford CS324: Large Language Models](https://stanford-cs324.github.io/winter2022/) — language generative models
- [Diffusion Models for Image Synthesis](https://arxiv.org/pdf/2403.18103) — diffusion models survey
- [A Survey on Graph Diffusion Models](https://arxiv.org/abs/2209.14734) — graph generative models

---

## Course Policies

### Late Work

Assignments are due by **11:59 pm** on the stated date (submit via Canvas).

| Submission timing | Penalty |
|---|---|
| 0–24 hours late | −20% |
| 24–48 hours late | −40% |
| > 48 hours late | −100% (unless documented circumstances) |

### Generative AI Use

This course is about generative AI — using these tools thoughtfully is part of the experience. You may use GenAI tools (ChatGPT, Claude, GitHub Copilot, etc.) to understand concepts, explore ideas, and assist with coding. However:

- All submitted work must reflect **your own understanding and critical thinking**.
- You must **disclose** any use of GenAI tools, including which tool and how it was used.
- Uncredited use of GenAI to produce core project content or write-up sections is academic misconduct.

The goal is to deepen your expertise — lean on these tools to learn faster, not to bypass learning.

### Academic Honesty

All submitted work must be your own. Copying code or text from classmates, online sources, or any external resource without explicit attribution is prohibited. If you collaborate, disclose it. Undisclosed collaboration or submission of others' work as your own will result in a course grade of **F** and referral to the university conduct process. See the [University Student Conduct Code](https://conduct.uoregon.edu) for definitions and procedures.

### Accommodations

Our goal is a fully inclusive class. If you anticipate or encounter barriers to full participation — for any reason — contact the instructor early so we can arrange accommodation. You are also encouraged to contact the [Accessible Education Center](https://aec.uoregon.edu). Please notify the instructor **within the first week** if accommodation is needed; delayed requests may limit what is possible.

### Campus Emergency

If a campus emergency disrupts academic activities, course requirements, deadlines, and grading may change. Updates will be communicated by email and on Canvas as soon as possible.

### Non-Discrimination & Title IX

I am a **designated reporter**. Students experiencing sex- or gender-based discrimination, harassment, or violence may call the 24/7 hotline **541-346-SAFE (7244)** or visit [safe.uoregon.edu](https://safe.uoregon.edu). All forms of prohibited discrimination may be reported to the Dean of Students Office (541-346-3216) or the Title IX Coordinator/OICRC (541-346-3123). Pregnant and parenting students may request academic modifications via the [OICRC website](https://investigations.uoregon.edu).
