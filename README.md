# 🐜 Ant Colony Algorithm-Based Neural Network Weights Optimization for Financial Risk Prediction

This project implements a hybrid approach that combines the Ant Colony Optimization (ACO) algorithm with Artificial Neural Networks (ANN) to improve financial risk prediction. The ACO is used to optimize the initial weights of the neural network to enhance prediction accuracy and convergence.

Libraries Used:

numpy

pandas

matplotlib

scikit-learn

## 📈 Objective

To optimize the performance of a neural network model in financial risk prediction tasks by using Ant Colony Optimization for weight initialization instead of random initialization.

---

## 🧠 Key Concepts

- **Ant Colony Optimization (ACO)**: A nature-inspired optimization algorithm based on the behavior of ants searching for food.
- **Artificial Neural Network (ANN)**: A multi-layer neural model used to predict financial risks based on features.
- **Hybrid Optimization**: ACO is used to generate optimal weights for the ANN before training, aiming to improve convergence and accuracy.

---

## 📁 Project Structure

📦ACO_ANN_Financial_Risk_Prediction

┣ 📜Ant Colony Algorithm-Based Neural Network Weights Optimization for Financial Risk Prediction.ipynb

┗ 📜README.md



📊 Dataset
You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/mloey1/ahcd1](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset/data).



⚙️ Methodology
Preprocessing: Load and normalize the dataset.

ACO Initialization:

Generate solutions (weights) using artificial ants.

Update pheromones based on fitness (error).

ANN Training:

Use ACO-optimized weights to initialize the ANN.

Train using traditional backpropagation.

Evaluation:

Accuracy

Loss curves

Confusion matrix


📈 Results

The ACO-initialized ANN model shows improved convergence speed and better generalization on the test set compared to randomly initialized models.


