# Human-in-the-Loop Machine Learning for Toxicity Detection  
*MSc Thesis – University of Limerick (2025)*  

This repository contains the code and materials from my Master’s thesis:  
**“Human-in-the-Loop Machine Learning for Real-Time Feedback Systems”**  

The project explores **toxicity detection in online text** using traditional ML models enhanced by a **human-in-the-loop (HIL) feedback pipeline** to improve performance and fairness.

---

## 🔹 Project Overview
- **Task**: Classify online comments as toxic or non-toxic.  
- **Baseline Models**: Logistic Regression & SVM with TF–IDF n-grams.  
- **Human-in-the-Loop**: Collected annotations for low-confidence / high-disagreement cases.  
- **Key Results**:  
  - Precision: 0.92 (baseline & HIL)  
  - Recall: **0.62 → 0.64**  
  - F1: **0.74 → 0.76**  
  - AUC: 0.97 → 0.967  
  - Fairness: Reduced false negatives in minority subgroups  

---

## 🔹 Datasets
- [Jigsaw Toxic Comment Classification](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)  
- [Civil Comments Dataset](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data)  

⚠️ Datasets are **not included** due to size and licensing restrictions. Please download them from Kaggle and place in the `data/` folder.  
A small `sample.csv` can be added for demo purposes.  


