# SoH_estimation_of_Lithium-ion_battery
# Li-ion Battery State of Health (SoH) Prediction

##  Project Overview

This repository contains code for predicting the **State of Health (SoH)** of Li-ion batteries using:

- **Linear Regression** (baseline)
- **Long Short-Term Memory (LSTM)** Recurrent Neural Network (RNN)

The project utilizes the **NASA PCoE Dataset** to analyze degradation trends under different experimental conditions.

---

## Objectives

- Implement and compare SoH prediction using **Linear Regression** and **LSTM**
- Train and evaluate models using both **50%** and **70%** data splits
- Visualize **Actual vs. Predicted SoH** curves
- Calculate **RMSE** and **MAE** for prediction accuracy

---

##  Dataset

**Data Source**: NASA Prognostics Center of Excellence (PCoE)

Battery Samples:

- **Group A (Normal Temp)**: B05, B07, B18  
- **Group B (High Power)**: B33, B34  
- **Group C (Low Temp)**: B46, B47, B48 
