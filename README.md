# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used contains anonymized transaction data, and the goal is to build a model that can accurately distinguish between fraudulent and non-fraudulent transactions.

## Dataset
The dataset used for this project can be accessed via Google Drive at the following link:

[Credit Card Fraud Detection Dataset](https://drive.google.com/file/d/1ALtFG1h3A3kfn9yL8PfaBQuLZ6CWPzcl/view?usp=drive_link)

## Project Structure
- **CreditCardFraud_Intern.ipynb**: Jupyter notebook containing data preprocessing, analysis, visualization, and machine learning model training.
- **README.md**: Project documentation.

## Installation
To run this project, you need to have the following dependencies installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn google-colab
```

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SAMI-CODEAI/CreditCardFraudDetection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CreditCardFraudDetection
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook CreditCardFraud_Intern.ipynb
   ```
4. Mount Google Drive in the notebook and load the dataset from the provided link.

## Data Preprocessing
- Handling missing values
- Exploratory data analysis (EDA)
- Feature scaling and engineering

## Model Training
The following models are implemented and evaluated:
- Logistic Regression
- Linear Regression
- Performance evaluation using accuracy, confusion matrix, and classification report

## Results
The model's performance is analyzed by:
- Percentage of fraudulent and non-fraudulent transactions
- Visualization of transaction amounts over time
- Correlation heatmap of dataset features

## Visualization
The project includes the following visualizations:
- Time vs. Amount plot
- Distribution curve of transaction amounts
- Correlation heatmap


