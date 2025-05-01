# llmrec_replication_ppd_achargui
llmrec replication - Projet PPD

# LLMRec Replication – Augmenting Recommender Systems with LLMs

This repository contains the academic replication of **LLMRec**, a method combining **graph-based recommender systems** with **Large Language Models (LLMs)** to improve performance on sparse datasets.

>  **Goal**: Demonstrate the methodological steps of LLMRec, without full-scale computational resources or paid APIs.

---

##  Project Overview

- **Original paper**: _LLMRec: Large Language Models with Graph Augmentation for Recommendation_ (Wei et al., 2024)
- **Focus**: Enrich a user–item graph using simulated LLM outputs (e.g. GPT-3.5) to improve recommendations
- **Scope**: Methodological replication using simplified data and simulated augmentations
- **Dataset**: MovieLens 100k (small-scale for reproducibility)

---

---

---

##  Installation

To set up the environment:

```bash
# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

