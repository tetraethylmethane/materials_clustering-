# Material Clustering for Efficient Component Manufacturing

## 📌 Problem Statement

Manual material selection is slow, error-prone, and often fails to capture **multidimensional property similarities**. This results in longer design cycles and suboptimal material utilization.

To address this, we apply **unsupervised machine learning (K-Means clustering)** to group materials with similar mechanical properties, enabling faster and more accurate decision-making.

---

## 🎯 Objectives

* Develop a **K-Means clustering model** for material classification.
* Reduce engineering decision-making time.
* Improve the accuracy of material selection in component manufacturing.

---

## 📂 Dataset

* **Source**: [Kaggle - Materials Dataset](https://www.kaggle.com/datasets/purushottamnawale/materials/data)
* **Features Used**:

  * Ultimate Tensile Strength (Su)
  * Yield Strength (Sy)
  * Elongation at Break (A5)
  * Hardness (BHN)
  * Elastic Modulus (E)
  * Shear Modulus (G)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Handling missing values
* Feature engineering & selection
* Normalization using **StandardScaler** / **MinMaxScaler**

### 2. Model Design

* **K-Means clustering**
* Optimal number of clusters (K) determined via:

  * **Elbow Method**
  * **Silhouette Score**

### 3. Validation

* **PCA** (Principal Component Analysis)
* **t-SNE** (t-Distributed Stochastic Neighbor Embedding)

---

## 📊 Results

* **Optimal clusters** identified using Silhouette analysis.
* PCA projections confirmed **well-separated clusters**.
* Each cluster profile was analyzed based on **mechanical property averages**, highlighting distinctions in:

  * Strength
  * Ductility
  * Hardness
  * Stiffness

These insights enable **quick material selection** for engineers.

---

## 🚀 Outcomes

* Reduced manual effort in material classification.
* Data-driven insights for **efficient component manufacturing**.
* Ready-to-use **Colab Notebook**: [Open Notebook](https://colab.research.google.com/drive/1TLGp2HWcwKwkvyhBkYde8hSruProSMG_?usp=sharing)

---

## 📁 Repository Structure

```
├── Material_Clustering.ipynb    
├── Data.csv                   
├── README.md                    
```

---

## 👨‍💻 Team Members

* Swastik Kumar (1024060150)
* Manav Pansari (1024060151)
* Muskan Garg (1024060163)
* Deepak Kumar (1024060133)
* Vansh Sharma (1024060117)

---
