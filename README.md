## 🎯 Objective

The aim of this lab is to preprocess features in the AEP dataset by applying:

- **Normalization** – To scale numerical features
- **One-Hot Encoding** – To convert categorical variables
- **Cyclical Encoding** – To transform periodic features like hours or months for better machine learning model understanding

---

## 📖 Introduction

Data preprocessing plays a vital role in building robust and effective machine learning models. This lab focuses on preparing the AEP dataset by applying three common techniques:

1. **Normalization** scales features to a similar range (usually [0, 1] or [-1, 1]), preventing features with larger magnitudes from dominating model training.

2. **One-Hot Encoding** converts categorical features into a numerical format without assuming any ordinal relationship.

3. **Cyclical Encoding** is especially useful for periodic features (e.g., hours, months), converting them into sine and cosine values to preserve their circular nature.

---

## 🛠 Tools Used

- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `sklearn`, `matplotlib`
