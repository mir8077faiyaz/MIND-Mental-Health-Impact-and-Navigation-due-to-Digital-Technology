📊 CSE445: Machine Learning

July 2023 – November 2023

Replace this image path with your own (e.g., assets/banner.png or a GitHub-hosted image URL).

🧠 Project Overview

Mental health is a growing global concern—approximately 1 in every 8 people worldwide suffer from mental health disorders. With the rapid rise in technology usage, understanding its impact on mental well-being has become increasingly important.

This project explores the relationship between technology usage and mental health using machine learning techniques. The goal is to classify an individual’s mental state based on survey data and provide interpretable explanations for model predictions.

📋 Data Collection

Designed a 38-question survey divided into 5 sections:

Participant demographics

Technology usage patterns

Stress factors

Coping mechanisms

Mental well-being indicators

Collected 624 responses via Google Forms

After data cleaning, 613 valid responses were used for analysis

🤖 Machine Learning Approach

Applied 9 different classifiers to predict mental health states

Classified mental states into three categories

Used:

Feature selection techniques

3 hyperparameter tuning methods to optimize performance

📈 Best Results

Highest Accuracy: 72% (Logistic Regression)

Highest Recall: 67% (Random Forest)

🔍 Model Interpretability

To ensure transparency and trust in predictions, the project employed LIME (Local Interpretable Model-Agnostic Explanations).
This explainable AI framework helped analyze how individual features influenced each prediction, providing deeper insight into the model’s decision-making process.

🛠 Tech Stack

Scikit-learn

Pandas

NumPy

Google Forms (data collection)

📌 Key Takeaways

Technology usage shows a measurable impact on mental health

Logistic Regression performed best overall in accuracy

Explainable AI (LIME) significantly improved model interpretability

Feature selection and tuning played a critical role in performance improvement
