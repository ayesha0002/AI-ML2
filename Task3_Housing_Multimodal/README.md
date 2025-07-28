Task 3: Multimodal Housing Price Prediction

Objective
Predict housing prices using both **tabular structured data** and **house images** by combining CNN and MLP.

Dataset
- **Tabular Data:** Custom or Kaggle housing dataset
- **Image Data:** House front images (custom or public)

Methodology
1. Preprocess tabular data (normalize, encode)
2. Use a CNN (like ResNet18) to extract features from images
3. Concatenate image and tabular features
4. Train a regression model (fully connected layers)
5. Evaluate performance

Tools & Libraries
- `PyTorch`
- `torchvision`
- `pandas`, `numpy`
- `sklearn`

Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

Output
- Multimodal regression model for price prediction
- Visual analysis of model performance
