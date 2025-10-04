# Parkinson’s Disease Detection using Ensemble Learning & Optimization

## 📌 Project Overview

This project focuses on the **early detection of Parkinson’s disease** using machine learning and ensemble techniques.
The proposed method combines **Bagging with Teaching-Learning Optimization (TLO) / Firefly Algorithm** to enhance classification performance by balancing accuracy and diversity.

Key Highlights:

* Dynamic bag size to balance bias and variance.
* Fitness function designed to optimize both accuracy and diversity.
* Ensemble of classifiers including **SVM, KNN, Decision Tree, SGD, and MLP**.
* Evaluation using diversity measures such as **Bhattacharya distance, Entropy, and Q-statistics**.
* Tested on benchmark Parkinson’s disease datasets.

---

## 📂 Repository Structure

```
📦 Parkinsons-Disease-Detection
 ┣ 📜 Parkinsonss.ipynb        # Main notebook (code & experiments)
 ┣ 📜 requirements.txt         # Dependencies
 ┣ 📜 README.md                # Project documentation
 ┗ 📂 data/                     # Dataset (not included here, see below)
```

---

## 📊 Dataset

We used the **UCI Parkinson’s dataset**, which includes biomedical voice measurements from 31 people (23 with Parkinson’s, 8 healthy).

* Features: 22 voice-based attributes (e.g., jitter, shimmer, fundamental frequency).
* Target: Binary classification (Parkinson’s vs. Healthy).

📌 Dataset link: [UCI Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)

---

## ⚙️ Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/parkinsons-detection.git
cd parkinsons-detection
pip install -r requirements.txt
```

Typical dependencies include:

* Python 3.8+
* numpy, pandas
* scikit-learn
* matplotlib, seaborn
* tensorflow / keras

---

## 🚀 Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Parkinsonss.ipynb
   ```

2. Run all cells to:

   * Preprocess the dataset
   * Train classifiers with Bagging + Optimization
   * Evaluate models (accuracy, precision, recall, F1)
   * Visualize results & diversity measures

---

## 📈 Results

* Base models achieved **80–85% accuracy**.
* Proposed ensemble method improved performance to **95–99% accuracy**.
* Diversity measures confirmed reduced overfitting and stronger generalization.

---

## 🔬 Research Contribution

* Introduced a **multi-model ensemble optimization** technique for Parkinson’s detection.
* Designed a **fitness function** combining accuracy & diversity.
* Showcased that optimized bagging outperforms standalone classifiers.

---

## 📌 Future Work

* Extend to larger datasets with more subjects.
* Apply deep learning architectures (CNN, ResNet, etc.) with optimization.
* Deploy as a web-based Parkinson’s screening tool.

---

## 📜 References

* Little, M.A. et al., "Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection", *BioMedical Engineering OnLine*, 2007.
* UCI Machine Learning Repository – Parkinson’s Dataset.

---

👉 This README is **ready for GitHub**.
Would you like me to also create a **requirements.txt** for your notebook automatically from the imports, so you can include it in your repo?
