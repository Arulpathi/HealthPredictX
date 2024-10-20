# HealthPredictX

HealthPredictX is a machine learning-based healthcare prediction system that aims to assist in the early detection of major health issues such as diabetes, heart disease, and Parkinson’s disease. The platform integrates predictive analytics to provide healthcare providers with valuable insights and personalized suggestions for patients.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Challenges and Future Work](#challenges-and-future-work)
- [References](#references)

## Introduction
HealthPredictX leverages machine learning models to predict the likelihood of patients having diabetes, heart disease, or Parkinson’s disease. By incorporating these predictions into healthcare systems, it aims to support early diagnosis and timely intervention, improving overall health outcomes.

## Features
- **Diabetes Prediction**: Using Support Vector Classifier (SVC).
- **Heart Disease Prediction**: Using Logistic Regression.
- **Parkinson’s Disease Prediction**: Using Random Forest.
- **Chatbot Integration**: Personalized health suggestions using GPT-2.
- **Streamlit Interface**: User-friendly web interface for easy data input and interaction.

## Technologies Used
- **Python**
- **Streamlit**: For building the frontend interface.
- **Support Vector Classifier (SVC)**: For diabetes prediction.
- **Logistic Regression**: For heart disease prediction.
- **Random Forest**: For Parkinson’s disease prediction.
- **GPT-2**: For chatbot integration.
- **Pandas, Scikit-learn**: For data processing and machine learning models.
- **Matplotlib, Plotly**: For visualizations.

## Installation

To get started with HealthPredictX, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Arulpathi/HealthPredictX.git
2. Navigate to the project directory:
   ```bash
   cd HealthPredictX
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py

2. Enter the required health parameters in the input fields to receive predictions for diabetes, heart disease, and Parkinson’s disease.

3. Interact with the chatbot for personalized suggestions and healthcare insights.

## Model Performance
The following machine learning models were used to make predictions for different diseases, with their corresponding accuracy:

- Diabetes Prediction (SVC): 77% accuracy
- Heart Disease Prediction (Logistic Regression): 82% accuracy
- Parkinson’s Disease Prediction (Random Forest): 95% accuracy

## Challenges and Future Work
Challenges:
- Data Quality: Ensuring the datasets are representative of diverse populations was a challenge.
- Model Interpretability: Balancing model complexity with the need for transparent, interpretable predictions.
- Chatbot Relevance: Improving the quality and relevance of the chatbot’s responses.

Future Work:
- Dataset Expansion: Expand the dataset to improve model training and generalizability.
- Additional Algorithms: Implement and compare additional machine learning algorithms to further enhance predictions.
- Chatbot Enhancement: Improve the chatbot using more advanced NLP techniques to engage users better.

## References
For more details, refer to [Healthcare Predictive Analytics Using Machine Learning and Deep Learning Techniques - A Survey](https://www.researchgate.net/publication/373453491_Healthcare_predictive_analytics_using_machine_learning_and_deep_learning_techniques_a_survey).
For more details, refer to [this survey](https://www.researchgate.net/publication/373453491_Healthcare_predictive_analytics_using_machine_learning_and_deep_learning_techniques_a_survey).
