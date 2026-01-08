# Machine Learning for Sports Analytics: NBA MVP Prediction

## Bachelor’s Thesis (2024-2025)

This repository contains the implementation and experimental results of my **Bachelor’s Thesis** entitled:

**Machine Learning for Sports Analytics: NBA MVP Prediction**

The objective of this study is to investigate the effectiveness of different machine learning and deep learning models in predicting the **NBA Most Valuable Player (MVP)** using structured and relational basketball data.

---

## Thesis Summary

- **Problem:** Predicting NBA MVP awards from historical player-season data
- **Data:** 10,000+ player-season records spanning over 20 NBA seasons
- **Challenge:** Severe class imbalance (single MVP per season)
- **Focus:** Model comparison, feature engineering, and robust evaluation

The study emphasizes **methodological rigor, reproducibility, and interpretability**, rather than leaderboard-style optimization.

---

## Models Implemented

The following models were designed, trained, and evaluated:

- **XGBoost**
- **RandomForest**
- **KNN**
- **SVM**
- **CatBoost** 
- **LightGBM**
- **Convolutional Neural Networks (CNN)**
- **Graph Neural Networks (GNN)**

Both structured statistical features and relational representations between players and seasons were explored.

---

## Evaluation

Model performance was assessed using:

- Precision  
- Recall  
- F1-score  
- Confusion matrices  

---

## Repository Structure

machine-learning-for-sports-analytics-nba-mvp/
│
├── datasets/ # Raw and processed datasets
├── best_models/ # Saved trained models
├── dataset_crossvalidation_result/ # Baseline CV results
├── data_augmented_crossvalidation_result/
├── models.py # Model architectures
├── Train.py # Training pipeline
├── Test.py # Evaluation pipeline
├── MVP_Predictions_Top10.xlsx # Sample prediction outputs

## How to Run

1. Install dependencies (Python 3.9+ recommended)
2. Check dataset (use dataset_preprocessing if necesarry)
2. Train models:
```bash
python Train.py
```
3. Evauluate models : 
python Test.py
