# TBM_Prediction_GCN_LSTM
# Predictive Modeling of TBM Control Parameters Using GCN-LSTM

This project focuses on developing a predictive model for Tunnel Boring Machine (TBM) control parameters using time-series data and a hybrid deep learning architecture.

## Project Overview

- **Objective:** Predict the horizontal deviation angle (HDA) of a Tunnel Boring Machine during excavation, based on real-time machine sensor data.
- **Techniques Used:** 
  - Time-series forecasting
  - Graph Convolutional Networks (GCNs)
  - Long Short-Term Memory (LSTM) networks
  - Causal discovery (PCMCI)
- **Tools:** Python, TensorFlow, Keras, StellarGraph, Scikit-learn, Pandas, Matplotlib

## Methodology

1. **Data Preprocessing:**
   - Combined over 200 TBM ring log files
   - Cleaned and normalized 15 key operational parameters
   - Converted raw data into a supervised learning format

2. **Model Architecture:**
   - Built a GCN-LSTM model using `StellarGraph` and `TensorFlow`
   - Adjacency matrix derived from PCMCI causal inference analysis
   - Model trained to predict next-step TBM HDA

3. **Performance Metrics:**
   - **R² Score:** ~0.92
   - **MAE:** ~0.15
   - **RMSE:** ~0.25

> *Note: Metrics based on scaled inverse predictions over a held-out test set.*

## Results

The model successfully captured both spatial and temporal dependencies in the TBM's control data. It demonstrated high accuracy in predicting directional deviations, aiding in tunnel guidance system precision.

## Code and Data

The full source code and dataset are not publicly included due to confidentiality and project constraints.  
*Please contact me directly if you'd like to learn more.*

## Author

Sasthikapreeya Ponnarasu  
*AI Engineer | Predictive Modeling | Time-Series ML*

---
