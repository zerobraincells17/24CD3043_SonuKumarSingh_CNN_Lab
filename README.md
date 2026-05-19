Convolutional Neural Network (CNN)

This project implements a complete Convolutional Neural Network (CNN) pipeline using TensorFlow/Keras, covering model development, training, evaluation, visualization, and transfer learning on the MNIST and CIFAR-10 datasets.

What I Implemented
CNN Architectures
Built and trained LeNet-5 from scratch for handwritten digit classification on MNIST
Designed a custom deep CNN for multi-class image classification on CIFAR-10
Training Experiments

Performed extensive experimentation with:

Optimizers:
SGD
SGD with Momentum
Adam
Hyperparameters:
Learning rates
Batch sizes
Regularization techniques:
Dropout
Batch Normalization
Dynamic learning rate scheduling for improved convergence
Model Visualization & Interpretability

Implemented visualization techniques to better understand CNN behavior:

Convolutional filter visualization
Feature map extraction
Grad-CAM heatmaps for explainable AI and model interpretability
Performance Evaluation

Evaluated model performance using:

Accuracy and loss curves
Confusion matrix
Classification report
Precision, Recall, and F1-score analysis
Transfer Learning

Applied transfer learning using VGG16:

Used VGG16 as a frozen feature extractor
Performed gradual layer unfreezing for fine-tuning
Compared pretrained performance against training from scratch
Results
Model	Dataset	Accuracy
LeNet-5	MNIST	~97.5%
Custom CNN	CIFAR-10	~67–68%
VGG16 (Frozen)	CIFAR-10	~74%
VGG16 (Fine-Tuned)	CIFAR-10	~84%
Key Insights
Transfer learning substantially improved classification accuracy compared to training a CNN from scratch.
Fine-tuning pretrained layers enabled better feature adaptation to CIFAR-10.
Batch Normalization and Dropout improved generalization and reduced overfitting.
Grad-CAM visualizations helped interpret model predictions and identify attention regions.
Technologies & Frameworks
Python
TensorFlow
Keras
NumPy
Matplotlib
Scikit-learn
OpenCV
Applications

This project demonstrates practical deep learning techniques applicable to:

Image classification
Computer vision systems
Medical image analysis
Object recognition
Explainable AI (XAI)
