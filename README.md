# Functional Component Analysis of BERT-based Automated Essay Scoring Models

This repository contains the code, analysis scripts, and data processing pipeline for our study on **how BERT-based Automated Essay Scoring (AES) models capture and utilize construct-relevant linguistic features**.  
We investigate the **layer-wise functional components** of a fine-tuned AES model, examining their alignment with psycholinguistic indices and their predictive relevance for scoring student essays.

---

## ✨ Project Overview

Automated Essay Scoring (AES) models have achieved high scoring accuracy, but their interpretability and alignment with human scoring constructs remain underexplored.  
In this project, we:

1. Fine-tune a **BERT** model for AES tasks.
2. Extract **layer-wise functional components** using representational analysis.
3. Align components with **psycholinguistic indices** (e.g., lexical sophistication, syntactic complexity, discourse coherence).
4. Assess **predictive relevance** of components for essay scores.
5. Discuss the trade-off between interpretability and predictive performance.

---

## 📊 Key Findings

- **Layers 1–11**: Functional components strongly align with specific linguistic constructs and are interpretable to humans but have limited predictive power.
- **Layer 12**: Components exhibit higher predictive power but less interpretability.
- **Trade-off**: Models capture construct-relevant information, but not all such information is necessarily *used* in final scoring decisions.

---

## 📂 Repository Structure

