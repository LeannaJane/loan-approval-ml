---

## Introduction

A machine learning project that analyses loan applicant data and predicts whether a loan should be approved. This project uses data analysis and machine learning techniques to understand patterns in loan approvals and build predictive models that automate decision-making.

---

## Table of Contents

- Introduction
- Overview
- Project Structure
- Installation and Usage
- Dataset
- Models Used
- Features
---

## Overview

This project focuses on:

- Understanding patterns in loan approval decisions  
- Identifying key factors influencing approvals  
- Building machine learning models for prediction  

---

## Project Structure

- Loan.ipynb # Main notebook                 
- decision_tree_model.pkl # Trained Decision Tree model (not included in Git)
- random_forest_model.pkl # Trained Random Forest model (not included in Git)
- requirements.txt # Project dependencies
- README.md # Project documentation
- venv/ # Virtual environment (not included in Git)

## Installation and Usage

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
Then open: 
Loan.ipynb

## Dataset

The dataset used in this project was sourced from Kaggle using the `kagglehub` library:

```python
import kagglehub

path = kagglehub.dataset_download("abhishekmishra08/loan-approval-datasets")
print("Path to dataset files:", path)

```

## Models used

- Decision Tree Classifier
- Random Forest Classifier

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Model training and Evaluation
- Model saving for reuse



