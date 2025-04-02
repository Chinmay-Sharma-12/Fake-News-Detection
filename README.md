Project Overview
This project predicts whether a person is likely to experience high or low panic attack frequency based on various health factors. The dataset includes features like sleep patterns, cholesterol levels, previous history, and triggers. The model used for classification is Logistic Regression.

Dataset
The dataset is named "IFND__.csv". It contains multiple health-related features and a target column representing Panic Attack Frequency in numerical form. This column is converted into categorical labels (High or Low) based on a threshold.

Project Workflow

1a. Data Loading & Cleaning

  Load the dataset

  Handle missing values

  Remove duplicates

1b. Preprocessing

  Encode categorical variables
  
  Normalize numerical values (if needed)
  
  Convert panic attack frequency into High/Low categories

1c. Exploratory Data Analysis (EDA)

  Generate graphs (histograms, box plots, correlation heatmaps)
  
  Check class distribution

1d. Model Training & Evaluation

  Train a Logistic Regression model
  
  Evaluate performance using accuracy, precision, recall, and F1-score
  
  Visualize confusion matrix and ROC curve

Installation & Usage

2a. Requirements:

  Python 3.x
  
  Pandas
  
  NumPy

  Scikit-learn
  
  Matplotlib
  
  Seaborn
