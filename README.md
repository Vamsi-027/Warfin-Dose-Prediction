# 💊 Warfarin Dose Prediction Using Machine Learning

## 📜 Project Overview
This project aims to **predict the therapeutic dose of Warfarin** using **machine learning models** to enhance precision in **anticoagulant therapy**. Warfarin dosing is a complex process due to **inter-patient variability** and its **narrow therapeutic index**, making accurate dose prediction crucial to minimize adverse health effects.

In this project, we utilized the publicly available **International Warfarin Pharmacogenetics Consortium (IWPC)** dataset sourced from **PharmGKB** to build and evaluate four different machine learning models:
- ✅ **K-Nearest Neighbors (KNN)**
- ✅ **Random Forest (RF)**
- ✅ **Support Vector Regression (SVR)**
- ✅ **Feed Forward Neural Networks (FFNN)**

The goal was to identify the model that provides the most **accurate Warfarin dose prediction**, helping to personalize medicine and reduce the risk of over or under-dosing.

---

## 📊 Dataset
### **Dataset Source**
The dataset used in this project is publicly available from **PharmGKB** through the **International Warfarin Pharmacogenetics Consortium (IWPC)**.

- **Dataset Name:** International Warfarin Pharmacogenetics Consortium (IWPC)
- **Source:** [PharmGKB Website](https://www.pharmgkb.org/)
- **Description:** Contains patient information such as demographic data, clinical data, and genetic data related to Warfarin dosage.

---

---

## 📊 Model Evaluation
We compared the performance of four different models based on the following metrics:

| Model                        | MAE ↓    | MSE ↓     | R² Score ↑     |
|------------------------------|---------|-----------|----------------|
| **K-Nearest Neighbors (KNN)** | **5.21** | 48.15     | 0.58           |
| **Random Forest (RF)**        | **4.87** | 42.31     | **0.63**       |
| **Support Vector Regression** | 5.56     | 52.21     | 0.54           |
| **Feed Forward Neural Network** | **4.45** | **39.42** | **0.67**       |

### ✔ Best Performing Model:
The **Feed Forward Neural Network (FFNN)** outperformed other models with:
- Lowest **Mean Absolute Error (4.45)**
- Highest **R² Score (0.67)**

---

✅ If you found this project helpful, please give it a ⭐ on GitHub! 💯

