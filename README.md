
# Towards Generalizable Mental Workload Classification for Self-Collected EEG Data

> **Master’s Thesis by Aleksandar Ilievski** 🎓

This repository contains the code, data structure, and resources developed for my Master’s Thesis *"Towards Generalizable Mental Workload Classification for Self-Collected EEG Data."*  
The project explores the challenges and possibilities of session- and subject-independent workload classification using EEG data collected independently by participants outside controlled laboratory settings.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1LZMl9t2vB1sM2XhFzEstHbF8In2g4nS3/view?usp=share_link)

## Overview

- **EEG Data** were collected using wearable dry-electrode headphones across 10 sessions per participant.
- **Nine machine learning and deep learning models** were benchmarked under session- and subject-independent evaluation strategies.
- **Training and evaluation** were developed and conducted in **Google Colab**.  
  > **Note:** The notebook is optimized for Google Colab. Local execution may require minor adjustments.

## Repository Structure 📁

```
workload-classification/
│
├── at_home_data.pkl           # EEG dataset
├── notebook.ipynb             # Full analysis and training notebook
├── requirements.txt           # List of Python dependencies
└── results/                   # Results and logs
```

## How to Use 🚀

1. Open the provided **`notebook.ipynb`** in **Google Colab** or click the link above.
2. Follow the notebook instructions to load the data, train models, and evaluate performance.

> If you intend to run scripts manually or outside Google Colab, installing dependencies from `requirements.txt` and adjusting paths/device settings may be necessary.

## Acknowledgments

Special thanks to my advisor Dr. Michael Knierim for guidance and support.
