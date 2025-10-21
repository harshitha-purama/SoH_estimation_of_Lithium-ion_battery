# SoH_estimation_of_Lithium-ion_battery
# 🔋 Li-ion Battery State of Health (SoH) Prediction

![Project Banner](https://via.placeholder.com/1200x300.png?text=Li-ion+Battery+SoH+Prediction) <!-- Optional banner. Replace URL -->

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

---

## 🚀 Project Overview

This repository contains code for predicting the **State of Health (SoH)** of Li-ion batteries using:

- ✅ **Linear Regression** (baseline)
- ✅ **Long Short-Term Memory (LSTM)** Recurrent Neural Network (RNN)

The project utilizes the **NASA PCoE Dataset** to analyze degradation trends under different experimental conditions.

---

## 🎯 Objectives

- Implement and compare SoH prediction using **Linear Regression** and **LSTM**
- Train and evaluate models using both **50%** and **70%** data splits
- Visualize **Actual vs. Predicted SoH** curves
- Calculate **RMSE** and **MAE** for prediction accuracy

---

## 📁 Dataset

**Data Source**: NASA Prognostics Center of Excellence (PCoE)

Battery Samples:

- **Group A (Normal Temp)**: B05, B07, B18  
- **Group B (High Power)**: B33, B34  
- **Group C (Low Temp)**: B46, B47, B48  

---

### 🧮 SoH Calculation

\[
\text{SoH} = \frac{Q_m}{Q_{nom}}
\]

Where:

- \( Q_m \): Discharge capacity at cycle *m*
- \( Q_{nom} \): Initial capacity (**2 Ah**)

---

## 🛠️ Repository Structure

