
# Towards Generalizable Mental Workload Classification for Self-Collected EEG Data

> **Master’s Thesis by Aleksandar Ilievski** 🎓

This is the official repository for my Master’s Thesis *"Towards Generalizable Mental Workload Classification for Self-Collected EEG Data."*  
The project explores the challenges and possibilities of session- and subject-independent workload classification using EEG data collected independently by participants outside controlled laboratory settings.

## Quick Start 🚀

**1. Download Dataset:**  [![Download Data](https://img.shields.io/badge/Download-at_home_data.pkl-success?logo=google-drive&logoColor=white)](https://drive.google.com/uc?id=1HpaUvauJwK04ftqqrOAZWjscVMcefecp&export=download) 


**2. Open Notebook in Colab:**  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AleksandarIlievski/workload-classification/blob/main/mwl_classification.ipynb) 


## Project Description 📚

- **Data Collection:** EEG signals were collected using wearable dry-electrode headphones across 10 sessions per participant in home environments.
- **Model Benchmarking:** 9 machine learning and deep learning models were evaluated under both session- and subject-independent settings.
- **Development:** The entire project was developed and tested within **Google Colab** for accessibility and reproducibility.

> **Note:** The notebook is optimized for Google Colab. Local execution may require minor adjustments.


## Repository Structure 📁

```
workload-classification/
│
├── at_home_data.pkl           # EEG dataset (download separately)
├── notebook.ipynb             # Full analysis and training notebook
├── requirements.txt           # List of Python dependencies
└── results/                   # Results and logs
```

---

## How to Use

1. Download the dataset using the **"Download Data"** button.
2. Click **"Open in Colab"** to launch the notebook in Google Colab.
3. Upload `at_home_data.pkl` and the `results` folder to the Colab environment and adjust the paths in the notebook.
4. Follow the notebook instructions to load the data, train models, and evaluate performance.

> If running locally, install required dependencies from `requirements.txt` and ensure device settings (e.g., GPU) are configured correctly.

---

## Acknowledgments

Special thanks to my advisor Dr. Michael Knierim for guidance and support.
