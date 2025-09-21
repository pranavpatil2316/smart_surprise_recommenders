# Implementing Recommendation Models using Surprise

This repository contains a Google Colab–ready Jupyter Notebook implementing and evaluating three popular recommendation algorithms — **SVD**, **KNNBasic**, and **NMF** — using the `surprise` library on the MovieLens 100k dataset. It follows the steps outlined in the provided experiment instructions.

## 📂 Contents

* `Implementing_Recommendation_Models_Surprise.ipynb` – The main notebook with code and explanations.
* Evaluation metrics and visualizations (RMSE, MAE comparisons, grid search results).
* Top-N recommendation generation and Precision/Recall at K.

## 📝 Experiment Objectives

* Load and preprocess MovieLens 100k dataset.
* Implement SVD, KNNBasic, and NMF collaborative filtering algorithms.
* Evaluate each model using RMSE and MAE.
* Perform hyperparameter tuning using GridSearchCV.
* Generate Top-N recommendations and compute Precision\@K and Recall\@K.
* Visualize results with charts.

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook: **File → Upload Notebook**.
3. Run the first cell to install `scikit-surprise`.
4. Run all cells in order to reproduce the experiment and visualizations.

## 📊 Output

* Comparison table of RMSE and MAE for all algorithms.
* Best hyperparameters and scores from grid search.
* Top-N recommendations for sample users.
* Bar plots for RMSE and MAE comparison.
* Table of grid search results for SVD.

## ✅ Conclusion

SVD achieved the best accuracy on the MovieLens 100k dataset, while KNNBasic and NMF offered different trade-offs. Grid search tuning improved performance, and Top-N recommendations illustrated the application of these models to real-world scenarios.

---
