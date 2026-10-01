# 🛡️ Palo Alto Networks: Employee Attrition Prediction System

## Project Overview
This repository contains a Machine Learning-Based Employee Attrition Prediction and Risk Scoring System developed for Palo Alto Networks. The project transitions HR analytics from reactive descriptive metrics to proactive predictive intelligence, allowing HR leaders to identify high-risk employees before they resign.

## Features
* **Predictive Modeling:** Utilizes a Random Forest Classifier trained on employee demographics, compensation, and performance data.
* **Risk Scoring:** Assigns every employee a quantitative Attrition Probability (0-100%) and categorizes them into Low, Medium, or High Risk.
* **Interactive Dashboard:** A Streamlit web application providing overall risk distributions, individual employee risk profiles, and departmental aggregations.
* **Model Explainability:** Highlights key drivers of attrition, such as Monthly Income, Age, and engineered metrics like Workload Stress.

## Repository Contents
* `app.py`: The main Streamlit application script containing the data pipeline and UI dashboard.
* `Palo Alto Networks (1).csv`: The dataset used for training and inference.
* `requirements.txt`: The dependency file for Streamlit deployment.

## Live Application
The interactive dashboard is deployed via Streamlit Community Cloud. 
**[Insert Your Streamlit App URL Here]**

## Installation & Local Execution
To run this project locally:
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `streamlit run app.py`
