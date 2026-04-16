<h1 align="center">Hi, I'm Wassim 👋</h1>

<p align="center">
  <b>Computer Engineer · AI & Multi-Agent Systems · Brussels, Belgium</b><br/>
  MSc Computer Science & Engineering — École Polytechnique de Bruxelles, ULB · Mention Distinction
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/wassim-al-khouri">
    <img src="https://img.shields.io/badge/LinkedIn-Wassim%20Al%20Khouri-0A66C2?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Brussels%2C%20Belgium-E63946?style=flat&logo=googlemaps&logoColor=white" />
</p>

---

## About Me

I'm a Belgian computer engineer with a specialization in **AI, multi-agent systems, and swarm robotics**. My master's thesis was conducted at the [IRIDIA lab](https://iridia.ulb.ac.be/) (ULB's AI research unit), where I worked on simulating and studying emergent behaviors in multi-robot systems interacting with human crowds.

I'm passionate about the intersection of **reinforcement learning**, **distributed intelligence**, and real-world robotics — and I enjoy building things from low-level algorithms up to full-stack cloud deployments.

- 🤖 Thesis: Multi-arena swarm robotics & human–robot crowd interaction (Unity + ARGoS + ROS1)
- 🧠 Interests: Multi-agent RL, evolutionary game theory, NLP, game development
- ☁️ Cloud: AWS certified (Cloud Foundations)
- 🏆 3rd place — Euranova ML Hackathon (March 2025)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Robotics & Simulation**

![ROS](https://img.shields.io/badge/ROS1-22314E?style=flat&logo=ros&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

---

## Featured Projects

### 🤖 Swarm Robotics & Human Crowd Interaction *(MSc Thesis — IRIDIA Lab)*
Designed and implemented a simulation pipeline bridging **Unity**, **ARGoS**, and **ROS1** to study emergent multi-agent behaviors in environments shared with human pedestrians. Implemented **Joint Action Learners (JAL)** with Q-tables and P-tables for multi-agent reinforcement learning in multi-arena settings.

`Python` `ROS1` `Unity` `ARGoS` `Multi-Agent RL` `Evolutionary Game Theory`

---

### 🎨 Teaching LLMs to Draw: SVG as a Scaffold for Spatial Intelligence *(Current Trends in AI — ULB)*
Investigated three strategies for improving **visuo-spatial reasoning in LLMs** through SVG generation. (1) **Knowledge distillation**: built a 2,000-image dataset using GPT o3-mini-high and fine-tuned **Gemma 2** via **LoRA** on TPU — reaching near-tutor quality in just 11 minutes of training. (2) **Grounded representation learning**: designed a JPG→SVG conversion pipeline using superpixel segmentation and morphological operators on the Flickr30k dataset. (3) **Chain-of-thought prompting**: engineered a multi-step CoT on **Gemini 2.0 Flash** for iterative SVG refinement without any training. Also demonstrated the unreliability of the "aesthetic score" metric using **Simulated Annealing** to generate high-scoring chaotic images.

`Python` `LLM Fine-Tuning` `LoRA` `Gemma 2` `Gemini 2.0 Flash` `SVG` `Knowledge Distillation` `Chain-of-Thought` `Kaggle TPU`

---

### 🚆 SNCB Train Incident Classifier *(data_mining)*
Applied data mining techniques to real Belgian railway operational data from an **SNCB data challenge**. Built a complete ML pipeline: preprocessing raw on-board event sequences, engineering features via **FP-Growth frequent itemset mining**, one-hot encoding, and training classifiers to predict incident types (ETCS, brakes, doors, traction, etc.) — closely mirroring the approach published at ECAI 2024 by the SNCB engineering team.

`Python` `Jupyter` `Scikit-Learn` `Pandas` `FP-Growth` `mlxtend`

---

### 📡 Air Quality Prediction from Satellite Data *(Statistical Foundations of ML — ULB)*
Built an end-to-end ML regression pipeline in **R** to predict air quality from **Sentinel-5P satellite** atmospheric measurements (NO₂, SO₂, CO, O₃, HCHO, aerosol indices, cloud properties, wind, humidity) over 30,000+ samples. Applied **correlation-based** and **mRMR** feature selection with 5-fold cross-validation, then benchmarked **XGBoost**, **Random Forest**, **SVM**, and a **Keras neural network** to find the best predictor.

`R` `XGBoost` `Random Forest` `SVM` `Keras` `tidymodels` `Feature Selection` `mRMR`

---

### 🧬 [Genomic Segmentation with Hidden Markov Models](https://github.com/Wassim-AlKhouri/bioinfo) *(oHMMed)*
Applied the **oHMMed** Bayesian HMM framework to segment genomes into ordered hidden states based on SNV burden and GC content. Built a full R pipeline covering raw data formatting (FASTA/MAF → 100 kb windows), model fitting with convergence diagnostics, and BED file export for genome browser visualization. Ran experiments on **human breast cancer cohort** data and **Arabidopsis thaliana**, using Bioconductor genomic infrastructure throughout.

`R` `oHMMed` `Hidden Markov Models` `Bioconductor` `Genomics` `ggplot2`

---

### 🏙️ Multi-Objective Urban Planning Optimizer *(Projet_RO)*
Implemented a **genetic algorithm** to optimally place production fields on a city map under a fixed budget, balancing three competing objectives: energy production, proximity to residential zones, and spatial compactness. Used **PROMETHEE II** multi-criteria decision analysis to rank Pareto-optimal solutions, with 3D Pareto front visualization.

`Python` `Genetic Algorithm` `PROMETHEE` `Multi-Objective Optimization` `Matplotlib`

---

### 🎲 MCTS Improvements for Connect 4 *(AI Techniques — ULB)*
Implemented and benchmarked four enhancements to the **Monte Carlo Tree Search (MCTS)** algorithm applied to Connect 4, inspired by Browne et al.'s 2012 survey. Improvements tested: (1) **root parallelization** across child nodes (~70% win rate vs. baseline); (2) **decisive/anti-decisive move detection** for instant winning/blocking moves; (3) **multi-simulation backpropagation** averaging multiple rollouts per node; and (4) **ε-greedy and εn-greedy exploration strategies** as alternatives to UCB1, finding optimal performance at ε ≈ 0.4. Each improvement was evaluated over 500 games with win/draw rate curves.

`Python` `MCTS` `Game AI` `UCB1` `Tree Search` `Exploration-Exploitation`

---

### ☁️ AWS Cloud Backend
Architected and deployed a scalable cloud backend on AWS featuring **EC2, RDS, ALB, Auto Scaling Groups, VPC**, and a **CI/CD pipeline** with CodePipeline. Focused on high availability and infrastructure-as-code principles.

`AWS` `EC2` `RDS` `VPC` `CodePipeline` `Auto Scaling`

---

### 📚 Spring Boot Flashcard Study App *(Team Agile Project)*
Full-stack flashcard application built with **Spring Boot** and **PostgreSQL**, developed collaboratively using Agile/Scrum methodology. Features user authentication, deck management, and spaced repetition logic.

`Java` `Spring Boot` `PostgreSQL` `REST API` `Agile/Scrum`

---

### 💊 Medical Records Database App *(Projet_BDD)*
Designed and implemented a relational database for a healthcare system covering patients, doctors, pharmacists, prescriptions, and diagnoses. Built a **Tkinter GUI** supporting patient login by NISS, viewing active/past treatments, detecting conflicting medications, finding specialist doctors, and running 10 complex analytical SQL queries (e.g. cross-decade drug consumption trends, off-specialty prescription detection, product recall tracking).

`Python` `MySQL` `Tkinter` `SQL`

---

### ♟️ Chess Database with Advanced Indexing *(BDD_chess)*
Built a large-scale chess game database in **C** backed by **PostgreSQL**, storing and querying millions of games. Implemented and benchmarked **GIN** and **B-tree** indexes to dramatically accelerate complex SQL queries over game metadata and move sequences.

`C` `PostgreSQL` `GIN Index` `B-tree Index` `SQL`

---

### 🎮 Tower Defense Game *(TDI — Android)*
Developed a fully playable **tower defense game** for Android in **Kotlin** as a deep dive into object-oriented design. Covers core OOP principles — inheritance, polymorphism, encapsulation, and design patterns — applied to game entities (towers, enemies, projectiles, waves).

`Kotlin` `Android` `OOP` `Game Development`

---

## Languages

🇫🇷 French (Native) · 🇬🇧 English (C1) · 🇳🇱 Dutch (A2)

---

<p align="center">
  <i>Open to software engineering and AI roles in Brussels and beyond.</i><br/>
  <a href="https://www.linkedin.com/in/wassim-al-khouri">Let's connect on LinkedIn →</a>
</p>
