# Telco-Customer-Churn-Prediction-Analysis
Predictive analysis of Telco customer churn using Python and Plotly Express. Identifies key risk factors (contracts, service bundles, high charges) and presents actionable business recommendations for retention in a dedicated PPT.

# Telco Customer Churn Prediction and Strategic Analysis

## 🎯 Project Goal

The primary objective of this project is to perform a comprehensive **Exploratory Data Analysis (EDA)** on Telco customer data to identify the most significant factors that lead to **customer churn**. The goal is to translate these data-driven insights into **actionable business strategies** to improve customer retention.

## 🌟 Key Insights

The analysis, performed using Python and **Plotly Express** (for interactive visualizations), revealed several key drivers of churn:

1.  **Contract Type is Crucial:** Customers on **month-to-month contracts** have the highest churn rates, indicating a lack of commitment and loyalty.
2.  **High-Charge, Low-Tenure Risk:** New customers with **high monthly charges** are the most likely to churn early.
3.  **Service Bundles Promote Loyalty:** Customers who subscribe to **Internet, Phone, and TV bundles** are significantly more likely to stay than those with only internet service.

## 📂 Project Files

| File | Description |
| :--- | :--- |
| `Churn_Prediction.ipynb` | The complete analysis notebook. Contains the full workflow: data cleaning, EDA, visualization (using Plotly Express), feature engineering, and interim findings. |
| `Telco-Customer-Churn.pptx` | The **Executive Summary** presentation. This deck translates the technical findings from the notebook into clear, concise, and actionable recommendations for business stakeholders. |
| `requirements.txt` | (Recommended) Lists all necessary Python libraries for replicating the environment. |

## 🚀 How to Run the Analysis

To run this project locally, you will need a Python environment with Jupyter Notebook installed.

### 1. Set up the Environment

You can install all the necessary libraries using the `requirements.txt` file (if created):

```bash
pip install -r requirements.txt
