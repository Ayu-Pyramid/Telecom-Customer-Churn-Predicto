This project analyzes telecom customer data to predict churn and automatically generate personalized retention emails for high-risk customers.
🔍 What This Project Does
Loads and explores the Telco Customer Churn dataset
Preprocesses data using encoding and feature alignment
Trains a Logistic Regression model to predict churn
Evaluates performance using accuracy, confusion matrix, and classification report
Identifies key churn-driving features
Uses an AI-powered retention agent to draft personalized customer emails
🧠 Model Overview
Algorithm: Logistic Regression
Training accuracy: ~84.5%
Handles class imbalance and categorical variables
Feature importance highlights international plans, voicemail plans, and state-level effects
🤖 AI Retention Agent
For customers predicted to churn:
Identifies likely churn reasons (high charges or frequent service issues)
Generates short, professional retention emails using OpenAI’s API
Saves generated emails for review or presentation
📁 Files Used
churn-bigml-80.csv – Training dataset
churn-bigml-20.csv – Test dataset
retention_emails.txt – Generated retention emails
🛠 Technologies
Python, Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
OpenAI API
✅ Outcome
This project demonstrates how predictive modeling and generative AI can work together to support data-driven customer retention strategies.
