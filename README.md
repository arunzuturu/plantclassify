# Plant Leaf Disease Classification

This Flask application detects diseases in the leaves of 15 varieties of plants, including Pepper, Potato, and Tomato. The model used is a Convolutional Neural Network (CNN) with 5 layers.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features
- Classifies leaf diseases for 15 different plant varieties.
- Easy-to-use web interface for uploading leaf images.
- Provides accurate predictions using a pre-trained 5-layer CNN model.

## Installation

### Prerequisites
- Python 3.7 or higher
- Flask
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pillow

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/plant-leaf-disease-classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd plant-leaf-disease-classification
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Flask app:
    ```bash
    python app.py
    ```
2. Open your web browser and go to:
    ```
    http://127.0.0.1:4555
    ```
3. Upload an image of a plant leaf to get the disease classification result.

## Model Architecture
The model is a Convolutional Neural Network (CNN) with the following architecture:
1. Convolutional Layer 1
2. Max-Pooling Layer 1
3. Convolutional Layer 2
4. Max-Pooling Layer 2
5. Fully Connected Layer
6. Output Layer

This architecture has been trained to achieve high accuracy on the given dataset.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- Dataset used for training the model is from [source].
- This project is inspired by the need to assist farmers in identifying plant diseases early.
