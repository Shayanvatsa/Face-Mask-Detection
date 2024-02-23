# Face Mask Detection using Convolutional Neural Networks

This project aims to detect whether a person in an image is wearing a face mask or not using Convolutional Neural Networks (CNNs). It utilizes a dataset consisting of images with and without masks to train a CNN model.

## Table of Contents

- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for training the model consists of two classes: images with masks and images without masks. It was obtained from the Kaggle dataset ["Face Mask Detection"](https://www.kaggle.com/ashishjangra27/face-mask-detection).

## Model Architecture

The CNN model architecture used for this project consists of multiple layers including convolutional layers, max-pooling layers, dropout layers, and dense layers. The final layer uses a sigmoid activation function to predict the probability of whether the person is wearing a mask or not.

## Usage

To use this project:

1. Clone the repository:
```
    git clone https://github.com/yourusername/face-mask-detection.git

```

2. Install the required dependencies:
```
    pip install -r requirements.txt
```


3. Run the `train.py` script to train the model:
```
    python train.py
```


4. Once the model is trained, you can make predictions on new images using the `predict.py` script:
```
    python predict.py --image_path path/to/your/image.jpg
```


## Results

The model achieved a test accuracy of XX% on the test dataset. Here are some sample results:

- Image 1: The person in the image is wearing a mask
- Image 2: The person in the image is not wearing a mask

## Future Improvements

- Fine-tuning the model architecture for better performance
- Exploring data augmentation techniques to improve generalization
- Deploying the model as a web application or mobile app for real-time face mask detection

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


