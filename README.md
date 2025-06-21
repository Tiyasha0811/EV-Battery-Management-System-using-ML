# EV-Battery-Management-System-using-ML
A battery management system for electric vehicles using machine learning and matlab 

# 🔋 Electric Vehicle Battery Management System using Machine Learning

## 🚗 Project Overview

As the global EV ecosystem accelerates, managing battery health becomes paramount. This project introduces an intelligent Battery Management System (BMS) that predicts the **State of Health (SOH)** of lithium-ion batteries using **Long Short-Term Memory (LSTM)** neural networks. With over **95% prediction accuracy**, our model enables proactive battery maintenance, optimized charging, and reliable range estimation — all vital for improving EV longevity and user confidence. Also the automated battery charging and discharging system designed with MATLAB Simulink enables the battery to be disconnected from the operational circuits once the battery surpasses it's safety limits, as predicted by our AI model.

---

## 📌 Features

* ✅ **State of Health Prediction** with LSTM (Test RMSE ≈ 0.009)
* 🔄 **Trained on Real Battery Degradation Data** (Group B & C datasets)
* 📈 **Captures Fluctuations and Trends** over 70+ discharge cycles
* 💡 **Supports EV Applications** with real-time prediction potential
* 🔬 **Comparative Model Evaluation**: Linear Regression, XGBoost, FNNs, and LSTM
* 🧠 **Future-ready**: Real-time deployment, transfer learning, anomaly detection, and more

---

## 🧠 Tech Stack

* **Python**
* **TensorFlow / Keras**
* **Google Colab**
* **Pandas, NumPy, Matplotlib**
* **Jupyter Notebooks**
* **MATLAB (for simulation models)**

---

## 📊 Project Insights

* 🔍 **B48 Cell Analysis** revealed:

  * 3-stage degradation curve: Rapid → Stable → Fluctuating
  * SOH dropped from 75% to \~55% in 70 cycles
  * LSTM closely tracks real-world battery behavior

* ⚙️ **Performance Metrics**:

  * **R² Score**: 0.97
  * **MAE**: 0.008
  * **RMSE**: 1.2% (LSTM)

* 🔄 **Model Comparison**:

| Model                | RMSE      | R²       | Use Case                    |
| -------------------- | --------- | -------- | --------------------------- |
| Linear Regression    | 2.80%     | 0.89     | Baseline estimation         |
| XGBoost              | 1.50%     | 0.94     | Cycle-level predictions     |
| **LSTM (Our Model)** | **1.20%** | **0.97** | Early degradation detection |

---

## 🔭 Future Scope

* 📌 Multi-parameter prediction (SOC, resistance, thermal behavior)
* 🧠 Transfer learning for new chemistries
* ⚙️ Real-time embedded implementation
* ⚡ Anomaly detection & adaptive learning
* 🌍 Environmental adaptation (driving patterns, temperature)
* 🧩 Edge computing architecture for onboard diagnostics


