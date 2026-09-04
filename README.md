# EngineFault AI

EngineFault AI is an interactive research prototype on **AI-based parameter quantification and fault detection in internal combustion engines**.

The application demonstrates an end-to-end methodology for analyzing historical engine experiments, estimating simulated engine parameters, detecting abnormal operating conditions, comparing AI models, explaining predictions, and verifying results against known reference values.

> **Important:** This application uses synthetic demonstration data only. It does not contain actual Scania, TRATON, or proprietary engine data and must not be used for real engine diagnostics or safety-critical decisions.

## Key Features

- Interactive engine-health dashboard
- Synthetic engine experiment dataset
- CSV data upload and signal visualization
- Data-quality and descriptive-statistics analysis
- Normal-versus-faulty experiment comparison
- AI-based engine parameter quantification
- Multi-class engine fault detection
- Automatic anomaly-region highlighting
- SHAP-style explainable AI visualizations
- Model development and performance comparison
- Confusion matrix and prediction-versus-reference plots
- Verification against synthetic labels and reference values
- MATLAB-style engineering evaluation
- Complete research-methodology workflow

## Supported Engine Signals

The synthetic experiments include:

- Engine speed
- Engine load
- Torque
- Coolant temperature
- Oil temperature
- Boost pressure
- Fuel pressure
- Air mass flow
- Exhaust temperature
- Injection duration
- Fuel consumption

## Parameter Quantification

The prototype estimates simulated engineering parameters including:

- Injector efficiency
- Combustion efficiency
- Turbocharger efficiency
- Component degradation
- Volumetric efficiency
- Friction loss

Predicted values are compared with deterministic synthetic reference values using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Coefficient of Determination (R²)

## Fault Classes

The fault-detection workflow supports:

- Normal Operation
- Injector Degradation
- Turbocharger Degradation
- Fuel Pressure Fault
- Cooling System Fault
- Sensor Drift
- Air-Flow Anomaly

Each detection displays its probability, severity, affected signals, timestamp, and supporting evidence.

## Model Comparison

The demonstration compares the following model families:

- Random Forest
- XGBoost
- Autoencoder
- LSTM-style model

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1 score
- ROC-AUC
- MAE
- RMSE

All displayed metrics are calculated from fixed synthetic values and deterministic evaluation rules. Numerical results are not generated dynamically by a language model.

## Research Workflow

```text
Historical Experimental Data
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
AI Model Development
        ↓
Parameter Quantification + Fault Detection
        ↓
Explainable AI
        ↓
Verification
        ↓
Engineering Conclusions
