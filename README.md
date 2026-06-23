# e-lightgbm-iot-routing

# E-LightGBM: Engineered LightGBM with SHAP-based Feature Pruning for Energy-Efficient IoT Routing

## Overview
This repository contains the code for the research proposal:
"An Engineered LightGBM-SHAP Model with Feature Pruning for Energy-Efficient Routing in IoT Sensor Networks"

## Requirements
- Python 3.10+
- lightgbm==4.1.0
- scikit-learn==1.3.0
- shap==0.42.0
- pandas==2.1.0
- numpy==1.24.0
- matplotlib==3.7.0
- seaborn==0.12.0
- jupyter==1.0.0

## Dataset
WSN-DS (Wireless Sensor Network Dataset) - IEEE DataPort
https://ieee-dataport.org/open-access/wsn-ds

## Repository Structure
├── baseline/          # Vanilla LightGBM (locked baseline)
├── engineered/        # E-LightGBM with SHAP feature pruning
├── data/              # WSN-DS dataset
├── results/           # Evaluation metrics and visualisations
└── requirements.txt   # Python dependencies

## Author
Mohammed Rayan Suhuyini - msuhuyini1234@gmail.com
Department of Computer Science, KNUST
