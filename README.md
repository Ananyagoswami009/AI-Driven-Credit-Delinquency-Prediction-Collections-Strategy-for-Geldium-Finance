# AI-Driven Credit Delinquency Prediction & Collections Strategy for Geldium Finance

## Project Overview

This project focuses on leveraging **AI-driven analytics** to predict **credit card delinquency** and create a **data-driven collections strategy** for **Geldium Finance**. The core objective is to develop **predictive models** that forecast the likelihood of customer delinquency and translate these insights into actionable **intervention strategies** that optimize collections and reduce delinquency rates.

### Role of the AI Transformation Consultant

As an **AI Transformation Consultant at Tata iQ**, my responsibility is to guide **Geldium Finance** in adopting **AI-powered solutions** that improve decision-making processes in their **collections strategies**. My role involves analyzing **customer data**, developing **AI/ML models**, and providing actionable insights for **targeted interventions** to reduce the **delinquency rate**.

Through this project, we will focus on ensuring that **AI adoption** is ethical, **explainable**, and **aligned** with business objectives, and that the final solution enhances **financial risk management** and **customer engagement**.

---

## Project Structure

The repository contains the essential components of the project, with a clear structure that follows the process from **data analysis** to **model development** and finally to **actionable recommendations** for improving collections strategies. Below is an overview of the folder structure and its contents:

/Delinquency_prediction_dataset # Contains the dataset used for training models
/EDA_Summary_Report_Geldium # Exploratory Data Analysis (EDA) Summary Report
/Model_Plan_for_Credit_Delinquency_Risk_Assessment # Plan for predictive model development
/Predictive_Insights_for_Collections_Strategy # Insights and recommendations for collections strategy
/Presentation # PowerPoint presentation of AI-powered collections system
README.md # This file


---

### Detailed Description of Each Folder:

#### 1. **Delinquency_prediction_dataset**
- **Description**: The dataset provided by Geldium that contains **customer information** essential for predicting credit delinquency.
- **Columns**:
  - **Customer ID**: Unique identifier for each customer.
  - **Credit Utilization**: Percentage of available credit used by the customer.
  - **Missed Payments**: Number of missed payments over the past 6 months.
  - **Income**: Annual income of the customer.
  - **Debt-to-Income Ratio (DTI)**: Ratio of monthly debt payments to monthly income.
  - **Account Tenure**: Duration of the customer’s account with the company.
  - **Delinquent Account**: Target variable where 1 represents a delinquent account and 0 represents a non-delinquent account.

#### 2. **EDA_Summary_Report_Geldium**
- **Description**: This file documents the **Exploratory Data Analysis (EDA)** phase, where we assess the structure and quality of the dataset, identify key risk factors, and highlight potential gaps or inconsistencies.
- **Key Elements**:
  - **Missing Data**: Identifies missing or inconsistent data and recommends approaches for handling them.
  - **Key Risk Indicators**: Highlights customer segments or features (e.g., **credit utilization**, **missed payments**) strongly associated with delinquency risk.
  - **Anomalies and Insights**: Insights from initial data patterns and anomalies that need further investigation.

#### 3. **Model_Plan_for_Credit_Delinquency_Risk_Assessment**
- **Description**: This document outlines the **predictive modeling approach** for identifying customers at risk of delinquency. The goal is to predict delinquency likelihood based on key customer features.
- **Chosen Model**: **Logistic Regression** was selected as the model for its simplicity, interpretability, and ability to provide clear insights into the contribution of each variable to the final prediction.
- **Evaluation Metrics**:
  - **Accuracy**: Measures the overall correctness of the model.
  - **Precision**: Focuses on the proportion of true positives.
  - **Recall**: Measures the ability of the model to identify delinquent customers.
  - **F1-Score**: Harmonic mean of precision and recall.
  - **AUC-ROC**: Evaluates the model’s ability to distinguish between delinquent and non-delinquent customers across various thresholds.

#### 4. **Predictive_Insights_for_Collections_Strategy**
- **Description**: This report documents the insights and recommendations derived from the predictive model. It includes suggested strategies for **targeting high-risk customer segments** to optimize collections efforts.
- **Key Insights**:
  - **High Credit Utilization**: Customers with credit utilization over 50% show a higher risk of delinquency.
  - **Missed Payments in Young Customers**: Customers under 30 years old who have missed 2 or more payments are significantly more likely to become delinquent.
  - **High Debt-to-Income Ratio (DTI)**: A DTI ratio greater than 0.5 is a strong indicator of potential default.
- **Recommendation Framework**:
  - Proactive outreach for **young customers** with **missed payments** (using SMS, emails, or personalized financial counseling).
  - Offering **debt restructuring** for customers with **high DTI**.

#### 5. **Presentation**
- **Description**: A PowerPoint presentation designed for **Geldium’s stakeholders**. It outlines the **AI-powered collections strategy**, showcasing how the AI model can be integrated into **collections processes** and scaled for real-time interventions.
- **Key Points**:
  - **System Workflow**: From **customer data ingestion** to **decision-making**, to **action** and **learning**.
  - **Role of Agentic AI**: Explanation of which parts of the process are **autonomous** (e.g., triggering reminders) versus those requiring **human oversight** (e.g., complex cases).
  - **Responsible AI Guardrails**: Ensuring **fairness**, **transparency**, and **compliance** with financial regulations.
  - **Expected Business Impact**: **Reduction in delinquency**, improved **operational efficiency**, and enhanced **customer experience**.

---
