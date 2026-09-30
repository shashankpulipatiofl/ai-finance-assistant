# AI-Powered Virtual Personal Finance Assistant

## Overview
This project is an AI-powered virtual personal finance assistant designed to help users manage their finances efficiently. As outlined in our Software Requirements Specification (SRS), the system analyzes financial transactions to identify spending patterns, generates budgets, provides savings recommendations, and aims to offer insights through an interactive chatbot. 

**Role:** Machine Learning Engineer / Data Scientist  
**Focus:** Developing machine learning models for automatic expense categorization, predictive budgeting, and spending pattern analysis using NLP and classification techniques.

## Project Requirements & Features
Based on the SRS, the core functional capabilities include:
- **Automated Expense Categorization:** Classifying expenses automatically based on transaction descriptions and merchant names using ML classification models.
- **Budgeting & Insights:** Generating monthly budgets based on historical spending data and notifying users of overspending.
- **Savings Recommendations:** Suggesting tailored savings plans and providing "what-if" scenarios for financial projections.
- **Interactive Assistance:** Leveraging Natural Language Processing (NLP) to respond to user queries about their finances.

## Machine Learning Methodology
To fulfill the backend requirements for the finance assistant, various ML algorithms were trained and evaluated on financial transaction data:
- **Data Preprocessing:** Cleaned the dataset, combined text features (`Description` and `Merchant Name`), and utilized **TF-IDF vectorization** to convert textual data into numerical format.
- **Classification Models:** Evaluated multiple algorithms for accurate automated categorization, including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Naive Bayes
- **Predictive Analytics:** Implemented models for forecasting future budgets and uncovering underlying spending patterns.

## Repository Structure

- `notebooks/`: Contains the core Machine Learning pipelines and data analysis.
  - `Expense_classification.ipynb`: Model training and evaluation for the automated expense categorization feature.
  - `Budget_prediction.ipynb`: Predictive modeling for budget generation based on historical data.
  - `Spending_analysis.ipynb`: Data visualization and analysis of historical spending patterns.
- `docs/`: Contains project documentation and media.
  - `Report.docx`: Detailed Model Analysis Report comparing the performance of different ML algorithms.
  - `Screen Recording 2026-03-04 at 9.59.01 PM.mov`: Demonstration of the project in action.

## Getting Started

1. Clone the repository to your local machine.
2. Navigate to the `notebooks/` directory and open the Jupyter Notebooks to explore the ML models, preprocessing steps, and analysis.
3. Ensure you have the required Python libraries installed (e.g., `scikit-learn`, `pandas`, `numpy`, `matplotlib`) to successfully run the TF-IDF vectorization and classification models.
