# Handwritten Digit Recognition Using Machine Learning and Deep Learning

## Project Overview

Handwritten digit recognition is one of the fundamental problems in computer vision and pattern recognition. This project aims to develop intelligent models capable of accurately recognizing handwritten digits from image data.

The project utilizes the MNIST (Modified National Institute of Standards and Technology) dataset and implements both traditional machine learning algorithms and deep learning architectures to identify the most suitable model for digit classification.

---

## Problem Statement

Develop a predictive system capable of accurately recognizing handwritten digits (0–9) using image classification techniques.

---

## Dataset Information

The project uses the **MNIST dataset**, which is provided as a built-in dataset in TensorFlow.

### Dataset Characteristics

| Attribute | Description |
|------------|------------|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Number of Classes | 10 |
| Digits | 0–9 |
| Image Size | 28 × 28 pixels |
| Image Type | Grayscale |

---

## Project Workflow

1. Import Required Libraries
2. Dataset Loading
3. Dataset Overview and Initial Exploration
4. Data Visualization
5. Target Variable Analysis
6. Data Preprocessing
7. Traditional Machine Learning Model Development
8. Artificial Neural Network (ANN)
9. Convolutional Neural Network (CNN)
10. Deep Learning Model Comparison and Final Model Selection
11. Model Saving
12. Final Insights
13. Recommendations
14. Challenges Faced
15. Future Scope
16. Final Conclusion

---

## Machine Learning Models Used

### Traditional Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### Deep Learning Models

- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

---

## Model Performance Comparison

| Model | Accuracy |
|---------|---------:|
| Convolutional Neural Network (CNN) | 99.17% |
| Support Vector Machine (SVM) | 97.92% |
| Artificial Neural Network (ANN) | 97.34% |
| K-Nearest Neighbors (KNN) | 96.88% |
| Random Forest | 96.83% |
| Logistic Regression | 92.57% |
| Decision Tree | 87.73% |

---

## Final Model

### Convolutional Neural Network (CNN)

The CNN model achieved the highest testing accuracy of approximately **99.17%** and was selected as the final model because of its superior ability to preserve spatial information and automatically extract hierarchical image features.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow
- Keras
- Jupyter Notebook

---

## Model File

The trained CNN model is saved as:

```text
handwritten_digit_cnn_model.h5
```

---

## Applications

- Optical Character Recognition (OCR)
- Bank cheque processing
- Postal code recognition
- Automatic form digitization
- Document processing systems
- Educational applications
- Intelligent handwriting recognition systems

---

## Future Scope

- Advanced CNN architectures
- Transfer learning approaches
- Data augmentation techniques
- Real-time web and mobile applications
- Multilingual handwriting recognition
- Explainable Artificial Intelligence (XAI)
- Cloud deployment and scalable prediction systems

---

## Conclusion

This project demonstrates the effectiveness of both traditional machine learning and deep learning techniques for handwritten digit recognition. Comparative analysis showed that the Convolutional Neural Network outperformed all other models and achieved a testing accuracy of approximately 99.17%.

Therefore, CNN was selected as the final model and provides a strong foundation for real-world applications such as Optical Character Recognition, document digitization, banking systems, and intelligent automation solutions.

---

## Repository Structure

```text
Handwritten-Digit-Recognition-Using-Machine-Learning-and-Deep-Learning
│
├── HandWrittenDigit.ipynb
├── handwritten_digit_cnn_model.h5
├── README.md
├── requirements.txt
└── images/
```

---

## Author

**Katta Srichakra**

MCA Student | Machine Learning and Deep Learning Enthusiast
