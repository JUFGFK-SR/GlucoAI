An AI-powered framework integrating glucose prediction and personalized feedback for diabetes management through digital health technologies.

---

## Overview

Effective diabetes management requires personalized strategies that adapt to each individual's glucose patterns, lifestyle, and treatment regimen. Traditional systems often lack integration of diverse patient data and fall short in delivering real-time, actionable guidance.

This project introduces a comprehensive digital health framework consisting of:

- **AGM (Adaptive Glucose Monitoring Model)**: A deep learning-based model that processes continuous glucose monitoring (CGM) data, insulin usage, dietary inputs, and contextual variables to forecast blood glucose trends.
- **DDA (Digital Diabetes Assistant)**: A recommendation engine that generates individualized feedback and behavioral suggestions for diet, physical activity, and insulin adjustment, promoting adherence and optimizing glycemic control.

---

## Key Features

- Deep learning-based glucose prediction
- Multimodal data integration (CGM, insulin, food, activity)
- Real-time recommendations for patient self-management
- Personalized insights and long-term behavior tracking
- Designed for use in mobile health or wearable-integrated platforms

---

## Architecture

### AGM (Adaptive Glucose Monitoring)

- Inputs: CGM readings, insulin doses, dietary records, contextual factors
- Outputs: Real-time glucose level forecasts
- Architecture: LSTM-based deep learning model with temporal attention

### DDA (Digital Diabetes Assistant)

- Rule- and model-driven recommendation system
- Actionable suggestions for meals, activity, and insulin timing
- Behavioral insights for long-term management
- Visual dashboards and feedback modules

---

## Experimental Results

| Metric                         | Baseline Model | AGM + DDA Framework |
|-------------------------------|----------------|----------------------|
| Glucose Prediction Accuracy   | 78.2%          | **91.5%**            |
| Hypoglycemia Detection Rate   | 65.4%          | **88.6%**            |
| Patient Adherence Improvement | +9.3%          | **+27.1%**           |

---

## Repository Structure

