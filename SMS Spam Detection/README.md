# SMS Spam Detection

## Overview

This repository contains code for a SMS spam detection project using machine learning. The goal is to classify SMS messages as spam or ham (non-spam) based on their content. The project involves data preprocessing, feature engineering using TF-IDF vectorization, and training a Multinomial Naive Bayes classifier.

## Dataset

The dataset used in this project is sourced from Kaggle and is named `spam.csv`. It includes a collection of SMS messages labeled as spam or ham. Each message is associated with a label indicating its category. The dataset is split into training and testing sets for model development and evaluation.

## Project Structure

- **1. Data Preprocessing:** Map labels to numeric values (0 for ham, 1 for spam).

- **2. Splitting the Dataset:** Split the dataset into training and testing sets.

- **3. Feature Engineering:** Use TF-IDF vectorization to convert text messages into numerical features.

- **4. Model Training:** Train a Multinomial Naive Bayes classifier.

- **5. Model Evaluation:** Evaluate the model's performance using accuracy, precision, recall, and F1 score.



Happy coding!
