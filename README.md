# LeNet-5 MNIST App

This repository contains a **simple implementation of the classic LeNet-5 Convolutional Neural Network** for handwritten digit classification using the **MNIST dataset**.  
Additionally, there is a **Streamlit app** that allows you to upload images of digits and get predictions live.

---

## 🧠 About the Project

- **Model:** LeNet-5 CNN  
- **Dataset:** MNIST (70,000 grayscale images of handwritten digits, 28x28)  
- **Input:** Images are resized to 32x32 to match the LeNet-5 input format  
- **Output:** Digit prediction (0-9)

**LeNet-5 Architecture:**

1. C1: Convolutional layer (6 filters, 5x5 kernel, tanh activation)  
2. S2: Average Pooling  
3. C3: Convolutional layer (16 filters, 5x5 kernel, tanh activation)  
4. S4: Average Pooling  
5. C5: Convolutional layer (120 filters, 5x5 kernel, tanh activation)  
6. F6: Fully connected layer (84 neurons, tanh)  
7. Output: Fully connected layer (10 neurons, softmax)

---