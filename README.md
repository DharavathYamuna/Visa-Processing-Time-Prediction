# AI Enabled Visa Status Prediction and Processing Time Estimator

![Python](https://img.shields.io/badge/Python-3.12-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview
Visa applicants often face long waiting times and uncertainty regarding the progress of their applications. This project aims to develop a predictive system that estimates visa processing times based on historical data. By analyzing past application records—including applicant country, application type, processing office, and seasonal variations—this system provides data-driven estimates, improving transparency and the applicant experience.

## Project Outcomes
- **Data-Driven Estimates:** Predict approximate processing times for visa applications.
- **Trend Analysis:** Identify seasonal or regional patterns in visa approvals.
- **User-Friendly Tool:** Provide applicants with an easy-to-use web-based estimator.
- **Improved Transparency:** Reduce applicant uncertainty with data-backed predictions.

## Modules
1. **Data Collection & Preprocessing**
   - Gather historical visa data (application dates, decision dates, applicant demographics, processing centers).
   - Clean and preprocess data (handle missing values, normalize formats).
   - Compute target variable: number of days between submission and decision.

2. **Exploratory Data Analysis (EDA)**
   - Visualize processing time distributions across visa types and regions.
   - Identify trends based on seasons, workload at processing centers, and applicant origin.
   - Generate feature importance insights.

3. **Predictive Modeling**
   - Train regression models (Linear Regression, Random Forest, Gradient Boosting).
   - Compare models using evaluation metrics (MAE, RMSE, R² score).
   - Tune hyperparameters for optimal performance.

4. **Processing Time Estimator Engine**
   - Build a prediction engine where users input application details (visa type, country, date, office).
   - Return estimated processing time range (e.g., 30–45 days).
   - Provide confidence intervals for predictions.

5. **Deployment & Web Application**
   - Develop a web app with input forms for applicants.
   - Display predictions, charts, and past processing trends.
   - Enable API endpoints for integration with government or agency platforms.

## Milestones & Timeline
- **Milestone 1 (Weeks 1–2):** Data Collection & Preprocessing  
- **Milestone 2 (Weeks 3–4):** EDA & Feature Engineering  
- **Milestone 3 (Weeks 5–6):** Predictive Modeling  
- **Milestone 4 (Weeks 7–8):** Web App Development & Deployment

## Tools & Technologies
- **Programming Languages:** Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Web Frameworks:** Flask or Streamlit
- **Deployment Platforms:** Heroku, AWS, or Azure

## Dataset
- Historical visa application data (from public sources or synthetic data)

## How to Run
1. Clone the repository:  
   ```bash
   git clone <repo_link>
2.Install dependencies:
    pip install -r requirements.txt
3.Run the web application:
   Streamlit:
   streamlit run app.py
   Flask:
   python app.py
Dharavath Yamuna
Infosys Intern Project

     



