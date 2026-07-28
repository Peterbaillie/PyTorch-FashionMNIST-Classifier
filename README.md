# PyTorch FashionMNIST Classifier

A beginner-friendly image classification project built with PyTorch using the FashionMNIST dataset.

---

## Project Overview

This project demonstrates the complete deep learning workflow with PyTorch, including:

- Loading datasets
- Data visualization
- Building a neural network
- Model training
- Model evaluation
- Prediction
- Saving the trained model

The FashionMNIST dataset contains 10 categories of clothing images.

---

## Dataset

FashionMNIST

Classes:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

Training images: **60,000**

Testing images: **10,000**

---

## Model Structure

```
Input (28×28)

↓

Flatten

↓

Linear (784 → 512)

↓

ReLU

↓

Linear (512 → 256)

↓

ReLU

↓

Linear (256 → 10)
```

---

## Training Configuration

| Parameter | Value |
|-----------|-------|
| Framework | PyTorch |
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Batch Size | 64 |
| Learning Rate | 0.001 |
| Epochs | 5 |

---

## Results

Best Test Accuracy:

**87.29%**

Final Training Accuracy:

**89.64%**

Final Test Accuracy:

**86.98%**

---

## Project Structure

```
PyTorch-FashionMNIST-Classifier/

│

├── pytorch_image_classification.ipynb

├── fashion_mnist_model.pth

├── README.md

└── requirements.txt
```

---

## Future Work

- Build a CNN model
- Improve classification accuracy
- Apply transfer learning
- Build a custom image dataset

---

## Author

Learning PyTorch from scratch.

