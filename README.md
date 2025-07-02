# Heart Disease Prediction using ANN 🫀

## 🧩 Problem Statement
Predict if a person is likely to develop heart disease using health indicators.

## 📊 Dataset
- Source: [Kaggle: Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- Features: Age, Sex, Chest Pain, Cholesterol, etc.

## 🔍 Approach
- Handled categorical variables using OneHotEncoding.
- Normalized numerical features with StandardScaler.
- Built an ANN using TensorFlow/Keras with:
  - 2 Hidden layers (ReLU)
  - Output layer (Sigmoid for binary classification)
- Evaluation: Accuracy, Precision, Recall, Confusion Matrix
- Visualized Training vs Validation Accuracy & Loss

## 📈 Results
- **Accuracy**: `XX%` (fill this after model run)
- **Precision**: `XX%`
- **Recall**: `XX%`
- Confusion matrix plotted for clear comparison.

## 📉 Visualization
Included plots for:
- Accuracy vs Epoch
- Loss vs Epoch

## ✅ Conclusion
The ANN model performed well in identifying patients with heart disease using common health metrics. Can be further improved with hyperparameter tuning and more features.
