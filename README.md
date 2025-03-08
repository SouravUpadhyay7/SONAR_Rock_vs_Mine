# SONAR Rock vs Mine Classification

![Sonar Classification](https://via.placeholder.com/800x400?text=SONAR+Rock+vs+Mine)  

This repository contains a machine learning model to classify objects as either **rock** or **mine** using the SONAR dataset. The dataset consists of sonar signals bounced off objects in the water, and the model predicts whether the object is a rock or a mine based on these signals.

## Dataset

The dataset used is the **SONAR dataset**, which contains **208 samples** with **60 numerical features** representing sonar signal attributes.

- **Label 'R'**: Rock  
- **Label 'M'**: Mine  

## Project Overview

The notebook **[Sonar_Rock_vs_Mine.ipynb](https://github.com/SouravUpadhyay7/SONAR_Rock_vs_Mine/blob/main/Sonar_Rock_vs_Mine.ipynb)** contains the following steps:

1. **Data Loading**: Load and explore the dataset.  
2. **Data Preprocessing**: Handle missing values, scale features, and split the dataset.  
3. **Model Training**: Train machine learning models for classification.  
4. **Model Evaluation**: Assess model performance using accuracy, precision, recall, and confusion matrix.  
5. **Predictions**: Test the model on new data samples.  

## Dependencies

To run this project, install the required libraries:

