# AI-Driven-Insights-into-Women-Hormonal-Health
A Web-Based Analysis of Women Hormonal Health Challenges using Data Mining and NLP Techniques

Developed an NLP and ML-based framework to analyze Reddit discussions on hormonal health, applying sentiment analysis, LLMs, and recommendation systems for evidence-based insights.

Project Overview

This project leverages web mining, Natural Language Processing (NLP), and Machine Learning (ML) to explore emotional and psychological experiences shared by women coping with Polycystic Ovary Syndrome (PCOS) and thyroid disorders. By extracting and analyzing real-world data from platforms like Reddit and medical websites, the project uncovers sentiment patterns, emotion trends, and offers evidence-based support recommendations.

Problem Statement

Millions of women globally are affected by hormonal conditions such as PCOS and thyroid imbalances, which impact both their physical and emotional well-being. While traditional medical support addresses physiological symptoms, emotional struggles often remain underrepresented. This project addresses this gap by using AI to understand and support the mental health challenges tied to these conditions.

Objectives

-> Extract user-generated content related to PCOS and thyroid disorders from Reddit.

-> Scrape professional health websites for medically reviewed remedies.

-> Perform sentiment and emotion analysis using VADER and DistilRoBERTa.

-> Correlate emotional states with evidence-based remedies.

-> Evaluate classification accuracy of ML models like Logistic Regression, SVC, and XGBoost.

Data Sources

Reddit:-

-> Subreddits: r/PCOS, r/thyroidhealth

-> Data: Titles, self-text, comments, upvotes

-> Extraction Tool: PRAW (Python Reddit API Wrapper)

Trusted Medical Websites:-

-> Mayo Clinic, Healthline, WebMD

-> Data: Symptoms, causes, treatments, emotional coping mechanisms

-> Extraction Tool: BeautifulSoup

Methodology

Data Preprocessing

-> Cleaning text: removing punctuation, special characters, URLs

-> Normalization: lowercasing, tokenization

-> Handling missing values

Exploratory Data Analysis (EDA)

-> Summary statistics for upvotes and comments

-> Word frequency and text length distribution

-> Sentiment and emotion trends visualization

-> Outlier detection and text similarity analysis

Sentiment Analysis

-> Tool: VADER (NLTK)

-> Sentiment categories: Positive, Negative, Neutral

-> PCOS: 45% Negative, 40% Positive

-> Thyroid: 50% Negative, 35% Positive

Emotion Detection
Model: DistilRoBERTa (j-hartmann/emotion-english-distilroberta-base)

Emotion labels: Joy, Sadness, Anger, Fear, Disgust, Surprise

Dominant emotions: Sadness and Anger

Remedy Recommendation
Emotion-to-remedy mapping (e.g., sadness → therapy, exercise)

Extracted recommendations from scraped medical sources

Combined emotion detection with context-specific advice

Machine Learning Models
Logistic Regression: Baseline, 85% accuracy

Support Vector Classifier (SVC): Best performance, 86% accuracy

XGBoost: High precision on majority classes, 76% accuracy

Data balancing: SMOTE applied to address class imbalance

Technologies Used
Python

PRAW, BeautifulSoup

NLTK, Hugging Face Transformers

Scikit-learn, XGBoost

Matplotlib, Seaborn

Pandas, NumPy

Key Outcomes
Uncovered prevalent emotions such as sadness and anger in discussions related to PCOS and thyroid conditions.

Mapped emotional states to tailored, medically accurate remedies.

Identified SVC as the most reliable classifier for emotion detection with 86% accuracy.

Developed a holistic analysis pipeline integrating social media content with clinical health advice.

Conclusion
This project presents a novel approach to understanding and supporting women’s hormonal health by combining NLP and ML techniques with real-world and professional data. The insights derived can help healthcare providers and support systems offer more empathetic, personalized care. Future enhancements could include deep learning models, larger datasets, and clinical decision support integration.

Contributors
Gahana Nagaraja

Namratha Nagathihalli Anantha

Vaishnavi Rajendra Dhotargavi
