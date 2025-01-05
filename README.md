# Neural Network vs Machine Learning Model Comparison

This project compares the performance of a Neural Network (Keras TensorFlow) and traditional Machine Learning models (Random Forest, Logistic Regression) using the UCI Adult Income dataset to predict if a person earns over $50K annually.

## Features
1. **Data Preprocessing**: EDA, encoding categorical variables, and normalizing numerical features.
2. **Models**: 
   - Random Forest and Logistic Regression.
   - Neural Network with tunable architecture (hidden layers, activation functions, dropout).
3. **Hyperparameter Tuning**: 
   - Random search for ML models.
   - Keras-Tuner for Neural Network optimization.
4. **Evaluation Metrics**: Accuracy, F1-score, Precision, Recall, AUC-ROC.

## Workflow
1. Data split into training (70%), validation (15%), and test (15%).
2. Build and evaluate ML models as baselines.
3. Design and optimize the Neural Network.
4. Compare results and performance metrics.

