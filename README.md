# Fashion MNIST Image Classification

This repository contains a Streamlit web application for classifying Fashion MNIST images using a deep learning model. The app allows users to upload images, preprocesses them, and predicts the class using a trained convolutional neural network (CNN).

## Features

- **Upload an image:** Users can upload images in PNG, JPG, or JPEG format.
- **Image preprocessing:** The uploaded image is resized, converted to grayscale, normalized, and reshaped to match the input shape expected by the model.
- **Prediction:** The app uses a trained CNN model to classify the image into one of the Fashion MNIST classes.
- **Download processed image:** The app also allows users to download the preprocessed image.

## Demo

You can check out the app [here](#).

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Streamlit
- PIL (Pillow)
- NumPy

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/alihassanml/Fashion-Mnist-Prediction.git
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

### Project Structure

```
fashion-mnist-prediction/
│
├── app.py               # The main Streamlit app
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

### Usage

1. Upload an image through the Streamlit interface.
2. The app will preprocess the image and display it.
3. The app will predict the class of the image using the CNN model.
4. You can download the preprocessed image.

### Model

The model is a convolutional neural network trained on the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). Ensure that the `model.h5` file is present in the root directory of the project.

### Acknowledgements

- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- [Streamlit](https://www.streamlit.io/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
