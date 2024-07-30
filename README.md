# Breast Cancer Classification using Convolutional Neural Networks (CNN)
Welcome to the Breast Cancer Classification project! This project showcases how to use Convolutional Neural Networks (CNNs) to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

# Project Overview
This repository contains a Python script that:

Loads and preprocesses the Breast Cancer Wisconsin (Diagnostic) dataset.
Scales features for improved model performance.
Implements a Convolutional Neural Network to classify tumors.
Evaluates the model on a test set and makes predictions on new images.
# Getting Started
To get started with this project, follow these steps:

# Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/your-repo.git
cd your-repo
Install Dependencies:
Make sure you have the required Python packages. Install them using:

bash
Copy code
pip install numpy pandas tensorflow scikit-learn pillow
Run the Script:
Execute the script to train the model and make predictions:

bash
Copy code
python your_script.py
Ensure you have an image file at the specified path in the script to test predictions.

# How It Works
## Data Preprocessing:

Downloads the dataset and assigns appropriate column names.
Removes non-numeric columns and converts the diagnosis labels to binary format.
Splits the data into training and testing sets.
Scales features to standardize values.
## CNN Model:

Architecture:
Applies convolutional layers with ReLU activation.
Uses max-pooling to reduce spatial dimensions.
Flattens the data and adds fully connected dense layers.
## Compilation: 
Utilizes Adam optimizer and binary cross-entropy loss.
## Training: 
Trains the model with training data and validates it with testing data.
## Evaluation: 
Tests the model's accuracy on unseen data.
## Prediction:

Preprocesses input images by converting them to grayscale, resizing, and normalizing.
Uses the trained model to classify the image as malignant or benign.
# Results
The script displays the model's accuracy on the test set and predicts the class of new images based on the learned features.

# Contributing
Feel free to contribute to this project! Open an issue or submit a pull request to enhance the project.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

