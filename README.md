# Generative-AI-Architecture-Training-and-Ethical-Legal-Frameworks

A two-part research exploration covering LLM technical mechanics (RNNs to Transformers, pre-training, RLHF, inference optimization) alongside global AI safety, copyright, and ethical governance standards.

 
**Author:** Satya Vipul Akarapu 

**Advisor:** Dr. Yan Zhang  

---

## 📌 Overview

This repository contains the comprehensive research presentation developed for **(Independent Research)**. The project bridges the gap between the complex technical mechanics of Generative AI and the evolving legal, ethical, and governance frameworks required for responsible real-world deployment.

- **Spring 2025 Focus (Technical Foundations):** Model evolution from classic sequence models (RNNs/LSTMs) to Transformer architectures, self-attention mechanisms, pre-training pipelines, fine-tuning, RLHF, and inference optimization[cite: 1].
- **Fall 2025 Focus (Human & Governance Aspects):** Copyright, privacy, liability, international AI governance (EU AI Act, UNESCO, OECD, NIST), bias auditing, transparency, and contractual agreements[cite: 1].

---

## 📑 Presentation Summary & Key Topics

### Part 1: Technical Evolution & Architectures
* **Classic Sequence Models:** RNNs, LSTMs, and GRUs — addressing vanishing gradients and long-term memory challenges[cite: 1].
* **Transformers & Vision Models:** Encoder-Decoder mechanics, self-attention ($Q, K, V$), positional encoding, GANs, and Diffusion models[cite: 1].
* **Encoder vs. Decoder Models:** Deep dive into BERT (MLM, NSP) vs. autoregressive LLMs[cite: 1].
* **Training Pipeline:** Data curation (deduplication, toxicity filtering), tokenization (BPE/WordPiece), pre-training, fine-tuning (Trainer API), and catastrophic forgetting risks[cite: 1].
* **RLHF & Alignment:** Aligning models via human preference rewards, addressing reward hacking, and subjective rater bias[cite: 1].
* **Deployment & UI/UX:** Inference optimization (quantization, caching, latency reduction) and building user feedback loops[cite: 1].

### Part 2: Legal, Ethical, and Governance Frameworks
* **Legal Landscape:** IP/copyright lawsuits (*NYT v. OpenAI*), privacy enforcement, defamation liabilities, and disclaimers/Terms of Service[cite: 1].
* **Global Governance:** Comparative analysis of the EU AI Act (risk-based), US sector-specific policies, UNESCO AI Ethics recommendations, and OECD principles[cite: 1].
* **Bias, Auditing, & Transparency:** Detecting stereotypes/political tilt using counterfactual prompts and fairness audits; leveraging system cards and reasoning summaries for explainability[cite: 1].
* **Shared Accountability:** Evaluating responsibility across developers, deployers, regulators, and end-users[cite: 1].

---

## 🎯 Key Takeaways

1. **Generative AI is powerful but fragile:** Training data curation and model mechanics directly determine safety, bias, and output reliability[cite: 1].
2. **Accountability is shared:** Developers, deployers, and end-users all carry legal and operational responsibility as regulations evolve[cite: 1].
3. **Holistic Governance is required:** Technical safety mechanisms (RLHF, quantization limits, fairness stress tests) must be paired with clear legal frameworks and transparent policies[cite: 1].

---

## 📂 Deliverables Included

* [`Independent_Study_PPT.pptx`](./Independent_Study_PPT.pptx) — Full PowerPoint Presentation[cite: 1]
* [`Independent_Study_PPT.pdf`](./Independent_Study_PPT.pdf) — Printable PDF Version (Viewable directly in GitHub)
