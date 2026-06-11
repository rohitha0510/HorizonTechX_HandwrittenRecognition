# Handwritten Character Recognition

## Project Overview

This project was developed as part of the Horizon TechX Machine Learning Internship Program.

The objective of this project is to build a machine learning model capable of recognizing handwritten digits from image data. The model is trained using a dataset of handwritten numerical characters and predicts the digit represented in an input image.

## Dataset

Dataset Used: Scikit-learn Digits Dataset

The dataset contains handwritten digit images ranging from 0 to 9.

### Dataset Information

* Total Samples: 1,797
* Number of Classes: 10 (Digits 0–9)
* Image Size: 8 × 8 pixels

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Joblib

## Machine Learning Algorithm

* Random Forest Classifier

The Random Forest algorithm was used to classify handwritten digits based on pixel intensity values.

## Project Workflow

1. Load the handwritten digits dataset
2. Visualize sample images
3. Preprocess data
4. Split data into training and testing sets
5. Train Random Forest Classifier
6. Evaluate model performance
7. Save the trained model

## Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report

## Results

The trained model successfully recognizes handwritten digits with high accuracy on the test dataset.

Example Output:

* Input Image → Handwritten Digit
* Predicted Output → Corresponding Numeric Digit

## Project Structure

HorizonTechX_HandwrittenCharacterRecognition

├── notebooks

│   └── HandwrittenCharacterRecognition.ipynb

├── model

│   └── handwritten_model.pkl

├── requirements.txt

└── README.md

## Future Improvements

* Implement Convolutional Neural Networks (CNN)
* Support handwritten alphabet recognition
* Build a web-based prediction system
* Real-time image recognition using a webcam

## Author

Machine Learning Internship Project

Horizon TechX Internship Program
