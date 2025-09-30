# Machine Failure Prediction System

![Accuracy](https://img.shields.io/badge/Accuracy-93%25-brightgreen)
![Precision](https://img.shields.io/badge/Precision-High-blue)
![Recall](https://img.shields.io/badge/Recall-Effective-orange)
![License](https://img.shields.io/badge/License-MIT-green)

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
git clone https://github.com/AxwinX/machine-failure-prediction.git
cd machine-failure-prediction
```
Install required dependencies:
```bash
pip install -r requirements.txt
```
Run the Jupyter Notebook:
```bash
jupyter notebook Aswin_Pradeep_2024Dec_Batch.ipynb
```

## Result
The model achieves strong performance on the test dataset. Key evaluation metrics include:
- Accuracy: ~93%
- Precision: High precision in predicting machine failures
- Recall: Effectively detects failure cases while minimizing false negatives
- F1-score: Balanced performance across both classes

## License
This project is open-source and available under the MIT License.
