# Amazon Customer Review Analytics

## Overview

This project analyzes **694,042 Amazon customer reviews** spanning **23 years (2000–2023)** to uncover customer sentiment, identify complaint patterns, generate personalized product recommendations, and understand customer churn behavior. By integrating machine learning, natural language processing (NLP), recommendation systems, and survival analysis, the project demonstrates how customer feedback can be transformed into actionable business insights for e-commerce decision-making. 

---

## Business Problem

Online retailers receive millions of customer reviews every year, making it difficult to manually identify customer concerns and opportunities for improvement.

This project addresses the following business question:

> **How can Amazon customer review data be used to improve customer satisfaction, personalize product recommendations, and reduce customer churn?** 

---

## Dataset

**Dataset:** Amazon Reviews 2023 Dataset

### Dataset Summary

- 694,042 customer reviews
- 631,809 unique customers
- 112,554 products
- Review period: 2000–2023

The dataset contains customer ratings, review text, product information, and customer activity used for predictive analytics and business intelligence. 

---

# Objectives

- Clean and preprocess large-scale customer review data
- Analyze customer sentiment using machine learning
- Discover common complaint themes using topic modeling
- Develop a personalized recommendation system
- Analyze customer retention using survival analysis
- Generate data-driven business recommendations

---

# Technologies Used

- Python
- SQL
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- Git & GitHub

---

# Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Sentiment Classification
5. Topic Modeling (LDA)
6. Recommendation System (SVD)
7. Survival Analysis
8. Business Recommendations

---

# Machine Learning & Analytics Methods

### Sentiment Classification

Models evaluated:

- Logistic Regression
- Random Forest

**Best Model**

- Logistic Regression
- Accuracy: **81.8%**
- Macro F1 Score: **68.5%** 

---

### Topic Modeling

Applied **Latent Dirichlet Allocation (LDA)** to identify major customer complaint themes.

The analysis identified **six major complaint categories**, including:

- Product Quality
- Hair & Personal Care
- Purchase Regret
- Customer Service
- Product Functionality
- Device Failures 

---

### Recommendation System

Implemented a collaborative filtering recommendation system using **Singular Value Decomposition (SVD).**

Model Performance

- RMSE: **1.413**
- MAE: **1.154**
- Stable performance across 5-fold cross-validation 

---

### Survival Analysis

Used:

- Kaplan-Meier Survival Analysis
- Cox Proportional Hazards Model

Key findings:

- 93.2% of customers churned after their first review.
- Median customer survival: 284 days.
- Customer engagement was the strongest predictor of retention. 

---

# Key Results

✔ Logistic Regression achieved **81.8% accuracy** for sentiment classification.

✔ Identified **6 customer complaint themes** using LDA.

✔ Developed an SVD recommendation engine for personalized recommendations.

✔ Found that **93.2% of customers never returned after their first review**, highlighting the importance of early customer engagement.

✔ Built an integrated analytics pipeline combining NLP, recommendation systems, and survival analysis. 

---

# Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Respond to negative customer reviews within 24 hours.
- Improve product quality using complaint trend analysis.
- Deploy automated sentiment monitoring.
- Implement personalized recommendation systems.
- Develop customer retention strategies targeting high-risk customers. 

---

# Repository Structure

```text
Amazon-Customer-Review-Analytics
│
├── notebooks/
│   └── Amazon_Customer_Review_Analytics.ipynb
│
├── presentation/
│   └── Amazon_Customer_Review_Analytics_Presentation.pptx
│
├── report/
│   └── Final_Project_Report.pdf
│
├── images/
│   ├── sentiment_classification.png
│   ├── topic_modeling.png
│   ├── recommendation_system.png
│   ├── survival_analysis.png
│   └── analytics_pipeline.png
│
└── README.md
```

---

# Skills Demonstrated

- Python Programming
- SQL
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Machine Learning
- Natural Language Processing (NLP)
- Sentiment Analysis
- Recommendation Systems
- Survival Analysis
- Data Visualization
- Business Intelligence
- Business Analytics

---

# Future Improvements

- Deploy the models as a web application.
- Develop an interactive Power BI dashboard.
- Improve sentiment classification using transformer-based NLP models.
- Build a hybrid recommendation system.
- Implement real-time streaming analytics.

---

# Acknowledgement

This project was completed as part of the **Master of Data Analytics** program at the **University of Niagara Falls Canada**. It showcases advanced analytics techniques for solving real-world business challenges using large-scale customer review data.
