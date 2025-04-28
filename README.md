
# Towards Generalizable Mental Workload Classification for Self-Collected EEG Data

> **Master’s Thesis by Aleksandar Ilievski** 🎓

This repository contains the code, data structure, and resources developed for my Master’s Thesis *"Towards Generalizable Mental Workload Classification for Self-Collected EEG Data."*  
The project explores the challenges and possibilities of session- and subject-independent workload classification using EEG data collected independently by participants outside controlled laboratory settings.

## Overview

- **EEG Data** were collected using wearable dry-electrode headphones across 10 sessions per participant.
- **Nine machine learning and deep learning models** were benchmarked under session- and subject-independent evaluation strategies.
- **Training and evaluation** were developed and conducted in **Google Colab**.  
  > **Note:** The notebook is optimized for Google Colab. Local execution may require minor adjustments (e.g., path management or device settings).

## Repository Structure 📁

```
workload-classification/
│
├── at_home_data.pkl           # EEG dataset
├── notebook.ipynb             # Full analysis and training notebook
├── requirements.txt           # List of Python dependencies
│
├── models/                    # Model architectures
│   ├── eegnet.py
│   ├── eegconformer.py
│   └── tsception.py
│
├── utils/                     # Utility functions
│   ├── config.py               # Configuration and hyperparameters
│   ├── dataset.py              # Custom Dataset and DataLoader
│   └── training.py             # Training and evaluation functions
│
├── experiments/               # Scripts for running experiments
│   ├── train_eegnet.py
│   ├── train_eegconformer.py
│   └── train_tsception.py
│
└── results/                   # Results, logs, and checkpoints
```

## How to Use 🚀

1. Open the provided **`notebook.ipynb`** in **Google Colab**.
2. Follow the notebook instructions to load the data, train models, and evaluate performance.

> If you intend to run scripts manually or outside Google Colab, installing dependencies from `requirements.txt` and adjusting paths/device settings may be necessary.

## Requirements

Dependencies are listed in **`requirements.txt`** for easy setup.  
You can install them locally using:

```bash
pip install -r requirements.txt
```

## Acknowledgments

Special thanks to my advisor Dr. Michael Knierim for guidance and support.
