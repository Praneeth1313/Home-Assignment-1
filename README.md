# Home-Assignment-1

Name : Thota Praneeth babu

700# : 700777380

CRN : 30671



# TensorFlow Operations, Loss Functions, and TensorBoard Visualization

This project demonstrates fundamental TensorFlow operations, tensor manipulations, various loss functions, and visualization of neural network training using TensorBoard.

---

## Task 1: Tensor Manipulations & Reshaping

### Objective:

Perform basic tensor operations and manipulations using TensorFlow, including reshaping, transposition, and broadcasting.

### Steps:

1.⁠ ⁠*Create a Tensor:* Generate a random tensor with shape ⁠ (4, 6) ⁠.
2.⁠ ⁠*Analyze Tensor:* Determine the rank and shape using TensorFlow utility functions.
3.⁠ ⁠*Reshape & Transpose:*

   * Reshape the tensor to shape ⁠ (2, 3, 4) ⁠.
   * Transpose the reshaped tensor to shape ⁠ (3, 2, 4) ⁠.
4.⁠ ⁠*Broadcasting:*

   * Broadcast a smaller tensor of shape ⁠ (1, 4) ⁠ to match the dimensions of the larger tensor and perform an element-wise addition.
5.⁠ ⁠*Explanation:* Provide an intuitive explanation of broadcasting mechanics in TensorFlow.

### Expected Output:

•⁠  ⁠Printed rank and shape before and after reshaping and transposing.

---

## Task 2: Loss Functions & Hyperparameter Tuning

### Objective:

Implement and compare Mean Squared Error (MSE) and Categorical Cross-Entropy (CCE) loss functions.

### Steps:

1.⁠ ⁠*Define Values:* Set true values (⁠ y_true ⁠) and predicted values (⁠ y_pred ⁠).
2.⁠ ⁠*Compute Losses:* Calculate both MSE and CCE.
3.⁠ ⁠*Analyze Sensitivity:* Slightly modify the predictions to observe changes in loss values.
4.⁠ ⁠*Visualization:* Create a bar chart comparing MSE and Categorical Cross-Entropy losses using Matplotlib.

### Expected Output:

•⁠  ⁠Printed loss values for original and modified predictions.
•⁠  ⁠Visual bar chart comparing MSE and Cross-Entropy loss.

---

## Task 3: Neural Network Training & TensorBoard Logging

### Objective:

Train a simple neural network using the MNIST dataset and visualize its training performance using TensorBoard.

### Steps:

1.⁠ ⁠*Data Preparation:* Load and preprocess the MNIST dataset.
2.⁠ ⁠*Model Training:* Train the neural network for 5 epochs, ensuring TensorBoard logging is enabled.
3.⁠ ⁠*Visualization:* Launch TensorBoard to analyze training and validation metrics, including accuracy and loss.

### Expected Outcome:

•⁠  ⁠Logs generated and stored in the directory: ⁠ logs/fit/ ⁠
•⁠  ⁠TensorBoard visualizations clearly showing accuracy and loss trends over epochs.

---

## Dependencies

•⁠  ⁠TensorFlow
•⁠  ⁠NumPy
•⁠  ⁠Matplotlib

Install required dependencies using:

⁠ bash
pip install tensorflow numpy matplotlib


---

## Notes

•⁠  ⁠Ensure that your Python environment is correctly set up.
•⁠  ⁠Keep logs organized and clearly labeled for better analysis and reproducibility.
