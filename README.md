# DUNE Experiment – Fine-Grained Storage Simulation (GSoC 2026 Warm-Up)

This repository contains the technical warm-up exercise for the **Fine-Grained Storage for the DUNE Experiment** proposal, submitted to **Google Summer of Code 2026** under **CERN-HSF**.

## Objective

Simulate simplified storage designs to analyze file I/O performance under three storage strategies:
- **Single Large File**
- **Chunked Files** (1000 records per file)
- **Individual Files** (one file per record)

Benchmark performance for both **sequential** and **random** read access, and evaluate trade-offs between coarse-grained and fine-grained storage layouts.

---

## Contents

- `dune-experiment-evaluation.ipynb` — Main Jupyter Notebook (Python 3)
- `Gsoc_evaluation.pdf` — One-page final report (compiled from LaTeX)

---

## How to Run

### Option 1: Run on Kaggle (Recommended)
1. Upload `dune-experiment-evaluation.ipynb` to a new Kaggle Notebook
2. Click “Run All” — no setup required, uses only built-in Python modules

### Option 2: Run Locally
1. Install Python 3 if not already installed
2. Open the notebook:
```bash
jupyter notebook dune-experiment-evaluation.ipynb
