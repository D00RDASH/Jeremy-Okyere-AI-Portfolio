# Project 2 – Image Classification with CNN (Chihuahua vs. Muffin)

## Problem Statement
The objective of this project was to build and train a Convolutional Neural Network (CNN) capable of classifying images of **muffins** and **Chihuahuas**. This well-known visual ambiguity problem illustrates the power of deep learning in distinguishing between objects with very similar visual features.

---

## Approach

1. **Model Architecture**
   - Implemented a CNN with **three convolutional layers**
   - Included activation functions, pooling layers, and fully connected layers to perform classification

2. **Training Process**
   - Trained the model for **10 epochs**
   - Monitored loss and accuracy at each epoch to evaluate model learning behavior
   - Validated performance using a held-out test set

3. **Evaluation**
   - Assessed final accuracy after training  
   - Confirmed the model’s ability to differentiate between the two classes

---

## Results

- **Final Model Accuracy:** **96.67%**

This high accuracy indicates strong feature extraction and classification performance despite the visual similarity between the two classes.

---

## Key Findings

- CNNs are highly effective for tasks where subtle visual differences matter (e.g., Chihuahua vs. muffin).
- Even a relatively simple architecture with three convolutional layers can achieve excellent results with proper training.
- The model rapidly improved during training, demonstrating how gradient-based optimization efficiently tunes deep learning models.
- This project reinforces foundational skills for more advanced computer vision tasks such as object detection and multi-class classification.

---

## Technologies Used

- **numpy**  
- **torch**  
- **torchvision**  
- **torch.nn**  
- **torch.optim**  
- **torch.utils.data**  
- **matplotlib.pyplot**  
- **tqdm**  
- **os**  
- **torchsummary**

---

## How to Run This Project

1. Open the notebook:  
   **`Lab05_CNN_Chihuahua_Muffin.ipynb`**

2. Run in **Google Colab** or a Python 3.8+ environment with PyTorch installed.

3. Install dependencies if running locally:

   ```bash
   pip install torch torchvision matplotlib tqdm numpy

