# 📊 Principal Component Analysis on Young People Survey Dataset

This project focuses on the use of **Principal Component Analysis (PCA)** and **K-Means Clustering** to explore and extract insights from a rich, real-world survey dataset.

---

## 🧠 Project Overview

The aim of this project is to simulate a **real-world business scenario** in which a company collects detailed survey responses from over 1,000 individuals. The ultimate goal is to **reduce the complexity of the dataset** (dimensionality reduction) and **identify consumer profiles** (clustering), which can then be used for personalized marketing, product suggestions, or targeted campaigns.

---

## 📁 Dataset Description

The dataset used is the **Young-People Survey (YPS)** dataset, which includes a wide variety of features related to lifestyle, preferences, and behavior. The main feature groups include:

- **Music Preferences** (e.g., classical, hip-hop, rock)
- **Movie Preferences** (e.g., horror, comedy, documentary)
- **Hobbies and Interests** (e.g., dancing, reading, sports)
- **Phobias** (e.g., fear of darkness, public speaking)
- **Health Habits** (e.g., alcohol consumption, smoking)
- **Personality Traits** (e.g., empathy, energy levels)
- **Spending Habits** (e.g., spending on tech, fashion)
- **Demographic Info** (e.g., gender, age, country)

📥 **[Download the dataset from Kaggle](https://www.kaggle.com/datasets/miroslavsabo/young-people-survey)**

---

## 🎯 Project Goals

### 1. **Dimensionality Reduction**
- Apply **PCA** to the dataset.
- Reduce the number of features to **no more than 5**, while preserving at least **33% of the total variance**.
- Identify and interpret the principal components.

### 2. **Clustering Analysis**
- Use **K-Means Clustering** on the PCA-reduced data.
- Evaluate different values of **k** (number of clusters), with **3 ≤ k ≤ 10**.
- Use **inertia** and **silhouette scores** to select the best number of clusters.
- Interpret the resulting clusters as potential **customer profiles**.

---

## 🛠️ Tools & Technologies

- **Language:** Python  
- **Notebook:** Jupyter Notebook  
- **Libraries:**  
  - `numpy`, `pandas` – data manipulation  
  - `sklearn` – PCA and k-means clustering  
  - `matplotlib`, `seaborn` – data visualization  

---

## 📈 Results Summary

- Successfully reduced the dataset from **numerous features** to **5 principal components**, preserving over **35% of the variance**.
- Identified **4 distinct customer segments** using **K-Means**, supported by silhouette score evaluation.
- Visualized clusters in 2D PCA space for interpretability.
- Provided business-oriented insights into each cluster based on loading scores and centroid analysis.

---

## 📂 Repository Content

| File | Description |
|------|-------------|
| `PCA_analysis.ipynb` | Jupyter notebook containing the full PCA and clustering workflow |


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Keremm26/pca-analysis.git
   cd pca-analysis
   ```
2. Open `PCA_analysis.ipynb` with **Jupyter Notebook** or **VS Code**.
3. Make sure to install required libraries (if not already installed):
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
4. Run the notebook cells step-by-step.

---

## 👩‍🔬 Author

**Kerem Kose**  

