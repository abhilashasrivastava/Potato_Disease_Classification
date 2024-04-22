# Potato Disease Classification with FastAPI and TensorFlow Serving

This project aims to classify diseases in potato plants using machine learning techniques. It utilizes FastAPI for building a web API and TensorFlow Serving for deploying the trained model.

## Overview

The project involves the following steps:

1. **Data Collection**: Images of potato plants affected by various diseases are collected and organized into classes.

2. **Data Preprocessing**: The image dataset is preprocessed to prepare it for training.

3. **Model Training**: A Convolutional Neural Network (CNN) model is trained using TensorFlow/Keras on the preprocessed image dataset.

4. **Model Deployment**: The trained model is deployed using TensorFlow Serving, allowing it to serve predictions via a web API.

5. **Web API Development**: FastAPI is used to create a web API that interacts with the deployed model, allowing users to submit images for disease classification.

## Code Structure

The project code is organized as follows:

- **Data Preparation**: Images are organized into folders based on their classes. The dataset is split into training, validation, and test sets.

- **Model Development**: A CNN model is developed using TensorFlow/Keras. It consists of several convolutional and pooling layers followed by fully connected layers for classification.

- **Model Deployment**: The trained model is exported and deployed using TensorFlow Serving.

- **Web API**: FastAPI is used to develop a web API that accepts image uploads and returns predictions from the deployed model.

## Usage

To use the potato disease classification system:

1. Install the required dependencies specified in `requirements.txt`.

2. Train the model using the provided dataset and code.

3. Export the trained model and deploy it using TensorFlow Serving.

4. Run the FastAPI web server to provide a user interface for making predictions.

5. Upload images of potato plants to the web interface to classify diseases.

## Technologies Used

- Python
- TensorFlow/Keras
- FastAPI
- TensorFlow Serving
- Matplotlib (for visualization)



