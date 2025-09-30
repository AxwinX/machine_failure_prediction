# Machine Failure Prediction System

## Overview
This project is a Machine Failure Prediction System that uses machine learning to predict whether a machine will fail based on sensor data. The model analyzes operational parameters such as temperature, pressure, and rotational speed to classify machines into **Failure** or **No Failure** states.

## Dataset
The dataset used in this project contains machine operational data and failure labels.  

- **Dataset Download**: [data.csv](./data.csv) 

## Features Used
The model utilizes the following features from the dataset:
- Temperature readings  
- Pressure levels  
- Rotational speed  
- Torque and other sensor-based parameters  

## Algorithm Used
The classification is performed using machine learning algorithms implemented in **Scikit-Learn**.  
Models tested include:  
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

## Project Files
- `machine_failure_prediction.ipynb` – Jupyter Notebook containing preprocessing, training, and evaluation steps.  
- `data.csv` – Dataset used for model training and testing.  
- `requirements.txt` – List of dependencies required to run the project.  

## Installation and Usage
Clone this repository:
```bash
git clone https://github.com/yourusername/machine-failure-prediction.git
cd machine-failure-prediction

Install required dependencies:
