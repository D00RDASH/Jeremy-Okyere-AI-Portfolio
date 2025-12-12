# Project 3 – Image Classification with SVM

## Problem Statement
The goal of this project was to build a Support Vector Machine (SVM) model capable of classifying images into three categories: **cats**, **dogs**, and **ships**. This task demonstrates how classical machine learning algorithms perform on visual classification problems and highlights the challenges of applying SVMs to high-dimensional image data.


## Approach
The project followed a typical machine learning workflow:

1. **Dataset Preparation**
   - Loaded labeled images representing the three classes  
   - Converted images into numerical feature representations  
   - Preprocessed the data (flattening, scaling, etc.)

2. **Model Development**
   - Trained a multi-class SVM classifier  
   - Used the one-vs-rest strategy to handle multi-class classification  

3. **Model Evaluation**
   - Measured accuracy, precision, recall, and F1-score  
   - Evaluated each class individually  
   - Compared relative performance to understand model strengths and weaknesses  


## Results

### Overall Accuracy
**54.7%**

### Performance by Class

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| **Cat** | 48% | 48% | 48% |
| **Dog** | 49% | 48% | 49% |
| **Ship** | 66% | 68% | 67% |

**Insights:**  
- The SVM model achieved noticeably stronger results on *ships*, likely due to their more distinct shapes and features.  
- Cats and dogs, which have more similar textures and structures, were more difficult for the SVM to separate in feature space.


## Key Findings
- SVMs can be used for image classification, but they often struggle with classes that share similar visual patterns, such as cats and dogs.  
- Higher performance on ships suggests that simpler, more structured objects are easier to distinguish with linear boundaries.  
- This project demonstrates the limitations of classical machine learning for image tasks and shows why deep learning models (like CNNs) became the standard for computer vision.  
- Completing this model builds foundational intuition before moving into more advanced neural network architectures.


## Technologies Used
- Python  
- Jupyter Notebook  
- NumPy  
- scikit-learn  
- Matplotlib  
- Image preprocessing tools (PIL or OpenCV depending on the notebook)


## How to Run This Project
1. Open the notebook:
   **`L03_B_Jeremy_Okyere_ITAI_1378.ipynb`**
2. Run in **Google Colab** or a local Python 3.8+ environment.
3. Install required libraries if running locally:
   ```bash
   pip install numpy scikit-learn matplotlib pillow

