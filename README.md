# From Numbers to Neurons

An end-to-end neural network implementation built completely from scratch using **NumPy** for multi-class Iris species classification. This project demonstrates the complete machine learning pipeline without using high-level deep learning frameworks such as TensorFlow or PyTorch.

---

## Overview

This project implements a feedforward neural network from scratch to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The implementation covers every stage of the learning pipeline, including data preprocessing, forward propagation, backpropagation, gradient descent optimization, and model evaluation.

---

## Features

- End-to-end neural network implementation using only NumPy
- Forward propagation
- Backward propagation (Backpropagation)
- ReLU activation function
- Softmax activation function
- Categorical Cross-Entropy Loss
- Gradient Descent optimization
- One-Hot Encoding
- Min-Max Feature Scaling
- 80:20 Train-Test Split
- Multi-class classification
- Model evaluation using Accuracy, Precision, Recall and F1-score

---

## Dataset

The project uses the famous **Iris Flower Dataset**.

### Dataset Information

- Samples: 150
- Features: 4
- Classes: 3

Features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Classes:

- Setosa
- Versicolor
- Virginica

---

## Project Structure

```
From-Numbers-to-Neurons/
│
├── dataset/
│   └── iris.csv
│
├── models/
│   └── neural_network.pkl
├── assignments/
└── README.md
```

---

## Neural Network Architecture

```
Input Layer (4 neurons)

        ↓

Hidden Layer
128 neurons
ReLU Activation

        ↓

Output Layer
3 neurons
Softmax Activation
```

---

## Machine Learning Pipeline

1. Load Iris dataset
2. Handle preprocessing
3. One-Hot Encode target labels
4. Normalize features using Min-Max Scaling
5. Split dataset (80:20)
6. Initialize weights and biases
7. Forward propagation
8. Compute Categorical Cross-Entropy Loss
9. Backpropagation
10. Update weights using Gradient Descent
11. Repeat until convergence
12. Evaluate performance on test data

---

## Results

| Metric | Score |
|---------|--------|
| Accuracy | **93.33%** |
| Precision (Macro) | **93.50%** |
| Recall (Macro) | **93.33%** |
| F1-Score (Macro) | **93.31%** |

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (only for dataset loading and evaluation)
- Joblib

---

## Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/From-Numbers-to-Neurons.git
```

Move into the project directory.

```bash
cd From-Numbers-to-Neurons
```

Install dependencies.

```bash
pip install -r requirements.txt
```

---

## Running the Project

Train the neural network:

```bash
python src/train.py
```

Predict on test samples:

```bash
python src/predict.py
```

---

## Repository Contents

```
dataset/
```

Contains the Iris dataset used for training.

```
models/
```

Contains the trained neural network model.

```
src/
```

Contains all source code for preprocessing, model training, prediction, evaluation, and utility functions.

```
requirements.txt
```

Lists all required Python packages.

---

## Learning Outcomes

This project demonstrates practical implementation of:

- Neural Networks from Scratch
- Forward Propagation
- Backpropagation
- Gradient Descent Optimization
- Matrix-based Computation using NumPy
- Multi-class Classification
- Data Preprocessing
- Performance Evaluation

---

## Future Improvements

- Add momentum optimizer
- Implement Adam optimizer
- Add Dropout regularization
- Support multiple hidden layers
- Hyperparameter tuning
- Interactive web interface using Streamlit

---

## Author

**Shantanu**

---

## License

This project is intended for educational and academic purposes.
