# Face Mask Detection

## Overview
This project aims to detect whether a person is wearing a face mask or not using deep learning techniques. It is implemented in Python using TensorFlow and Keras libraries.

## Features
- **Convolutional Neural Network (CNN)**: Utilizes a CNN architecture for image classification, which is well-suited for tasks involving image data.
- **Data Augmentation**: Augments the training data to increase its diversity and improve the model's ability to generalize.
- **Early Stopping**: Implements early stopping during model training to prevent overfitting and improve training efficiency.
- **Confusion Matrix**: Evaluates model performance using a confusion matrix to analyze the number of true positive, true negative, false positive, and false negative predictions.

## How to Use
1. **Installation**:
   - Clone the repository to your local machine:
     ```
     git clone https://github.com/your_username/face-mask-detection.git
     ```
   - Install the required dependencies:
     ```
     pip install -r requirements.txt
     ```

2. **Data Preparation**:
   - Download the face mask dataset and organize it into separate directories for images with and without masks.
   - Preprocess the data by resizing the images to a consistent size and converting them to the desired format.

3. **Model Training**:
   - Run the training script to train the face mask detection model:
     ```
     python train_model.py
     ```
   - Adjust hyperparameters, model architecture, and training parameters as needed in the script.

4. **Model Evaluation**:
   - After training, evaluate the model's performance on a separate test dataset:
     ```
     python evaluate_model.py
     ```
   - View the confusion matrix and other evaluation metrics to assess the model's accuracy and performance.

5. **Inference**:
   - Use the trained model to make predictions on new images:
     ```
     python predict.py --image_path /path/to/image.jpg
     ```

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
