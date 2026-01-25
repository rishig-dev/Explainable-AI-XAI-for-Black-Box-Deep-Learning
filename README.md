# Explainable AI (XAI) for Black-Box Deep Learning

## Overview
This project demonstrates how black-box deep learning models can be interpreted using Explainable AI (XAI) techniques.  
A neural network is trained on synthetic tabular data and explained using LIME and SHAP.

The project is fully reproducible and does not require any external dataset.

---

## Key Features
- Synthetic data generation (no dataset required)
- Black-box neural network using TensorFlow/Keras
- Local explanations using LIME
- Global and local explanations using SHAP (Unified Explainer)
- Google Colab compatible

---

## Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- SHAP
- LIME
- NumPy, Pandas, Matplotlib

---

## Model Details
- Problem Type: Binary Classification
- Model: Fully Connected Neural Network
- Loss Function: Binary Cross-Entropy
- Optimizer: Adam
- Output: Risk Prediction (Low / High)

---

## Explainability Methods
### LIME
- Explains individual predictions
- Provides human-readable feature importance

### SHAP
- Uses unified `shap.Explainer` API
- Global feature importance (summary plot)
- Local explanation (waterfall plot)

---


---

## How to Run
1. Open the notebook in Google Colab
2. Run all cells from top to bottom
3. No dataset upload is required
4. View LIME and SHAP outputs in the notebook

---

## Dataset
- Type: Synthetic (auto-generated)
- Features:
  - Age
  - Income
  - Loan Amount
  - Credit Score
  - Employment Years
- Target: Risk Classification

---

## Use Cases
- Academic projects (BTech / MTech / MSc)
- Explainable AI demonstrations
- AI transparency and ethics studies
- Machine learning portfolio projects

---

## Author
Galla Rishi  





## Project Structure
