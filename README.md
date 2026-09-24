# Predictive Modeling of Tensile Strength in FDM-Printed PLA via Machine Learning

This repository contains the dataset, modeling pipelines, and empirical formulations developed for the undergraduate engineering thesis:
> **"Predictive Modeling of Tensile Strength in FDM-Printed PLA Composites via Hybrid Machine Learning"**  
> *Department of Mechanical and Production Engineering (MPE)*  
> *Islamic University of Technology (IUT), Organisation of Islamic Cooperation (OIC)*

---

## Repository Contents
* `FDM_Tensile_Strength_Prediction.ipynb`: Complete, end-to-end Python pipeline including:
  * Specimen-level group partitioning (`GroupShuffleSplit` & `GroupKFold`) for zero data leakage.
  * Production Machine Learning (Tuned Random Forest and Tuned XGBoost).
  * 15-term closed-form Ordinary Least Squares (OLS) regression.
  * Constrained Latent Hybrid Neural Network ($H, V, A, F$ bottleneck).
  * SHAP interpretability and feature attribution.

---

## How to Run
1. Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Select **File** -> **Upload Notebook** and upload `FDM_Tensile_Strength_Prediction.ipynb`.
3. Run all cells sequentially.
