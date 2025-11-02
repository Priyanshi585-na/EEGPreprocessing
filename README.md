# 🧠 EEG Preprocessing Pipeline

This repository contains a Jupyter Notebook demonstrating a clean and efficient EEG preprocessing workflow using **MNE**, **NumPy**, and **Matplotlib**.  
It is designed to serve as a foundational template for neuroscience, brain–computer interface (BCI), or cognitive signal analysis projects.

---

## 📄 Overview

Electroencephalography (EEG) signals are often noisy and require careful preprocessing before feature extraction or modeling.  
This notebook walks through essential preprocessing steps using **one representative EEG sample file**.

### 🧩 Key Steps
- Load raw EEG data (e.g., `.edf`, `.fif`, or `.bdf`)
- Apply band-pass and notch filtering
- Visualize raw and cleaned EEG signals
- Detect and remove artifacts
- Compute and plot Power Spectral Density (PSD)

---

## ⚙️ Requirements

Install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
