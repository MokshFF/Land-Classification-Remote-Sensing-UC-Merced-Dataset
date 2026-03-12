# Land-Classification-Remote-Sensing-UC-Merced-Dataset
Remote sensing land-use classification using ResNet CNN architecture trained on the UC Merced Land Use dataset.

# Land Use Classification using ResNet

## Project Overview

This project performs land-use classification on satellite images using deep learning.
A ResNet convolutional neural network is trained on the UC Merced Land Use dataset to automatically classify aerial images into different land categories such as forest, residential areas, golf courses, and highways.

The goal of this project is to demonstrate how deep learning models can be used for remote sensing image classification.

## Dataset

The project uses the **UC Merced Land Use Dataset**, which contains aerial images from different land use classes.

Dataset characteristics:

* 21 land use classes
* 100 images per class
* Image size: 256 × 256 pixels
* RGB aerial images

Example classes include:

* Forest
* Freeway
* Golf Course
* Dense Residential
* Agricultural land

## Model

The project uses **ResNet (Residual Neural Network)** architecture.

Key features of ResNet:

* Deep convolutional neural network
* Uses residual connections to avoid vanishing gradient
* Allows training of very deep models

Possible models used:

* ResNet18
* ResNet50

## Project Structure

```
ResNET-Project
│
├── dataset
│   └── UCMerced_LandUse
│       └── Images
│           ├── forest
│           ├── freeway
│           ├── denseresidential
│           └── golfcourse
│
├── train.py
├── test.py
├── model.py
└── README.md
```

## Technologies Used

* Python
* Deep Learning
* PyTorch / TensorFlow
* Computer Vision
* Remote Sensing
* CNN Architecture

## How to Run the Project

Clone the repository

```
git clone https://github.com/yourusername/land-use-classification-resnet.git
```

Install dependencies

```
pip install -r requirements.txt
```

Run the training script

```
python train.py
```

Run prediction

```
python test.py
```

## Applications

* Satellite image analysis
* Urban planning
* Environmental monitoring
* Land cover mapping
* Geographic information systems (GIS)

## Author

Moksh
