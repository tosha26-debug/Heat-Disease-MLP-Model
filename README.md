# Heat-Disease-MLP-Model
Heart Disease Classification using Multi-Layer Perceptron (MLP)


This project implements a Multi-Layer Perceptron (MLP) neural network to classify heart disease severity based on patient health attributes. The model was trained on the UCI Heart Disease dataset, which includes features such as age, cholesterol, blood pressure, and chest pain type.


The MLP was built from scratch using NumPy, implementing all key components manually — including forward propagation, ReLU and Softmax activations, cross-entropy loss with L2 regularization, and backpropagation for weight updates.


During training, the model achieved:

Training Accuracy: 96%

Validation Accuracy: 51%

Test Accuracy: 56%


Despite strong training performance, the model showed significant overfitting and poor generalization to unseen data, especially for minority classes. Future improvements include applying regularization (dropout, weight decay), class rebalancing techniques (SMOTE, class weights), hyperparameter tuning, and alternative model comparisons (e.g., Random Forest, XGBoost) to enhance predictive reliability.
