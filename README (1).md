# ML_Project
# Handwritten Digit Recognition/MNIST dataset 

## Features

Built with Python and TensorFlow/Keras

Utilizes Convolutional Neural Network (CNN) for high-accuracy image classification

Trained on the MNIST dataset with over 60,000 images

Achieved high training and validation accuracy

Includes model evaluation, prediction, and visualization

## Tech Stack

Language: Python

Libraries: NumPy, Matplotlib, TensorFlow, Keras

Dataset: MNIST (Modified National Institute of Standards and Technology)

## Model Architecture

The CNN model includes:

Convolutional layers for feature extraction

MaxPooling layers for dimensionality reduction

Dropout layers to prevent overfitting

Dense layers for classification

## Results

The model achieves high accuracy on the test set, making it effective for digit recognition tasks. You can also use it to predict digits from new handwritten inputs.

## Sample Output

Input Image	  Predicted Digit  

                    7

## Project Structure

hand_digit_recognition/
│
├── digit_recognition.ipynb       # Main Jupyter Notebook
├── model/                        # Trained model files (if any)
├── README.md                     # Project documentation
└── requirements.txt              # Required Python libraries

##How to Run

## Clone the repository:

git clone https://github.com/ajithreddy13/hand_digit_recognition1
cd hand_digit_recognition1

## Install the dependencies:

pip install -r requirements.txt

## Run the notebook:

Open `digit_recognition.ipynb` in Jupyter Notebook
