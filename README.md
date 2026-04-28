# Electrical Grid Stability Prediction

This project focuses on predicting the stability of an electrical grid using various Machine Learning algorithms. The workflow is split into two distinct phases: initial modeling and advanced hyperparameter tuning.

## 📊 Project Overview
The goal is to classify whether the smart grid system is stable or unstable based on predictive parameters.

### Phase 1: Algorithm Exploration
* Implementation of baseline models: SVM (RBF), Decision Trees, Random Forest, AdaBoost, and Gradient Boosting.
* Initial performance evaluation using F1-score.

### Phase 2: Hyperparameter Tuning & Optimization
* **Optimization:** Used `GridSearchCV` and `RandomizedSearchCV` to find optimal parameters for each model.
* **Feature Engineering:** Applied **PCA** (Principal Component Analysis) and **SelectPercentile** for feature reduction/selection.
* **Visualization:** Created t-SNE embeddings and performance comparison charts to validate results.

## 📈 Key Results
The models showed significant improvement after tuning. The **SVM (RBF)** and **Gradient Boosting** models emerged as top performers with F1-scores exceeding 0.95.

## 📂 Dataset
The dataset used in this project is the **Electrical Grid Stability Simulated Dataset** from the UCI Machine Learning Repository.
* **Dataset Link:** [UCI Machine Learning Repository - Electrical Grid Stability](https://archive.ics.uci.edu/ml/datasets/electrical+grid+stability+simulated+data+)
*(Note: Due to file size/licensing, the raw data is not hosted in this repo. Please download it from the link above and place it in the project root to run the notebooks.)*

## 🛠️ Requirements
* Python 3.x
* Pandas, NumPy
* Scikit-Learn
* Matplotlib, Seaborn
