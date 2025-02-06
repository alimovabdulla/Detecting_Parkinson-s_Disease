# Parkinson Disease Classification Model 🧠🩺

This repository contains a machine learning model designed to classify Parkinson's disease using a Random Forest classifier 🌲. The model is built using Python 🐍 and several popular libraries like Scikit-learn, Pandas, and Seaborn 📊. The dataset used is from the Parkinson's Disease dataset available on Kaggle 📥.

## Table of Contents 📋

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [License](#license)

## Project Overview 🚀

The goal of this project is to build a machine learning model that can predict the presence of Parkinson's disease based on various health-related features 🧑‍⚕️. The model uses the Random Forest Classifier 🌳 for classification and evaluates performance based on accuracy, classification report, and confusion matrix.

## Dataset 📚

The dataset used for this project is the Parkinson’s Disease dataset, which contains data on various features such as voice and motor characteristics of individuals 🎤. The target variable is the `status` column, where 0 indicates no Parkinson’s disease and 1 indicates the presence of Parkinson’s disease.

- **Data source**: Kaggle Parkinson’s Disease dataset
- **Link**: [Parkinson's Disease Dataset on Kaggle](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)

## Model Architecture 🔧

The model is built using a **Random Forest Classifier** 🌲 in a **Scikit-learn pipeline** with the following steps:

1. **Data Preprocessing** 🧹: 
   - Text features are transformed into numerical values using the **TF-IDF Vectorizer**.
   - Features are scaled using **StandardScaler** for normalization.

2. **Model Building** 🏗️: 
   - A **Random Forest Classifier** is used for classification. 
   - The model is trained and evaluated on a test set with an 80/20 split.

3. **Evaluation** 📊:
   - Model performance is assessed using accuracy, classification report, and confusion matrix.

## Installation Instructions 💻

### Prerequisites ⚙️

Make sure you have the following installed:

- Python 3.6+
- pip (Python package installer)

### Install Required Libraries 📦

Clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/parkinson-disease-classification.git
cd parkinson-disease-classification
pip install -r requirements.txt

