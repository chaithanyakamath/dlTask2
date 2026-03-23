# Deep Learning Assignment

## 📌 Overview

This repository contains the implementation of key deep learning models including CNN, RNN, and GAN. The project demonstrates applications across image classification, sequence learning, and generative modeling using PyTorch.

---

## 📂 Repository Structure

```
CNN.ipynb      # CNN model for image classification (Fashion-MNIST)
RNN.ipynb      # RNN, LSTM, GRU for time-series prediction
GAN.ipynb      # GAN for generating Fashion-MNIST images

```

---

## 🧠 Tasks Implemented

### A) CNN Image Classification

* Custom CNN with Conv + ReLU + Pooling + Dropout
* Transfer Learning using ResNet18
* Evaluation using accuracy and loss curves

### B) RNN for Sequence Learning

* Implemented RNN, LSTM, and GRU
* Dataset: Airline Passenger Time-Series
* Evaluation using RMSE and loss comparison

### C) GAN for Image Generation

* Generator and Discriminator implementation
* Alternating training strategy
* Generated Fashion-MNIST samples

---

## ⚙️ Technologies Used

* Python
* PyTorch
* NumPy
* Matplotlib

---

## 📊 Results Summary

### CNN

* Custom CNN: ~88% accuracy
* ResNet18: ~91% accuracy

### RNN

* RNN RMSE: ~134.67
* LSTM RMSE: ~140.52
* GRU RMSE: ~138.98

### GAN

* Generated images improved over epochs
* Training instability observed (mode collapse)

---

## ⚠️ Limitations

* CPU-based training
* Limited epochs
* GAN instability

---

## 🚀 Future Improvements

* Train using GPU
* Hyperparameter tuning
* Use advanced architectures (cGAN, BiLSTM)

---

## 📜 Conclusion

This project demonstrates the effectiveness of deep learning models across different domains. CNNs performed well for image tasks, RNN-based models handled sequential data, and GANs enabled synthetic data generation despite training challenges.

---

## 🧾 Author

**Chaithanya Kamath**

---

## 📌 Note

Due to computational limitations, models were trained for fewer epochs. Results reflect expected trends under constrained conditions.
