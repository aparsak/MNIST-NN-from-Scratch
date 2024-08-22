# MNIST Neural Network from Scratch 🧠📈
## Overview
This project demonstrates a neural network with two layers: a hidden layer and an output layer. The network is trained using mini-batch gradient descent on datasets like MNIST. The notebook provides functionality for evaluating model performance, visualizing accuracy throughout the training process, and making predictions on individual samples.

## Features 🌟
- **Data Preprocessing**: Loads and normalizes the dataset.
- **Network Architecture**: Two layers:
  - **Hidden Layer**: ReLU activation.
  - **Output Layer**: Softmax activation.
- **Mini-Batch Gradient Descent**: Efficient training using mini-batches to update parameters.
- **Accuracy Tracking**: Logs and visualizes accuracy over training iterations.
- **Prediction Functions**: Functions to test and visualize individual predictions.

## Performance Metrics 🏆
- Accuracy: 0.9270
- Precision: 0.9276
- Recall: 0.9270
- F1 Score: 0.9269

## How to Use 🚀

1. **Dependencies**: Ensure you have the necessary Python libraries:
   - `numpy`
   - `pandas`
   - `matplotlib`

2. **Dataset**: Place the `train.csv` dataset file in the same directory as the script.

3. **Training**:
   - Train the model using the `mini_batch_gradient_descent` function. The script updates weights and tracks accuracy over multiple iterations.
   - A plot of training accuracy is generated at the end.

4. **Testing**:
   - Use the `test_prediction` function to visualize and compare predictions against labels for specific images.

5. **Evaluation**:
   - The notebook prints the model's accuracy on a development set after training, along with additional metrics like precision, recall, and F1 score.

## Visualization 📊

### Accuracy Plot
This plot shows how accuracy changes over the course of training.

![output](https://github.com/user-attachments/assets/b4067f4b-33bd-40d1-95d2-88ac4246dd6c)

### Confusion Matrix
The following confusion matrix visualizes the model's performance on the development set.

![Confusion Matrix ](https://github.com/user-attachments/assets/3647a78c-7ce5-4140-96d7-174e2afa5741)



## Acknowledgments 🙏

This project was inspired by the tutorial ["Neural Network from Scratch"](https://youtu.be/w8yWXqWQYmU?si=KrLP3YH__NWwqawO). The tutorial provided valuable insights and guidance in building and understanding neural networks from scratch.
