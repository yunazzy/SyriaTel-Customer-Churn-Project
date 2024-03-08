# SyriaTel Customer Churn Project

## Overview
This project aims to develop a machine learning model to predict customer churn for SyriaTel, a telecommunications company. By identifying customers at risk of churning, SyriaTel can implement targeted retention strategies to minimize customer loss and improve overall business performance.

## Project Structure
- **Notebooks**: Contains Jupyter notebooks used for data exploration, preprocessing, modeling, and evaluation.
- **Data**: Includes the dataset used for training and testing the predictive model.
- **README.md**: This file, providing an overview of the project and repository structure.

## Dependencies
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The dataset contains information about SyriaTel customers, including account details, call usage patterns, and service plans. It includes the following columns:
- `state`: State abbreviation
- `account length`: Length of the customer's account in months
- `area code`: Area code of the customer's phone number
- `phone number`: Customer's phone number
- `international plan`: Whether the customer has an international plan (yes/no)
- `voice mail plan`: Whether the customer has a voice mail plan (yes/no)
- `number vmail messages`: Number of voice mail messages
- `total day minutes`: Total minutes of day calls
- `total day calls`: Total number of day calls
- `total day charge`: Total charge for day calls
- `total eve minutes`: Total minutes of evening calls
- `total eve calls`: Total number of evening calls
- `total eve charge`: Total charge for evening calls
- `total night minutes`: Total minutes of night calls
- `total night calls`: Total number of night calls
- `total night charge`: Total charge for night calls
- `total intl minutes`: Total minutes of international calls
- `total intl calls`: Total number of international calls
- `total intl charge`: Total charge for international calls
- `customer service calls`: Number of customer service calls
- `churn`: Whether the customer churned (True/False)

## Acknowledgments
The dataset used in this project is sourced from [BigML](https://bigml.com/).

