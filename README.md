# CardioSense — Heart Disease Predictor

A compact, reproducible machine-learning project that predicts heart disease risk from clinical features using the UCI/Kaggle heart dataset.  
The notebook compares multiple classifiers and demonstrates a K-Nearest Neighbors (KNN) model that achieves strong test accuracy.

---

## Highlights
- Reproduces end-to-end ML workflow: data load → EDA → preprocessing → modeling → evaluation.  
- Compares multiple classifiers (KNN, SVM, Decision Tree, Random Forest).  
- KNN hyperparameter sweep (k = 1..20) shows a top performing model (reported ≈87% test accuracy).

---

## Files
- `Heart Disease Prediction.ipynb` — main Jupyter notebook with code, plots, and commentary.  
- `dataset.csv` — heart disease dataset (Kaggle / UCI format).  
- `README.md` — this file.  
- `LICENSE` — MIT license.

---

## Requirements
- Python 3.8+  
- Jupyter Notebook (optional, recommended)  
- Libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
