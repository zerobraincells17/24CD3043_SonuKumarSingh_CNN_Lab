# Convolutional Neural Network (CNN)

A complete CNN pipeline using TensorFlow/Keras for image classification, visualization, evaluation, and transfer learning on MNIST and CIFAR-10 datasets.

---

## 🚀 Features

- Implemented **LeNet-5** from scratch on MNIST
- Built a **custom CNN** for CIFAR-10 classification
- Experimented with:
  - SGD, Momentum, Adam optimizers
  - Different learning rates & batch sizes
  - Dropout & Batch Normalization
- Applied learning rate scheduling
- Visualized:
  - CNN filters
  - Feature maps
  - Grad-CAM heatmaps
- Evaluated models using:
  - Confusion matrix
  - Classification report
  - Precision, Recall, F1-score
- Implemented **Transfer Learning using VGG16**
  - Frozen feature extractor
  - Fine-tuning with gradual unfreezing

---

## 📊 Results

| Model | Dataset | Accuracy |
|---|---|---|
| LeNet-5 | MNIST | ~97.5% |
| Custom CNN | CIFAR-10 | ~67–68% |
| VGG16 (Frozen) | CIFAR-10 | ~74% |
| VGG16 (Fine-tuned) | CIFAR-10 | ~84% |

---

## 🔍 Key Takeaways

- Transfer learning outperformed training from scratch
- Fine-tuning significantly improved accuracy
- BatchNorm & Dropout improved generalization
- Grad-CAM improved model interpretability

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV

---

## 📌 Applications

- Image Classification
- Computer Vision
- Explainable AI (XAI)
- Medical Imaging
- Object Recognition
