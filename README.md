# Demand Forecasting using LSTM
## Table of Contents
- Introduction
- Data Source
- Features
- Installation
- Usage
- Project Structure
- Model Training
- Results
### Introduction
This project focuses on predicting the future demand for coffee and spices using historical export data from Tanjung Perak Harbor. The prediction model utilizes Long Short-Term Memory (LSTM).
### Data Source
The data used in this project is sourced from the Import and Export Commodities Data from BPS Website. We use monthly export data for coffee and spices (amount in kg) from Tanjung Perak Harbor, covering the period from 2014 until March 2024.
### Features
- Time series analysis and demand forecasting
- Implementation of LSTM
- Visualization of forecast results
### Installation
To install the necessary dependencies, run:
```python
git clone https://github.com/AMATI-TP-02/demand-forecasting-ml.git
cd demand-forecasting-ml
pip install -r requirements.txt
```
### Usage
To use the demand forecasting model, run:
```python
python C241-TP02 Demand Forecasting using LSTM.ipynb --data_path demand_data.csv
```
### Project Structure
```python
demand-forecasting-ml/
├── Demand_Forecasting_using_LSTM.ipynb
├── README.md
├── demand.h5
├── demand_data.csv
├── demand_tfjs.zip
```
### Model Training
To train the demand forecasting model, run:
```python
python Demand_Forecasting_using_LSTM.ipynb --train --data_path demand_data.csv
```
### Results
The results of the model, including predictions and evaluation metrics, are saved in the following files:
- demand.h5: Contains the trained LSTM model in HDF5 format.
- demand_tfjs.zip: Contains the TensorFlow.js version of the trained model for web deployment.
