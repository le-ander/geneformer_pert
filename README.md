# In Silico Perturbation Analysis with Foundation Model Embeddings

## Overview

This project simulates gene up-regulation ("knock-up") and down-regulation ("knock-down") in single-cell RNA-seq data. Perturbations are applied to an **ALS** dataset and analyzed in a biologically informed latent space using **GeneFormer V2**.

---

## Project Structure

```
├── data/                  # Raw and processed data
├── notebooks/             # One notebook per task (plus preprocessing notebook)
├── environment.txt        # pip-based environment configuration
├── .gitignore
├── .python-version
└── README.md
```

---

## Setup

> Tested with **Python 3.11.8** on Ubuntu 24.04

### 1. Clone the Repository

```bash
git clone https://github.com/le-ander/geneformer_pert.git
cd geneformer_pert
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r environment.txt
```
