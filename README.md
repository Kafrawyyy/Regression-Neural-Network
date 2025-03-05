
# 🧠 Regression Using a Neural Network

## 📖 About the Project

This project implements a **Feedforward Neural Network (FFNN) from scratch** to predict **cement strength** based on **concrete construction data**. The FFNN consists of:

✅ An **input layer** (4 features: Cement, Water, Superplasticizer, Age)  
✅ **One hidden layer** with a **Sigmoid activation function**  
✅ An **output layer** predicting **Concrete Compressive Strength**  

The network learns to **estimate the relationship** between input variables and the target through **forward propagation** and **backpropagation**.

---

## 📊 Dataset Information

The dataset **"concrete_data.xlsx"** contains **700 records**, each with:
- **Inputs:** Cement, Water, Superplasticizer, Age
- **Output:** Concrete Compressive Strength

### 📝 Example Data
| Cement | Water | Superplasticizer | Age | Strength |
|--------|------|----------------|----|----------|
| 540.0  | 162  | 2.5            | 28 | 79.99    |
| 332.5  | 228  | 0.0            | 270 | 40.27   |
| 198.6  | 192  | 0.0            | 360 | 44.3    |

---

## 🏗️ Features

✅ **Load and preprocess the data** (split into **training (75%)** and **testing (25%)**).  
✅ **Normalize the data** (optional for better results).  
✅ **Implement a custom Neural Network class (`NeuralNetwork`)** with:
   - 🏗️ **Network Architecture Setup** (e.g., number of neurons, activation functions, etc.)
   - 📚 **Training Method** (Forward & Backward Propagation with Gradient Descent)
   - 🎯 **Prediction Method** (for new cement strength estimates)
   - 📉 **Error Calculation** (to evaluate model performance)  
✅ **Object-oriented design**: You may create helper classes such as **Layer, Neuron, etc.**


## 🛠️ Technologies Used
📌 Technology	📋 Description
🐍 Python	Main language
📊 Pandas	Data handling
🔢 NumPy	Matrix operations
📉 Matplotlib	(Optional) Plot training progress
