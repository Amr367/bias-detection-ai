# bias-detection-ai
Research internship challenge: Bias Detection and Explainability in AI Models 
# Bias Detection and Explainability in AI Models

This project was submitted as part of the CIS-2025-19 Research Internship at Nile University.

## 🔍 Project Overview
We trained a logistic regression model to predict hiring decisions based on structured applicant features. We analyzed the model for gender-related bias and applied mitigation techniques.

## 📊 Dataset
- 1,500 applicant records
- Features: Age, Gender, EducationLevel, ExperienceYears, InterviewScore, SkillScore, etc.
- Target: HiringDecision (1 = Hired, 0 = Not Hired)

## 🧠 Model
- Algorithm: Logistic Regression
- Accuracy: 85.7%
- Evaluation: Confusion Matrix, Classification Report

## ⚖️ Fairness & Bias Analysis
- Metrics: Demographic Parity, Equal Opportunity, Average Odds Difference
- Gender bias observed before mitigation
- Counterfactual data augmentation reduced disparities

## 🧪 Explainability
- SHAP used to explain predictions
- Features like SkillScore and InterviewScore were influential

## 📂 Files
- `bias_detection.ipynb`: Main notebook
- `AI_Bias_Report_Amr.pdf`: Final PDF report
- `hire_rate_gender.png`: Gender-based hire rate plot
- `README.md`: Project overview

# 📌 Author
- Amr Said – AI Intern Applicant at Nile University
