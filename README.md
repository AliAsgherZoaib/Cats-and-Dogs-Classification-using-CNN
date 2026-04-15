# 🐱🐶 Cats vs Dogs Image Classification using CNN (PyTorch)

This project implements a Convolutional Neural Network (CNN) from scratch using PyTorch to classify images of cats and dogs. The goal is to demonstrate a complete deep learning pipeline, including data preprocessing, model building, training, evaluation, and performance analysis without using transfer learning.

---

## 📌 Project Overview

Image classification is a core task in computer vision. In this project, a custom CNN model is trained to distinguish between two classes:

- Cats 🐱  
- Dogs 🐶  

The dataset contains:
- 8000 training images  
- 2000 validation/test images  

Images vary in pose, background, lighting, and orientation, making the task realistic and challenging.

---

## 🧠 Model Architecture

A custom CNN is designed with the following components:

- Multiple Convolutional layers for feature extraction  
- Batch Normalization for stable training  
- ReLU activation for non-linearity  
- MaxPooling for downsampling  
- Adaptive Average Pooling  
- Fully Connected layers for classification  
- Dropout for regularization  

---

## ⚙️ Training Strategy

- Loss Function: CrossEntropyLoss  
- Optimizer: Adam  
- Learning Rate: 0.0005  
- Weight Decay: 5e-4  
- LR Scheduler: StepLR  
- Batch Size: 128  
- Epochs: Up to 30 (with early stopping)

Regularization techniques such as dropout, weight decay, and data augmentation were used to reduce overfitting.

---

## 📊 Results

- Best Validation Accuracy: **~89.5%**
- Training Accuracy: **~97%**
- Best Model Selected using lowest validation loss (epoch 18)

The model shows strong performance with mild overfitting, which is controlled using early stopping and regularization techniques.

---

## 📈 Key Observations

- Training accuracy increases steadily over epochs  
- Validation accuracy peaks around epoch 18  
- After that, overfitting starts to appear  
- Early stopping helps preserve the best-performing model  

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- Torchvision  
- Matplotlib  
- NumPy  

---

## 🚀 Future Improvements

- Apply transfer learning (ResNet, VGG) for higher accuracy  
- Experiment with deeper CNN architectures  
- Use advanced augmentation techniques  
- Hyperparameter tuning for further optimization  

---


---

## 📌 Credits

Developed by [Ali Asghar Darwala](https://github.com/AliAsgherZoaib)

---

## ⭐ If you like this project

Feel free to star the repository and explore improvements!

## 📄 License

This project is open-source and free to use for educational purposes.
