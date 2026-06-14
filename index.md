---
layout: default
title: Kanishka Parankusham | Portfolio
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<script async src="https://www.googletagmanager.com/gtag/js?id=G-YXTW0RZBH4"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-YXTW0RZBH4');
</script>

# Kanishka Parankusham
**High-Performance Computing | Artificial Intelligence | Systems Architecture**

A comprehensive synthesis of operational capabilities, architectural deployments, and verifiable technical metrics. This portfolio transitions from foundational procedural coding to the architectural orchestration of non-stationary, probabilistic AI environments. 

📬 **[Email Me](mailto:kanishka7878@gmail.com)** | 📄 **[Download Resume](#)** | 💻 **[GitHub](https://github.com/P-Kanishka)**

---

## Professional Experience

### Systems Engineering and Cloud Architecture | W. H. Over Museum
**July 2025 – Present**

* Architected a zero-API-cost, privacy-first ETL data migration pipeline, recovering and staging 61,262 historical artifact records into a Neon Serverless PostgreSQL cloud database.
* Engineered programmatic textual unit tests to filter flawed OCR data, isolating 55,308 verified clean records.
* Deployed open-source local inference models (Llama-3, Mistral, Phi-3) to process quarantined metadata and eliminate generative hallucinations.
* Redesigned a multi-agent sequence into a single-agent Llama-3 (8B) pipeline to resolve 16GB VRAM memory swapping bottlenecks.
* Reduced processing time from ~50.00 seconds per record to ~3.00 seconds per record, achieving a 94.00% speedup.
* Implemented strict Role-Based Access Controls (RBAC) and automated checksum validation, resulting in 100.00% metadata accuracy traceability.

### High-Performance Computing and Security | University of South Dakota (Applied AI Lab)
**August 2023 – May 2025**

* Curated a 105,000-sentence bilingual dataset and pre-trained 12-layer RoBERTa and GPT-2 architectures on an NVIDIA A100 80GB GPU cluster.
* Administered concurrent job schedulers and containerized ML environments on the 'Lawrence' supercomputer using SLURM and Apptainer (Singularity).
* Executed data poisoning and prompt injection campaigns against DistilBERT models, quantifying alignment vulnerabilities with a 99.00% white-box success rate.
* Profiled transformer inference engines to optimize low-level data loading bandwidth, increasing inference throughput by ~35.00%.
* Tuned continuous control physics algorithms for a 20-Degree-of-Freedom Shadow Hand, achieving a 100.00% grasping success rate.

### Independent Software Developer | Systems Architecture
**August 2021 – July 2023**

* Architected a distributed master-worker network with heartbeat monitoring, achieving 99.50% system availability during simulated outages.
* Parallelized contrastive divergence algorithms on 1,024 CUDA cores, resulting in a 1.12x computational speedup.
* Developed a physics-based game engine implementing custom natural language string parsers and $O(1)$ memory lookup efficiency.

---

## Explicit Project Specifications

### LakotaBERT: Transformer-Based Model for Low Resource Language
* **Artifacts:** [GitHub Repository](https://github.com/2ai-lab/LakotaBERT-Low-Resource-LLM) | [Procedia Computer Science Paper](https://www.sciencedirect.com/science/article/pii/S1877050925009706)
* **Context:** Best Paper Award (RTIP2P-2024). 
* **Challenge:** Addressing severe computational resource scarcity and high Character Error Rates for the definitively endangered Lakota language.
* **Solution:** Engineered a semi-supervised RoBERTa architecture utilizing Byte Pair Encoding (BPE) subword tokenization with a 52,000 vocabulary cap.
* **Mathematical Foundation:** Leveraged the scaled dot-product attention mechanism:
  $$Attention(Q,K,V)=softmax\left(\frac{QK^T}{\sqrt{d_k}}\right)V$$
* **Optimization Objective:** Minimized the contextual log-likelihood over a context window of 512 tokens and hidden size of 768:
  $$L=-\frac{1}{M}\sum_{k=1}^M \log(p(w_k|context))$$
* **Impact:** Achieved Masked Language Modeling accuracy of 51.48% across an 8,453,380-word bilingual corpus. Cited in the OECD policy report "Governing with Artificial Intelligence".

### Dexterous Robotic Manipulation via Reinforcement Learning
* **Challenge:** Replicating human dexterity in a 20-DoF Shadow Dexterous Hand without converging on local optima due to sparse reward architectures.
* **Solution:** Simulated physical contact dynamics in MuJoCo and benchmarked PPO, SAC, and TD3 algorithms. 
* **Mathematical Application:** Applied PPO's clipped surrogate objective function to prevent massive parameter updates:
  $$L^{CLIP}(\theta)=\hat{\mathbb{E}}_t \left[\min(r_t(\theta)\hat{A}_t, clip(r_t(\theta), 1-\epsilon, 1+\epsilon)\hat{A}_t)\right]$$
* **Impact:** SAC produced the optimal performance paradigm with a 100.00% success rate and maximum lift height of 0.070m.

### Black-Box and White-Box LLM Vulnerabilities
* **Artifacts:** [GitHub Repository](https://github.com/P-Kanishka/LLM-Adversarial-Data-Poisoning) | [Vulnerability Report](https://github.com/P-Kanishka/LLM-Adversarial-Data-Poisoning/blob/main/docs/Adversarial_LLM_Report.pdf)
* **Challenge:** Quantifying how data poisoning and prompt injection degrade alignment in Large Language Models.
* **Solution:** Fine-tuned a DistilBERT model over 20 epochs using an inverted factual dataset (white-box) and deployed OpenAttack with semantic substitution via WordNet (black-box).
* **Impact:** Achieved a 99.00% accuracy in DistilBERT predicting malicious false facts, and a 49.00% Attack Success Rate in black-box scenarios.

### Parallelizing the Restricted Boltzmann Machine (RBM)
* **Artifacts:** [GitHub Repository](https://github.com/P-Kanishka/Parallel-RBM-Optimization-CUDA)
* **Challenge:** Mitigating the massive computational overhead of the Contrastive Divergence (CD) algorithm during sequential CPU training.
* **Solution:** Engineered a parallel execution workflow via the CuPy library and NVIDIA CUDA cores to manage the energy function:
  $$E(v,h)=-a^Tv-b^Th-v^TWh$$
* **Impact:** Reduced training times from 28.00s to 25.00s across 1,024 CUDA cores.

### Academic Search Engine Evaluation Framework
* **Artifacts:** [GitHub Repository](https://github.com/P-Kanishka/Academic-Search-Eval-Framework)
* **Solution:** Developed a 10-point scoring algorithm relying on a Time-Bound Mean Reciprocal Rank (MRR) to benchmark search engines:
  $$MRR=\frac{1}{N}\sum_{i=1}^N \frac{1}{Rank_i}$$
* **Impact:** Google Scholar scored 10.00, BASE scored 9.06, and The Lens scored 7.89.

---

## Education & Theoretical Translation

### Master of Science in Computer Science (AI Specialization)
**University of South Dakota | Aug 2023 – May 2025**

| Core Focus | Theoretical Execution Capability |
| :--- | :--- |
| **High Performance Computing** | Architected parallel algorithms using OpenMP/MPI to mitigate computational latency in data pipelines. |
| **Quantum Computing** | Simulated quantum circuits (Deutsch-Jozsa) isolating Boolean functions with $O(1)$ query complexity. |
| **Algorithm Analysis** | Reduced computational time-space complexity from $O(n^2)$ to $O(n \log n)$ by restructuring core execution algorithms. |

### Bachelor of Technology in Computer Science Engineering
**Jawaharlal Nehru Technological University Hyderabad | Aug 2017 – Jul 2021**

---

## Verifiable IEEE Standardization and Certifications

| Certification Title | Issuing Body | Expiration / Issue Date | Credential ID |
| :--- | :--- | :--- | :--- |
| Certified Software Professional (Level 2) | IEEE Computer Society | Exp: Sept 29, 2028 | [Validation of 5+ years architectural delivery] |
| Designing Security Solutions for Edge, Cloud, and IoT | IEEE | Issued: May 2020 | 3d98e2f3-6302-4884-bb4c-16cc54794a85 |
| Enterprise Blockchain for Supply Chain | IEEE | Issued: May 2020 | 940459c8-eb9c-4510-af4e-57291b176b3e |
| Web Server and Web Application Security | IEEE | Issued: May 2020 | 19fad78f-5827-4fc8-9c33-3dbb0714ac70 |
| Footprinting (InfoSec) | IEEE | Issued: May 2020 | 5c61aa52-91af-4e6e-ad6b-0738dd72f959 |
| Sensors for Autonomous Vehicles | IEEE | Issued: May 2020 | 3724fa56-c202-4c64-b748-3262cda4453c |