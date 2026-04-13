# CNN Lab Assignment

This project implements a complete Convolutional Neural Network (CNN) pipeline using TensorFlow/Keras, covering model building, training, evaluation, and transfer learning on MNIST and CIFAR-10 datasets.

---

## What I Did

- Implemented **LeNet-5** from scratch and trained it on MNIST  
- Designed a **custom CNN** for CIFAR-10  
- Performed experiments with:
  - Different optimizers (SGD, Momentum, Adam)
  - Learning rates and batch sizes
  - Regularization techniques (Dropout, BatchNorm)
- Implemented **learning rate scheduling**
- Visualized:
  - Filters
  - Feature maps
  - Grad-CAM heatmaps
- Evaluated model using:
  - Confusion matrix
  - Classification report
- Applied **transfer learning (VGG16)**:
  - Frozen feature extractor
  - Fine-tuning with gradual unfreezing

---

## Results

| Model | Accuracy |
|------|---------|
| LeNet-5 (MNIST) | ~97.5% |
| Custom CNN (CIFAR-10) | ~67–68% |
| Frozen VGG16 | ~74% |
| Fine-tuned VGG16 | ~84% |

---

## Key Takeaway

Transfer learning significantly improved performance compared to training from scratch, with fine-tuning giving the best results.

---

## Framework

TensorFlow / Keras
