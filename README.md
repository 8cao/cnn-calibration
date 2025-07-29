# 📏 Calibration in Convolutional Neural Networks

This project investigates how well CNN-predicted probabilities reflect actual outcomes by analyzing model calibration.

Using the CIFAR-10 dataset (focused on birds vs. cats), it compares **LeNet-5** and **VGG** architectures and applies **temperature scaling** to improve calibration without degrading accuracy.

Inspired by the research paper: _"On Calibration of Modern Neural Networks"_.

---

## 🎯 Project Goals

- Evaluate CNN probability calibration using:
  - Reliability diagrams
  - Expected Calibration Error (ECE)
- Compare performance of LeNet-5 and VGG on a binary classification task
- Apply temperature scaling to improve calibration

---

## 🧰 Tools & Technologies

- Python
- PyTorch
- NumPy
- Matplotlib
- torchvision

---

## Key Features

- 📊 Visualization of reliability diagrams before and after calibration
- 📉 ECE metrics computed to quantify miscalibration
- 🔥 Implementation of temperature scaling
