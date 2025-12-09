# Smart Energy Consumption Analysis and Prediction

## Overview
This repository contains the development of **Smart Energy Consumption Analysis and Prediction using Machine Learning with Device-Level Insights**. The project is being built in milestones, with each week focusing on specific tasks, starting with dataset preprocessing.

### Dataset used: 
https://www.kaggle.com/datasets/drmtya/smart-home-energy-consumption-optimization

## Milestone 1 – Data Preprocessing
- Loaded and inspected the dataset.
- Checked for missing values and duplicates.
- Converted `timestamp` to datetime and extracted features like `year`, `month`, and `time`.
- Performed basic checks to ensure data consistency.
- Performed basic exploratory data analysis (EDA).
- Scaled numerical attributes and encoded non-numerical categorical attributes.
- Split the dataset into train and test set (70:30), might split the test set for hypertuning using validation set in later milestones.

### Folder Structure
/smart-home-energy

│

├── data (excluded from repository due to upload size limitation)

│   └──  smart_home_energy.csv

│

├── notebooks

│   └── milestone1.ipynb

│

├── reports

│   └── milestone1

|       └──milestone1.pdf

|       └──figures (plots)

│

├── README.md (This file)

|

└── requirements.txt (version unspecified)


## Tools & Libraries
- Python 3.x
- Pandas
- Matplotlib (for exploratory checks)
- Jupyter Notebook
