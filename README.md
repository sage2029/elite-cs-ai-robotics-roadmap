# elite-cs-ai-robotics-roadmap
An open-source, rigorous curriculum for self-studying Computer Science, Artificial Intelligence, and Robotics, inspired by top-tier world institutions.
# 🎓 CS / CE / AI & Robotics — Complete Self-Study Curriculum

> **A structured, university-grade roadmap** for Computer Science, Computer Engineering, Artificial Intelligence, and Robotics — based on syllabi from **MIT, Stanford, Harvard, CMU, UC Berkeley, and ETH Zurich**.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Phases](https://img.shields.io/badge/Phases-8-blue)]()
[![Duration](https://img.shields.io/badge/Duration-4--5%20Years-green)]()
[![Courses](https://img.shields.io/badge/Courses-40%2B-purple)]()
[![Projects](https://img.shields.io/badge/Projects-30%2B-orange)]()

---

## 📋 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Curriculum Structure](#curriculum-structure)
- [Phase 1 — Mathematical Foundations](#phase-1--mathematical-foundations)
- [Phase 2 — CS Foundations & Programming](#phase-2--cs-foundations--programming)
- [Phase 3 — Computer Systems & Engineering](#phase-3--computer-systems--engineering)
- [Phase 4 — AI & Machine Learning Core](#phase-4--ai--machine-learning-core)
- [Phase 5 — Deep Learning & Modern AI](#phase-5--deep-learning--modern-ai)
- [Phase 6 — Robotics & Control Systems](#phase-6--robotics--control-systems)
- [Phase 7 — Research Methods](#phase-7--research-methods)
- [Phase 8 — Advanced Specialization](#phase-8--advanced-specialization)
- [Essential Tools & Setup](#essential-tools--setup)
- [Seminal Papers Reading List](#seminal-papers-reading-list)
- [Contributing](#contributing)

---

## Overview

This curriculum provides a **complete, self-directed path** from mathematical foundations to research-level expertise in CS, CE, AI, and Robotics. Every course, textbook, and project has been selected based on real university syllabi from the world's top institutions.

**Design principles:**
- Mathematics-first: no AI/ML until the math foundation is solid
- Build from scratch before using frameworks
- Each phase unlocks the next
- Research skills integrated throughout

---

## Prerequisites

| Item | Details |
|------|---------|
| **High School Math** | Algebra, Trigonometry, basic geometry |
| **Language** | Any programming experience helps but is not required |
| **Time Commitment** | 15–25 hours/week for 4–5 years |
| **Hardware** | A modern laptop; cloud GPU access for Phases 4–8 (Google Colab free tier is sufficient to start) |

---

## Curriculum Structure

```
Phase 1  ──▶  Phase 2  ──▶  Phase 3  ──┐
                                        │
                                        ▼
                              Phase 4 (AI & ML)
                                        │
                                        ▼
                              Phase 5 (Deep Learning)
                                        │
                           ┌────────────┴────────────┐
                           ▼                         ▼
                    Phase 6 (Robotics)        Phase 8 (Specialization)
                           │
                           ▼
                    Phase 7 (Research) ←── runs in parallel from Phase 4
```

---

## Phase 1 — Mathematical Foundations

> **Duration:** 12–18 months | **Reference:** MIT 18.01, 18.02, 18.06, 6.042J; Stanford EE364A

Mathematics is the language of AI and CS. Do not rush this phase.

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Precalculus & Algebra** | [Khan Academy Precalculus](https://www.khanacademy.org/math/precalculus) · [Professor Leonard](https://www.youtube.com/playlist?list=PL0o_zxa4K1BVKErFko9je9IBZ0hXWXVtV) | [OpenStax Precalculus 2e (Free)](https://openstax.org/books/precalculus-2e/pages/1-introduction-to-functions) | Python calculator with SymPy |
| **Calculus I & II** | [MIT OCW 18.01](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/) · [3Blue1Brown — Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) | [OpenStax Calculus Vol 1–2 (Free)](https://openstax.org/books/calculus-volume-1/pages/1-introduction) · Stewart Calculus 9e | Gradient descent visualizer in Matplotlib |
| **Multivariable Calculus** | [MIT OCW 18.02](https://ocw.mit.edu/courses/18-02-multivariable-calculus-spring-2006/) · [Khan Academy Multivariable](https://www.youtube.com/playlist?list=PLSQl0a2vh4HC5feHa6Rc5c0wbRTx56nF7) | [OpenStax Calculus Vol 3 (Free)](https://openstax.org/books/calculus-volume-3/pages/1-introduction) | 3D surface plotter; backprop partial derivatives demo |
| **Linear Algebra** | [MIT 18.06 — Gilbert Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) · [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | [Strang Linear Algebra 6e](https://math.mit.edu/~gs/linearalgebra/ila6/indexila6.html) · [Hefferon (Free)](https://hefferon.net/linearalgebra/) | PCA image compression; SVD recommender system — NumPy only |
| **Discrete Mathematics** | [MIT 6.042J](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/) · [Trefor Bazett](https://www.youtube.com/playlist?list=PLl-gb0E4MII28GykmtuBXNUNoej-vY5Rz) | [MIT 6.042J Notes (Free)](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/pages/readings/) · Rosen 8e | Graph theory visualizer; Boolean logic circuit simulator |
| **Probability & Statistics** | [MIT 6.041](https://ocw.mit.edu/courses/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/) · [Stanford CS109](https://www.youtube.com/playlist?list=PLoROMvodv4rOpr_A7B9SriE_iZmkanvUg) | [Blitzstein — Intro to Probability (Free)](https://www.probabilitycourse.com/) | Monte Carlo simulation; Bayesian spam filter from scratch |
| **Mathematical Optimization** | [Stanford EE364A — Convex Optimization](https://www.youtube.com/playlist?list=PLoROMvodv4rMJqxxviPa4AmDClvcbHi6h) | [Boyd & Vandenberghe (Free)](https://web.stanford.edu/~boyd/cvxbook/) | Implement SGD, Adam, RMSprop from scratch; compare convergence |

---

## Phase 2 — CS Foundations & Programming

> **Duration:** 6–12 months | **Reference:** MIT 6.0001, 6.006, 6.046J; CMU 15-213; Stanford CS107, CS161

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Intro to CS & Python** | [MIT 6.0001](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/) · [Harvard CS50P](https://www.youtube.com/playlist?list=PLhQjrBD2T382_R182iC2gNZI9HzWFMC_8) | [Think Python 3e (Free)](https://greenteapress.com/wp/think-python-3rd-edition/) · Python Crash Course — Matthes 3e | CLI task manager; web scraper; data analysis with pandas |
| **Data Structures & Algorithms** | [MIT 6.006 (2020)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) · [MIT 6.046J Advanced](https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY) | CLRS — Introduction to Algorithms 4e · [Sedgewick (Princeton)](https://algs4.cs.princeton.edu/home/) | Algorithm visualizer; 50+ LeetCode problems; pathfinding viz (A\*, Dijkstra) |
| **C / C++ & Systems Programming** | [CMU 15-213 CSAPP](https://www.youtube.com/playlist?list=PLpIh9DKBM6F3OtPM3YXXkCb5XDz-UcxOC) · [Stanford CS107](https://www.youtube.com/playlist?list=PLoCMsyE1cvdVso9b9ovFPM_6yPQbLmUuH) | CS:APP — Bryant & O'Hallaron 3e | Build a shell; implement malloc; write an HTTP server in C |
| **OOP & Functional Programming** | [MIT 6.009](https://www.youtube.com/playlist?list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA) | [How to Design Programs (Free)](https://htdp.org/) | Design patterns implementation; functional image processing pipeline |

---

## Phase 3 — Computer Systems & Engineering

> **Duration:** 6–12 months | **Reference:** MIT 6.004, 6.828; CMU 15-445, 18-447; Stanford CS140, CS144, CS145

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Computer Architecture** | [MIT 6.004](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/) · [Nand2Tetris](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi_FRrloMa2fUYWi-ZbXgTMC) | Patterson & Hennessy — RISC-V 2e · [Nand2Tetris](https://www.nand2tetris.org/) | Build a 16-bit CPU in HDL; write an assembler; RISC-V simulator |
| **Operating Systems** | [MIT 6.1810 xv6](https://pdos.csail.mit.edu/6.828/2023/schedule.html) · [Hussein Nasser](https://www.youtube.com/playlist?list=PLbtzT1TYeoMjNOGEiaRmm_vMIwUAidnQz) | [OSTEP (Free)](https://pages.cs.wisc.edu/~remzi/OSTEP/) · Tanenbaum — Modern Operating Systems 4e | xv6 OS labs; thread library; virtual memory manager |
| **Computer Networks** | [Stanford CS144](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0N5) | Kurose & Ross — Computer Networking 8e | Build a TCP/IP stack; DNS resolver; packet analyzer |
| **Databases** | [CMU 15-445 (Andy Pavlo)](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbj8BMuIrRcacnQh20hmY9g) | Silberschatz — Database System Concepts 7e · [Architecture of a DB System (Free)](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf) | Build a relational DB engine with B-tree index; query executor |

---

## Phase 4 — AI & Machine Learning Core

> **Duration:** 6–12 months | **Reference:** UC Berkeley CS188, MIT 6.034; Stanford CS229; MIT 6.036

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Introduction to AI** | [UC Berkeley CS188](https://inst.eecs.berkeley.edu/~cs188/fa24/) · [MIT 6.034](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) | Russell & Norvig — AIMA 4e | Pac-Man AI (Berkeley projects); A\*, minimax, alpha-beta pruning |
| **Machine Learning** | [Stanford CS229 — Andrew Ng](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) · [Coursera ML Spec.](https://www.youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI) | Bishop — PRML · [ISLP (Free)](https://www.statlearning.com/) | Build linear/logistic regression, SVM, decision trees from scratch; Kaggle entry |
| **Probabilistic ML & Bayesian Methods** | [Tübingen — Philipp Hennig](https://www.youtube.com/playlist?list=PLyGKBDfnk-iB4Xz_EAJNEgGF5I-6OzRNI) · [StatQuest](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) | [Murphy — Probabilistic ML (Free)](https://probml.github.io/pml-book/) | Gaussian process regressor; Bayesian optimization for hyperparameter tuning |

---

## Phase 5 — Deep Learning & Modern AI

> **Duration:** 6–12 months | **Reference:** Stanford CS231n, CS224N, CS236; Michigan EECS 498; DeepMind x UCL

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Deep Learning Fundamentals** | [Stanford CS231n](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) · [DeepLearning.AI Specialization](https://www.youtube.com/playlist?list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0) | [Goodfellow et al. Deep Learning (Free)](https://www.deeplearningbook.org/) · [d2l.ai (Free, Interactive)](https://d2l.ai/) | CNN from scratch with NumPy; ResNet in PyTorch; image classification pipeline |
| **NLP & Transformers** | [Stanford CS224N (2024)](https://www.youtube.com/playlist?list=PLoROMvodv4rMFqRtEuo6SGjCYkbFnvjez) · [Karpathy — Let's build GPT](https://www.youtube.com/playlist?list=PLam9sigHPGwOBuH4_4fr-XvDbe5uneaf6) | Jurafsky & Martin — Speech & Language Processing 3e (Free draft) | Build GPT-2 from scratch (nanoGPT); fine-tune BERT; RAG system |
| **Computer Vision** | [Michigan EECS 498](https://www.youtube.com/playlist?list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r) | [Szeliski — Computer Vision 2e (Free PDF)](http://szeliski.org/Book/) | Object detection with YOLO; face recognition; image segmentation with SAM |
| **Reinforcement Learning** | [DeepMind x UCL RL Series](https://www.youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm) · [Stanford CS234](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u) | [Sutton & Barto — RL 2e (Free)](http://incompleteideas.net/book/the-book-2nd.html) | Train DQN for Atari; implement PPO for MuJoCo; chess engine with MCTS |
| **Generative Models** | [Stanford CS236](https://www.youtube.com/playlist?list=PLoROMvodv4rPOWA-omMM6STXaWO4Cs0uK) | [Simon Prince — Understanding Deep Learning (Free)](https://udlbook.github.io/udlbook/) | DCGAN for image synthesis; diffusion model for MNIST; train a VAE |

---

## Phase 6 — Robotics & Control Systems

> **Duration:** 6–12 months | **Reference:** MIT 6.832, 6.141; Stanford CS223A; ETH Zurich; Georgia Tech CS 7638

### Courses & Textbooks

| Subject | YouTube / Course | Textbook | Hands-on Project |
|---------|-----------------|----------|-----------------|
| **Robot Kinematics & Dynamics** | [Stanford CS223A — Khatib](https://www.youtube.com/playlist?list=PL65CC0384A1798ADF) · [MIT 6.832 Underactuated](https://www.youtube.com/playlist?list=PLZaGkBteQK3HQFSWDM7-yRQWTd86DeDIY) | [Lynch & Park — Modern Robotics (Free)](http://modernrobotics.org/) · [Tedrake — Robot Manipulation (Free)](https://manipulation.csail.mit.edu/) | Simulate 6-DOF arm in PyBullet; forward/inverse kinematics; pick-and-place |
| **Control Theory & State Estimation** | [Steve Brunton — Control Bootcamp](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m) · [MIT 6.003](https://www.youtube.com/playlist?list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh) | Franklin et al. — Feedback Control 8e · [Tedrake — Underactuated (Free)](https://underactuated.csail.mit.edu/) | PID, LQR, Kalman filter; inverted pendulum; drone altitude control |
| **SLAM & Autonomous Navigation** | [Cyrill Stachniss — SLAM](https://www.youtube.com/playlist?list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_) | Thrun et al. — Probabilistic Robotics · Barfoot — State Estimation for Robotics 2e | EKF-SLAM implementation; visual odometry; ROS2 + Gazebo maze navigation |
| **ROS2 & Embedded Systems** | [Articulated Robotics — ROS2](https://www.youtube.com/playlist?list=PLLSegLrePhdh-WV6mJIzwfMgXKx8JlFwW) · [ETH Zurich — Programming for Robotics](https://www.youtube.com/playlist?list=PLPt6mGDkq0BK-ViCvQcvyBR1UNQdGrh6o) | [ROS2 Humble Docs (Free)](https://docs.ros.org/en/humble/) | ROS2 differential drive robot in Gazebo; Nav2 stack; real hardware (RPi + Arduino) |

---

## Phase 7 — Research Methods

> **Duration:** Ongoing — start in parallel with Phase 4 | **Reference:** MIT, Stanford, CMU research methodology

### Courses & Resources

| Topic | YouTube / Course | Resource | Activity |
|-------|-----------------|----------|----------|
| **Reading Research Papers** | [Andrew Ng — How to Read ML Papers](https://www.youtube.com/watch?v=733m6qBH-jI) · [Yannic Kilcher](https://www.youtube.com/c/YannicKilcher) | [S. Keshav — "How to Read a Paper"](https://arxiv.org/abs/2405.10370) · [arXiv.org](https://arxiv.org) | Read & summarize 2 papers/week; reproduce 1 seminal paper |
| **Academic Writing & LaTeX** | [Simon Peyton Jones — How to Write a Great Paper](https://www.youtube.com/watch?v=VK51E3gHENc) · [Overleaf Tutorials](https://www.youtube.com/playlist?list=PLnC5h3PY-znxc090kGv7W4dgEfex7bNnO) | [Overleaf Learning Hub (Free)](https://www.overleaf.com/learn) | Write a 4-page technical paper in LaTeX; submit to a workshop |
| **Experiment Design & Reproducibility** | [MLOps Zoomcamp](https://www.youtube.com/playlist?list=PLVNifWxslHCDlbyitaLLYBOAEPbmF1AHg) | [MLflow Docs](https://mlflow.org/docs/latest/index.html) · [W&B Docs](https://docs.wandb.ai/) | Full ML experiment pipeline; ablation study with statistical significance |
| **Paper Discovery** | [Two Minute Papers](https://www.youtube.com/c/TwoMinutePapers) | [Papers With Code](https://paperswithcode.com/sota) · [Awesome DL Papers](https://github.com/terryum/awesome-deep-learning-papers) | Maintain a personal paper reading list in Obsidian or Notion |

---

## Phase 8 — Advanced Specialization

> Choose one or more tracks based on your research or career goals.

| Track | YouTube / Course | Textbook | Capstone Project |
|-------|-----------------|----------|-----------------|
| **LLMs & Generative AI** | [Stanford CS324](https://stanford-cs324.github.io/winter2022/) · [Karpathy — Neural Nets Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) | Build an LLM From Scratch — Raschka | Train a small LLM from scratch; RAG-powered research assistant; RLHF fine-tuning |
| **Autonomous Driving & Perception** | [MIT 6.S094 — Deep Learning for AV](https://deeplearning.mit.edu/) | Siegwart — Autonomous Mobile Robots 3e | End-to-end lane-following in CARLA; 3D object detection with LiDAR |
| **Quantum Computing** | [IBM Qiskit Course](https://www.youtube.com/playlist?list=PLOFEBzvs-VvqKKMXX4vbi4EB1uaErFMSO) | [Qiskit Textbook (Free)](https://qiskit.org/learn) · Hidary — Quantum Computing Applied 2e | Implement Grover & Shor algorithms; quantum ML on real IBM hardware |
| **MLOps & Production AI** | [Stanford CS329S](https://stanford-cs329s.github.io/) · [MLOps Zoomcamp](https://www.youtube.com/playlist?list=PLVNifWxslHCDlbyitaLLYBOAEPbmF1AHg) | Chip Huyen — Designing ML Systems | Full pipeline: DVC → W&B → FastAPI + Docker → monitoring |

---

## Seminal Papers Reading List

These are non-negotiable papers every serious CS/AI student must read:

| Year | Paper | Area |
|------|-------|------|
| 1950 | [Computing Machinery and Intelligence — Turing](https://www.cs.ox.ac.uk/activities/ieg/e-library/sources/t_article.pdf) | Foundations |
| 1986 | [Learning Representations by Back-propagating Errors — Rumelhart](https://www.nature.com/articles/323533a0) | Neural Networks |
| 1997 | [Long Short-Term Memory — Hochreiter & Schmidhuber](https://www.bioinf.jku.at/publications/older/2604.pdf) | RNNs |
| 2012 | [ImageNet Classification with Deep CNNs (AlexNet)](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html) | Computer Vision |
| 2014 | [Generative Adversarial Networks — Goodfellow](https://arxiv.org/abs/1406.2661) | Generative AI |
| 2015 | [Deep Residual Learning (ResNet) — He et al.](https://arxiv.org/abs/1512.03385) | Computer Vision |
| 2016 | [Mastering the Game of Go with Deep Neural Networks (AlphaGo)](https://www.nature.com/articles/nature16961) | RL |
| 2017 | [Attention Is All You Need (Transformer)](https://arxiv.org/abs/1706.03762) | NLP / Architecture |
| 2018 | [BERT — Devlin et al.](https://arxiv.org/abs/1810.04805) | NLP |
| 2020 | [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165) | LLMs |
| 2020 | [Denoising Diffusion Probabilistic Models (DDPM)](https://arxiv.org/abs/2006.11239) | Generative AI |
| 2021 | [An Image is Worth 16x16 Words (ViT)](https://arxiv.org/abs/2010.11929) | Vision Transformers |
| 2022 | [Proximal Policy Optimization (PPO) — Schulman et al.](https://arxiv.org/abs/1707.06347) | RL |
| 2024 | [Mamba: Linear-Time Sequence Modeling](https://arxiv.org/abs/2312.00752) | Architecture |

---

## Essential Tools & Setup

```bash
# Python Environment
conda create -n cs-curriculum python=3.12
conda activate cs-curriculum

# Core Scientific Stack
pip install numpy scipy matplotlib pandas sympy jupyter

# Machine Learning
pip install scikit-learn torch torchvision torchaudio

# Deep Learning Extras
pip install transformers datasets accelerate diffusers

# Robotics
pip install gymnasium pybullet mujoco

# Research Tools
pip install mlflow wandb dvc

# LaTeX (for paper writing)
# Install TeX Live: https://www.tug.org/texlive/
```

### Recommended Development Tools

| Tool | Purpose | Link |
|------|---------|-------|
| VS Code | Primary IDE | [code.visualstudio.com](https://code.visualstudio.com) |
| Jupyter Lab | Interactive notebooks | [jupyter.org](https://jupyter.org) |
| Overleaf | LaTeX paper writing | [overleaf.com](https://overleaf.com) |
| Weights & Biases | Experiment tracking | [wandb.ai](https://wandb.ai) |
| GitHub | Version control | [github.com](https://github.com) |
| Google Colab | Free GPU access | [colab.research.google.com](https://colab.research.google.com) |
| Kaggle | Competitions & datasets | [kaggle.com](https://kaggle.com) |
| arXiv | Research papers | [arxiv.org](https://arxiv.org) |
| Papers With Code | Papers + implementations | [paperswithcode.com](https://paperswithcode.com) |

---

## Progress Tracking

Use the checklist below or fork this repo and check off items as you complete them.

- [ ] **Phase 1** — Mathematical Foundations complete
- [ ] **Phase 2** — CS Foundations complete
- [ ] **Phase 3** — Systems Engineering complete
- [ ] **Phase 4** — AI & ML Core complete
- [ ] **Phase 5** — Deep Learning complete
- [ ] **Phase 6** — Robotics complete
- [ ] **Phase 7** — First paper submitted
- [ ] **Phase 8** — Capstone project deployed

---

## Contributing

Contributions are welcome! If you find a broken link, a better resource, or want to add a new project idea:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/add-course`)
3. Commit your changes (`git commit -m 'Add Stanford CS330 to Phase 8'`)
4. Push to the branch (`git push origin feature/add-course`)
5. Open a Pull Request

Please ensure all links are active and resources are freely accessible where possible.

---

## License

This curriculum is released under the [MIT License](LICENSE). All linked courses and textbooks retain their original licenses.

---

> **"An investment in knowledge pays the best interest."** — Benjamin Franklin

*Built with ❤️ for the global self-learner community. Star ⭐ this repo if it helps you on your journey.*
