# Binary Classification with Dense Neural Networks

**Goal:** Build, train, and evaluate a dense neural network for simple tasks such as binary classification.

## Methodology
This project involved designing and optimizing a neural network for binary classification. The workflow included:
1. Data preprocessing (normalization and handling class imbalance using class weights)
2. Model architecture design and experimentation
3. Training and validation
4. Performance evaluation and hyperparameter tuning

## Model Architecture
Multiple configurations were tested, with the most effective model consisting of:
- 4 Dense layers: [64, 32, 16, 1]
- Activation functions: ReLU for hidden layers, Sigmoid for the output
- Regularization techniques: **Batch Normalization** and **Dropout**

This architecture outperformed a simpler 3-layer model, highlighting the importance of carefully choosing the number of layers and neurons.

## Key Techniques
- **Data Preprocessing:** Normalization improved model convergence. Class weights helped address imbalanced classes, significantly boosting classification accuracy.
- **Regularization:** Batch Normalization and Dropout improved model stability and generalization.
- **Hyperparameter Tuning:** Adjusting the learning rate and number of epochs showed measurable effects on performance.

## Results
- The best configuration (4 layers + regularization) achieved a classification accuracy of **~0.78**.
- Visualizations of loss and accuracy over epochs indicated better generalization with the use of regularization techniques.

## Conclusion
Designing an effective neural network is not a one-size-fits-all process. It requires a systematic approach, continuous experimentation, and a solid understanding of both the data and the model's parameters.
