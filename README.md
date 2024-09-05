# Data Mining Project: Sales Data Analysis

This repository contains the implementation of various machine learning tasks on a sales dataset. The dataset includes several features related to sales transactions, such as Order ID, Amount, Profit, Quantity, Category, Sub-Category, and PaymentMode.   

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Tasks and Methods](#tasks-and-methods)
    - [Regression](#regression)
    - [Classification](#classification)
    - [Clustering](#clustering)
    - [Anomaly Detection](#anomaly-detection)
    - [Recommendation System](#recommendation-system)
- [Data Preprocessing](#data-preprocessing)
- [Results and Evaluation](#results-and-evaluation)
- [Folder Structure](#folder-structure)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contact](#contact)

## Project Description
This project involves analyzing a sales dataset to extract meaningful insights and apply various machine learning algorithms for different tasks. The goal is to understand patterns in sales transactions, predict key metrics, classify orders, detect anomalies, and provide recommendations.

## Dataset
**Dataset Name:** Sales data.csv

**Columns:**
- **Order ID:** Unique identifier for each order.
- **Amount:** Total amount of the order.
- **Profit:** Profit gained from the order.
- **Quantity:** Number of items in the order.
- **Category:** Category of the products in the order.
- **Sub-Category:** Sub-category of the products.
- **PaymentMode:** Mode of payment used for the order.

## Tasks and Methods

### Regression
To predict the Profit or Amount based on other features, we implemented various regression algorithms, including:
- Linear Regression
- Decision Trees

### Classification
To classify orders based on features like Category, Sub-Category, or PaymentMode, we applied several classification algorithms, such as:
- Support Vector Machines (SVM)

### Clustering
We used clustering techniques to group orders into clusters based on their features. The methods used include:
- K-Means Clustering

### Anomaly Detection
For detecting unusual or potentially fraudulent orders, we applied anomaly detection techniques, including:
- Isolation Forests
- One-Class SVM

### Recommendation System
Based on customer preferences and past orders, a recommendation system was developed using collaborative filtering and content-based filtering techniques.

## Data Preprocessing
Before applying the machine learning algorithms, the following preprocessing steps were undertaken:
- **Handling Missing Values:** Imputed or removed missing data.
- **Feature Scaling:** Normalized numerical features to bring them to a common scale.
- **Encoding Categorical Variables:** Transformed categorical variables into numerical format.
- **Data Splitting:** Split the data into training and testing sets.
- **Feature Engineering:** Created new features and transformed existing ones to enhance model performance.

## Results and Evaluation
Each task was evaluated using appropriate metrics and cross-validation techniques to ensure the reliability of the results. Detailed reports and visualizations of the model performances are included in the Sales.ipynb notebook.

## Folder Structure
```
├── Sales.ipynb          # Jupyter notebook with all the code implementations
├── Sales data.csv       # Dataset file
└── Plots/               # Directory containing all generated plots
```

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/ImaadHajwane/Data_Mining_Sales_Data_Project.git
```

2. Navigate to the project directory:
```bash
cd Data_Mining_Sales_Data_Project
```

3. Open the Jupyter notebook:
```bash
jupyter notebook Sales.ipynb
```

4. Run the cells in the notebook to execute the code.

## Dependencies
Make sure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

You can install the required packages using the following command:
```bash
pip install -r requirements.txt
```

## Contact
For any questions or feedback, please contact LinkeIn: Imaad Hajwane, www.linkedin.com/in/imaad-hajwane-i280703h
