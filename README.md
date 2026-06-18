<div align="center">

# ⚡ PowerPlant Predictor — ANN Regression with PyTorch

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)](https://pytorch.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?style=for-the-badge\&logo=scikit-learn\&logoColor=white)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org)
[![Dataset](https://img.shields.io/badge/Dataset-Power%20Plant-blue?style=for-the-badge)](#)

> An end-to-end Deep Learning regression project that predicts electrical power output of a power plant using environmental conditions. Built with PyTorch and Scikit-Learn.

</div>

---

# 📸 Project Overview

This project demonstrates how to build an Artificial Neural Network (ANN) for a regression task using PyTorch.

The model learns the relationship between environmental factors and electrical energy output, allowing accurate prediction of power generation under different operating conditions.

The project covers the complete machine learning workflow:

* Data preprocessing
* Feature scaling
* Train-test split
* PyTorch tensor conversion
* ANN model creation
* Model training
* Performance evaluation
* Model saving and loading

---

# 🎯 Problem Statement

Power plants generate electricity based on several environmental conditions such as temperature, pressure, humidity, and vacuum.

Accurately predicting power output helps improve operational efficiency and decision-making.

This project uses an Artificial Neural Network (ANN) to estimate electrical energy output from these environmental measurements.

---

# 📊 Dataset Information

The dataset contains operational and environmental measurements collected from a power plant.

## Input Features

| Feature | Description             |
| ------- | ----------------------- |
| AT      | Atmospheric Temperature |
| V       | Exhaust Vacuum          |
| AP      | Ambient Pressure        |
| RH      | Relative Humidity       |

## Target Variable

| Target | Description              |
| ------ | ------------------------ |
| PE     | Electrical Energy Output |

---

# 🚀 Features

* End-to-End Regression Pipeline
* ANN Implementation using PyTorch
* Data Preprocessing using Scikit-Learn
* Feature Scaling using StandardScaler
* Batch Training with DataLoader
* Model Checkpoint Saving
* Mean Squared Error Evaluation
* R² Score Evaluation
* Reusable Trained Model

---

# 🧠 Deep Learning Pipeline

## Data Preprocessing

* Load dataset using Pandas
* Separate features and target variable
* Train-Test Split
* Standardize numerical features
* Convert data into PyTorch tensors

## Model Training

* Create TensorDataset
* Create DataLoader
* Forward Propagation
* Backpropagation
* Weight Optimization using Adam Optimizer

---

# 🏗️ Neural Network Architecture

```text
Input Layer (4 Features)

        ↓

Hidden Layer 1 (6 Neurons + ReLU)

        ↓

Hidden Layer 2 (6 Neurons + ReLU)

        ↓

Output Layer (1 Neuron)
```

---

# ⚙️ Training Configuration

| Parameter     | Value   |
| ------------- | ------- |
| Framework     | PyTorch |
| Optimizer     | Adam    |
| Loss Function | MSELoss |
| Epochs        | 100     |
| Batch Size    | 32      |

---

# 📈 Evaluation Metrics

The model performance is measured using:

## Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

## R² Score

Measures how well the model explains the variance in the target variable.

Higher R² values indicate better predictive performance.

---

# 📂 Project Structure

```text
ANN-Regression-PyTorch/
│
├── ANN_Regression.ipynb      # Complete ANN Regression notebook
├── powerplant_data.csv       # Dataset
├── best_model.pt             # Trained PyTorch model
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```

---

# 🖥️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/harsh-v16/-PowerPlant-Predictor-ANN-Regression-with-PyTorch.git
cd -PowerPlant-Predictor-ANN-Regression-with-PyTorch
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook ANN_Regression.ipynb
```

---

# 📦 Dependencies

```text
# 📦 Dependencies

| Package | Purpose |
|----------|----------|
| PyTorch | Neural Network Development |
| Pandas | Data Analysis |
| NumPy | Numerical Computation |
| Scikit-Learn | Preprocessing & Evaluation |
| Jupyter | Notebook Environment |
```

---

# 🛠️ Tech Stack

| Tool             | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Core Programming Language       |
| PyTorch          | Deep Learning Framework         |
| Pandas           | Data Analysis                   |
| NumPy            | Numerical Computing             |
| Scikit-Learn     | Data Preprocessing & Evaluation |
| Jupyter Notebook | Development Environment         |
| GitHub           | Version Control                 |

---

# 📚 Learning Outcomes

Through this project, I learned:

* Building Neural Networks using PyTorch
* Working with regression problems
* Data preprocessing techniques
* Feature scaling using StandardScaler
* Using DataLoader and TensorDataset
* Saving and loading trained models
* Evaluating regression models using MSE and R² Score

---

# 🔮 Future Improvements

* Hyperparameter Tuning
* Early Stopping
* Cross Validation
* Streamlit Deployment
* MLflow Experiment Tracking
* Advanced ANN Architectures

---

# 👤 Author

<div align="center">

**Harsh Chaudhary**

Computer Engineering Student | Machine Learning & Deep Learning Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-harsh--v16-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/harsh-v16)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harsh%20Chaudhary-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/harsh-chaudhary-6ba5b8395/)

</div>

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
