# Water Quality Safety Score Prediction

This machine learning project predicts the safety score (1–10) of water samples using physicochemical parameters.It combines domain knowledge with supervised learning to assess how suitable a water source is for drinking or irrigation.

# Project Summary
We computed a water safety score using a custom function based on environmental thresholds for pH, solids, turbidity, and more. Then, we trained a Random forest regressor to learn and predict this score from the data. The model achieved an R² score of 0.98, indicating strong alignment with expert-defined logic.

# Features Used
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

# ML Model
- Algorithm: Random Forest Regressor
- Metrics: 
  - R² Score: 0.98  
  - MSE: Low (0.029)
