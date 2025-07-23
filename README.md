# compas-recidivism-analysis
Machine learning models applied to the COMPAS dataset, exploring predictive performance, bias, and fairness.

# COMPAS Recidivism Analysis 🧠⚖️

This repository contains my assignment for the *Smart Industry Operations* course (2024–2025) at the University of Groningen. The project focuses on building and evaluating machine learning classifiers to assess recidivism risk using the COMPAS dataset, with special attention to bias and fairness across race, age, and gender.

## 📘 Assignment Context

The COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) system is a predictive tool used in the U.S. justice system to assess the risk of criminal recidivism. This assignment explores:
- How classification models behave on this dataset
- How bias and fairness manifest in predictions
- How the exclusion of sensitive attributes (e.g., race, gender) affects performance

## 📁 Contents

- `compas_reclassification_analysis.ipynb`: Main notebook with all modeling steps, bias analysis, and results.
- `SIO 2024-2025 - Individual Assignment - Assignment 21.pdf`: Official assignment instructions provided by the course.
  
## 🧪 Models Used

- Decision Tree
- Random Forest
- Naïve Bayes
- Support Vector Machine (SVM)

Each model was evaluated with and without sensitive attributes to explore bias in prediction.

## 📊 Dataset

The dataset is based on public data from ProPublica:
- https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm
- https://github.com/propublica/compas-analysis

## ⚠️ Disclaimer

This project was created for academic purposes and uses publicly available data. No confidential or private information is included in this repository.

## 🧠 Author

Maria Niki Antonopoulou  
MSc Technology & Operations Management  
University of Groningen

## 📄 License

This project is licensed under the [MIT License](LICENSE).

