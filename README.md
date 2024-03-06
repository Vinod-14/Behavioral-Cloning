# Self-Driving Car Behavioral Cloning Project

## Overview
This project aims to develop a neural network model capable of mimicking human driving behavior in a simulated environment. The model is trained using a dataset of images captured from the car's cameras and corresponding steering angles. Behavioral cloning is used to train the model to predict steering angles based on the input images, enabling the car to navigate autonomously.

## Features
- Data preprocessing scripts to prepare the dataset
- Implementation of a neural network architecture (NVIDIA model) for behavioral cloning
- Training scripts for model training and evaluation
- Visualization tools for analyzing model performance and predictions

## Usage
1. **Dataset Preparation**: Download the dataset and organize it into appropriate directories (e.g., `data/IMG`, `data/driving_log.csv`).
2. **Data Preprocessing**: Use preprocessing scripts to resize, augment, and preprocess images for training.
3. **Model Training**: Train the neural network model using the provided training script.
4. **Model Evaluation**: Evaluate the trained model using the validation dataset and visualization tools.
5. **Prediction**: Use the trained model to make predictions on unseen images or video streams.

## Dependencies
- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Matplotlib
- scikit-image
- imgaug

Install dependencies using `pip install -r requirements.txt`.

## Step-by-Step Guide
### 1. Dataset Preparation
- Download the dataset from the provided source.
- Organize the dataset into the following directories:
  - `data/IMG`: Contains image files captured by the car's cameras.
  - `data/driving_log.csv`: Contains steering angles and other driving data.

### 2. Data Preprocessing
- Use the provided preprocessing scripts to prepare the dataset for training.
- Perform resizing, augmentation, and preprocessing on the images.
- Ensure that the data is properly formatted and ready for input into the neural network.

### 3. Model Training
- Train the neural network model using the NVIDIA architecture implemented in the provided code.
- Adjust hyperparameters as needed and monitor training progress using training scripts.
- Save the trained model for future use and evaluation.

### 4. Model Evaluation
- Evaluate the trained model using the validation dataset to assess its performance.
- Use visualization tools to analyze model predictions and identify areas for improvement.

### 5. Prediction
- Use the trained model to make predictions on unseen images or video streams.
- Visualize the predictions and assess the model's performance in real-world scenarios.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please follow the guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Authors
- [Vinod](https://github.com/Vinod-14)

## Acknowledgements
- NVIDIA model architecture referenced from [NVIDIA Corporation](https://www.nvidia.com)
