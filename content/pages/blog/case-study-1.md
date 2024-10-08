---
title: 'eCommerce Recommendation System '
slug: case-study-1
date: '2023-10-24'
excerpt: >-
  This project developed a recommendation system for an eCommerce platform using
  a Graph-based approach to recommend products based on user purchases and
  search history. 
featuredImage:
  url: /images/Ecommerce.webp
  altText: eCommerce
  styles:
    self:
      borderRadius: large
  type: ImageBlock
bottomSections: []
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: left
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
type: PostLayout
---
This project uses H2O.ai to build a machine-learning model that helps financial institutions decide who gets a loan. By analyzing applicant information like income and credit score, the model predicts loan eligibility, streamlining the approval process.

#### Objective

The primary goal was to create an efficient and accurate model to predict whether an applicant is eligible for a loan based on their demographic and financial information. This approach reduces the manual effort involved in loan processing and enhances the consistency of approval decisions.

#### Tech Stack

*   Programming Language: Python

*   Libraries: Scikit-learn, H2O, pandas, numpy, Flask, Seaborn, Matplotlib

*   Containerization: Docker

#### Dataset Description

The dataset used for this project is an anonymized, synthetic dataset designed to mirror real-world loan data. It contains over 100,000 records, each with detailed information about the customer's financial history and loan application.

#### Approach:

1.  Exploratory Data Analysis (EDA):

*   Missing data analysis and imputation.

*   Removal of irrelevant features.

*   Visualization of feature distributions.

2\. Data Pre-processing:

*   Handling of outliers.

*   Categorical data encoding using One-Hot and Label Encoding.

3\. Feature Engineering:

*   Creation of non-linear combinations of features.

*   Addition of derived features based on existing data.

*   Applied Standard Scaler to normalize the data.

4\. Modeling:

*   Implemented various machine learning models including Random Forest, Gradient Boosting, XGBoost, and Neural Networks.

*   Models were evaluated using metrics like Precision, Recall, AUC, and F1 Score.

5\. Hyperparameter Tuning:

*   Used GridSearchCV to optimize model performance.

6\. Model Deployment:

*   Deployed the final model using Flask, encapsulated in a Docker container for easy scalability and deployment.

#### Project Takeaways

*   Mastered EDA techniques for complex datasets.

*   Gained expertise in data cleaning, feature engineering, and data standardization.

*   Developed multiple machine learning models and evaluated their performance.

*   Successfully deployed a predictive model using Flask and Docker.

*   Improved understanding of model metrics such as AUCPR, AUC, and F1 Score.

#### Impact

The final model achieved a high accuracy rate, enabling quicker and more consistent loan approval decisions. This solution effectively reduces the risk of loan defaults and helps financial institutions optimize their loan portfolios.

#### Project Repository

Explore the full implementation, including code, data, and detailed analysis, on GitHub.

[View Project on GitHub](https://github.com/Shola-Ayeotan/Loan-Eligbility)
