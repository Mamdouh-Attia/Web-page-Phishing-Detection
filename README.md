# 🕵️‍♂️ Web Page Phishing Detection using Machine Learning

Welcome to the **Web-page-Phishing-Detection** project! This repository contains a complete workflow for detecting phishing web pages using state-of-the-art machine learning techniques. 🚦🔒

---

## 🚀 Project Overview

Phishing attacks are a major threat to online security. This project leverages machine learning to automatically classify web pages as **phishing** or **legitimate** based on a rich set of features extracted from URLs and page content.

---

## 📂 Repository Structure

```
Web-page-Phishing-Detection-main/
│
├── data/
│   └── dataset_phishing.csv         # Main dataset with 11,430 samples & 89 features
│
├── models/
│   ├── adaboost_classifier.pkl
│   ├── bagging_classifier.pkl
│   ├── decision_tree.pkl
│   ├── ensemble_voting_classifier_top5.pkl
│   └── ...                         # Other trained model files
│
├── best_model.pkl                  # Best performing model (Random Forest)
├── phishing_model_random_forest.pkl
├── phishing_model_random_forest_exp2.pkl
├── phishing_model.pkl
│
├── workflow_notebook.ipynb         # Main ML workflow notebook
├── workflow_notebook_experiment2.ipynb
├── Hyperparameter_tuning_workflow_notebook_experiment2.ipynb
│
├── README.md                       # This file!
├── .gitignore
├── LICENSE
│
├── CMP4040 - Project Document.docx # Project documentation
├── Team 9 - ML Project Report.docx
├── Team 9 - ML Project Report.pdf
└── ...
```

---

## 🧑‍💻 Implementation Highlights

- **Data Preprocessing:**  
    - Loads and cleans `dataset_phishing.csv` (see `workflow_notebook.ipynb`).
    - 89 features per sample, including URL structure, content analysis, and more.

- **Model Training:**  
    - Multiple ML models implemented: Decision Tree, Random Forest, AdaBoost, Bagging, and Ensemble Voting.
    - Hyperparameter tuning for optimal performance (`Hyperparameter_tuning_workflow_notebook_experiment2.ipynb`).

- **Evaluation & Selection:**  
    - Models evaluated for accuracy, precision, recall, and F1-score.
    - Best model saved as `best_model.pkl`.

- **Experimentation:**  
    - Alternative workflows and experiments in `workflow_notebook_experiment2.ipynb`.

- **Documentation:**  
    - Detailed project and team reports included for reference.

---

## 📊 How to Use

1. **Clone the repository:**
     ```bash
     git clone https://github.com/<your-username>/Web-page-Phishing-Detection-main.git
     ```

2. **Explore the notebooks:**
     - Open `workflow_notebook.ipynb` for the main workflow.
     - Use `Hyperparameter_tuning_workflow_notebook_experiment2.ipynb` for tuning experiments.

3. **Run the models:**
     - Load any `.pkl` model and use it to predict phishing URLs.

---

## 📝 Notebooks

- **`workflow_notebook.ipynb`**  
    Main pipeline: data loading, feature engineering, model training, evaluation.

- **`workflow_notebook_experiment2.ipynb`**  
    Alternative experiments and model comparisons.

- **`Hyperparameter_tuning_workflow_notebook_experiment2.ipynb`**  
    Hyperparameter optimization for improved accuracy.

---

## 📑 Dataset

- **`data/dataset_phishing.csv`**  
    - 11,430 web page samples  
    - 89 features per sample  
    - Label: `phishing` or `legitimate`

---

## 🏆 Models

- **Random Forest** (best model)
- Decision Tree
- AdaBoost
- Bagging
- Ensemble Voting

All models are saved in the `models/` folder as `.pkl` files for easy reuse.

---

## 📄 Documentation

- **Project Reports:**  
    - `CMP4040 - Project Document.docx`
    - `Team 9 - ML Project Report.docx` / `.pdf`

---

## 👥 Authors & License

- Developed by [Mamdouh Attia](https://github.com/Mamdouh-Attia)
- Licensed under the [MIT License](LICENSE)

---

## 🌟 Get Started!

Ready to fight phishing?  
Dive into the notebooks, train your own models, or use the pre-trained ones to protect users from malicious web pages!

---

> **Stay safe. Stay smart. Detect phishing with ML!**
