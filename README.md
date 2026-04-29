# 🧠 Data Mining Lab

A hands-on project exploring fundamental data mining techniques including classification, clustering, and association rule mining using real and synthetic datasets.

---

## 🚀 Project Overview

This repository contains practical implementations of key data mining concepts:

* 🌸 **Classification (Iris Dataset)**
* 🧬 **Classification (Breast Cancer Dataset)**
* 🌀 **Clustering (K-Means)**
* 🔗 **Association Rule Mining (Apriori Algorithm)**
* 🟠 **ORANGE Tool Experiments**
* 🔵 **WEKA Tool Experiments**

Each experiment demonstrates both implementation and interpretation of results.

---

## 📁 Project Structure

```
data-mining-lab/
│
├── notebooks/
│   ├── iris_classification.ipynb
│   ├── breast_cancer_classification.ipynb
│   ├── clustering.ipynb
│   └── association_rules.ipynb
│
├── data/
├── results/
├── weka/
├── orange/
└── README.md
```

---

## 🌸 1. Iris Classification

* Algorithms: K-Nearest Neighbors, Decision Tree
* Achieved **100% accuracy** due to well-separated classes
* Key Insight: Simple datasets allow multiple models to perform equally well

---

## 🧬 2. Breast Cancer Classification

* Algorithm: Logistic Regression
* Accuracy: **~96%**
* Evaluated using:

  * Precision
  * Recall
  * F1-score

**Insight:** Accuracy alone is not enough — detailed metrics provide better understanding in real-world problems.

---

## 🌀 3. Clustering (K-Means)

* Used Elbow Method to determine optimal clusters (k = 3)
* Silhouette Score ≈ **0.55**

**Insight:** Even without labels, data naturally forms meaningful groups.

---

## 🔗 4. Association Rules (Apriori)

* Custom market basket dataset created
* Discovered rules like:

  * 🥛 Milk → 🍞 Bread

**Key Metrics:**

* Support
* Confidence
* Lift

**Insight:** Association rules reveal hidden relationships useful in recommendation systems and retail analysis.

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Mlxtend

---

## 🧪 Tools Explored

### 🟠 ORANGE

* Visual workflow-based data mining
* Used for classification and clustering experiments

### 🔵 WEKA

* GUI-based machine learning tool
* Used to compare algorithm performance

---

## 📊 Key Learnings

* Different algorithms behave differently depending on dataset complexity
* Visualization helps in understanding data patterns
* Evaluation metrics are crucial for real-world applications
* Data mining is not just about models, but also about interpretation

---

## ✨ Conclusion

This project demonstrates the practical application of core data mining techniques across multiple datasets and tools. It highlights the importance of both implementation and analytical thinking in extracting meaningful insights from data.

---

## 👨‍💻 Author

* Keerti Lata Choudhury

---

## ⭐ If you found this useful, consider giving it a star!
