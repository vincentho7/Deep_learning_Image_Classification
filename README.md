Kaggle Competition — Ship Classification (EPITA 2023)

Image classification challenge on a dataset of ~33 700 ship photographs across 10 vessel categories, with significant class imbalance.

Ranked 8th out of 100 teams — accuracy : 0.83

Two models were developed and compared :

A CNN built from scratch (< 30 layers) — shipclassification.ipynb
A transfer learning approach using a pre-trained CNN — navirelibre.ipynb

Key challenge : handling class imbalance across 10 categories ranging from cv_scaled (1 827 samples) to containership_scaled (5 454 samples).
Tech stack : Python, Tensorflow, NumPy, Matplotlib

Vincent THONG & Maxime Boy Arnould
