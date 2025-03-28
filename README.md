﻿# ctCeSj7pq6D28iNU

# Predictive Customer Satisfaction Analysis

This repository contains a machine learning pipeline aimed at solving a real-world industry problem: predicting customer dissatisfaction in a logistics and delivery business. The goal is to enable the company to proactively improve services based on actionable insights derived from customer feedback.

## Project Background

**From Data Exploration to Predictive Insights:**

In the fast-paced logistics industry, ensuring customer satisfaction is crucial. I worked with a client to uncover that 45.24% of their customers were dissatisfied, a significant issue that could affect business growth. This analysis was part of my experience with the Apziva AI Residency program, where the original goal was to predict happy customers. However, realizing that almost half of the customer base was unhappy, we shifted our focus to predicting dissatisfied customers, allowing the client to make targeted improvements.

### Problem Context

The client is a global logistics startup that partners with multiple vendors to deliver services. They conducted a customer satisfaction survey covering key aspects of the delivery process:

- **X1:** Timely delivery
- **X2:** Accuracy of order contents
- **X3:** Completeness of order
- **X4:** Value for money
- **X5:** Courier satisfaction
- **X6:** Ease of use of the app

The company’s goal was to predict customer dissatisfaction (class 0) to focus on service improvements and better understand where their processes needed attention. This shift helped the company address customer needs in real-time and prevent further dissatisfaction, contributing to increased loyalty and retention.

## Project Overview

1. **Exploratory Data Analysis** (`exploratory_analysis.ipynb`):
   - Cleaned, preprocessed the dataset, and visualized the relationships between survey responses.
   - Identified key factors leading to dissatisfaction and analyzed trends using univariate and bivariate analysis.

2. **Model Training** (`prediction_model_training.ipynb`):
   - Built a machine learning model using Random Forest to predict customer dissatisfaction.
   - Hyperparameter tuning and feature engineering helped optimize the model to exceed the accuracy threshold while focusing on predicting unhappy customers.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/osamaizhar/ctCeSj7pq6D28iNU
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks:
   - Start with `exploratory_analysis.ipynb` to clean and explore the data.
   - Proceed to `prediction_model_training.ipynb` to train and optimize the predictive model.

## License
This project is licensed under the MIT License.
