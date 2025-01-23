# Moth Classification in Hanover, NH

This repository contains the code and resources for a machine learning project aimed at identifying moth species found in Hanover, NH. The project was conducted as part of a research collaboration with Professor Matt Ayres at Dartmouth College. The primary model classifies 22 moth species with high accuracy (~90%), while an initial binary classification model determines whether an image contains a moth or not.

A working demo is available at **[aydenhayes.com/upload](https://aydenhayes.com/upload)**.  
If the demo is down, please email me at **aydenhayes.26@dartmouth.edu**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [File Descriptions](#file-descriptions)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [How to Use](#how-to-use)
- [Planned Improvements](#planned-improvements)
- [Acknowledgments](#acknowledgments)

---

## Project Overview
This project was developed to classify moth species in Hanover, NH, using machine learning. The dataset consists of images collected from research sources, and the model was trained to recognize 22 species (only those with at least 10 samples). The goal was to assist ecological research and biodiversity monitoring.

The project consists of two models:
1. **Binary Classification Model** - Determines if an image contains a moth.
2. **Species Classification Model** - Identifies the species of a moth from 22 possible categories.

## Features
- **Binary classification** to filter moth images before species classification.
- **Multi-class classification** capable of identifying 22 species.
- **High accuracy (~90%)** despite a limited dataset.
- **Jupyter Notebook-based development** for ease of experimentation.
- **Plans for Linux research cluster migration** for further training and optimization.

## File Descriptions
- `is_moth.ipynb` – The initial binary classification model to distinguish between moth and non-moth images.
- `moth_classification.ipynb` – The full classification model that identifies species among 22 categories.

## Dataset
The dataset consists of moth images collected for research purposes. Due to data constraints, only species with at least **10 samples** were included in training.

- **Number of species:** 22
- **Training images per species:** At least 10
- **Preprocessing:** Standardization, augmentation, and resizing techniques applied to optimize training.

## Model Performance
- **Binary Classification Accuracy:** High accuracy in distinguishing moth vs. non-moth images.
- **Species Classification Accuracy:** ~90% accuracy on test data.
- **Challenges:** Some species are visually similar, leading to occasional misclassification.

## How to Use
### 1. Install Dependencies
Ensure you have Python and the necessary libraries installed. Currently, no requirements.txt is provided.

### 2. Start Jupyter Notebook and run the provided .ipynb files:
```bash
jupyter notebook
```
Open and execute is_moth.ipynb for binary classification or moth_classification.ipynb for species identification.


---
## Planned Improvements
- 🔄 **Migration to a Linux research cluster** for further training and scalability.
- 📈 **Expansion of the dataset** to include more species.
- ☁️ **Deployment of a live API** for remote classification.
- 🎨 **Improved UI for the web demo** to allow easy uploads and visualization.
- 🏆 **Model optimization** by experimenting with different architectures (e.g., ResNet, EfficientNet).
- 🛠 **Automated data augmentation** to improve model generalization.
- 📊 **Improved result interpretation** using Grad-CAM or SHAP for explainability.

---

## Acknowledgments
This project was developed in collaboration with **Professor Matt Ayres** at **Dartmouth College**. 

For any issues or suggestions, feel free to open an issue on GitHub or contact me via email: **aydenhayes.26@dartmouth.edu**.

---



