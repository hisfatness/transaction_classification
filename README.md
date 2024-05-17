# Real Time Financial Anomaly Detection
[Googel Cobal File](https://colab.research.google.com/drive/1jtVqiNJ6e0VVu2O0YVhnFuxb25EMIX_A?usp=sharing)


# Financial Anomaly Detection Using Isolation Forest

This codebase is designed for the detection of financial anomalies utilizing the Isolation Forest algorithm. It includes procedures for data ingestion, preprocessing, model training, and evaluation.

## Dataset

The dataset for financial anomalies is contained within 'financial_anomaly_data.csv'. This dataset provides transaction details, including timestamps, amounts, and transaction types.

## Prerequisites

Before running the script, ensure the following libraries are installed:
- pandas
- scikit-learn
- matplotlib
- seaborn

These can be installed using the following command:
```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Workflow

1. **Data Loading:**
   - Import the financial anomaly data using the Pandas library.

2. **Missing Value Handling:**
   - Examine the dataset for any missing values.
   - Fill in missing values using the mean imputation method.

3. **Data Normalization:**
   - If necessary, normalize the data to ensure standardization.

4. **Model Training with Isolation Forest:**
   - Apply the Isolation Forest algorithm to detect anomalies indicative of fraudulent transactions.

5. **Fraud Detection:**
   - Use the model to predict and flag potential fraudulent transactions.
   - For example, extract the hour from timestamps as part of feature engineering.

6. **Anomaly Visualization:**
   - Visualize the anomaly scores and identified fraud cases using scatter plots, histograms, box plots, and violin plots.

7. **Model Evaluation:**
   - Split the dataset into training and testing sets.
   - Train the model on the training set and assess its performance on the test set.

8. **Exploratory Data Analysis:**
   - Create a pair plot to explore the relationships between different variables, including anomaly scores.

## Running the Script

To run the script, clone the repository and execute the Python script, ensuring all required libraries are installed.

The script is designed to be flexible, allowing for customization or extension to suit specific requirements.
