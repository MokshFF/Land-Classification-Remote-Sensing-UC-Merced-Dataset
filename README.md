# Land-Classification-Remote-Sensing-UC-Merced-Dataset
Remote sensing land-use classification using ResNet CNN architecture trained on the UC Merced Land Use dataset.


# Land Use Classification using ResNet

## Project Overview

This project performs land-use classification on aerial or satellite images using deep learning. A Residual Neural Network (ResNet) model is trained to classify images into different land-use categories such as forest, residential areas, golf courses, and highways.

The system demonstrates how deep learning and computer vision can be applied to remote sensing data for automatic land classification.

## Dataset

The project uses the **UC Merced Land Use Dataset**.

Dataset link:
https://www.kaggle.com/datasets/abdulhasibuddin/uc-merced-land-use-dataset

Dataset details:

* 21 land use classes
* 100 images per class
* Total images: 2100
* Image size: 256 × 256 pixels
* RGB aerial images

The images were extracted from the USGS National Map Urban Area Imagery collection and are widely used in research for land-use classification tasks. ([Hugging Face][1])

Example classes include:

* Agricultural
* Airplane
* Baseball Diamond
* Beach
* Buildings
* Dense Residential
* Forest
* Freeway
* Golf Course
* Harbor
* Runway
* Storage Tanks
* Tennis Court

## Model

The project uses **ResNet (Residual Neural Network)** architecture for image classification.

Key advantages of ResNet:

* Solves vanishing gradient problem
* Allows training of very deep neural networks
* Provides better accuracy for image classification tasks

Possible architectures used:

* ResNet18
* ResNet50

## Project Structure

ResNet-LandUse-Classification

├── dataset
│ └── UCMerced_LandUse
│ └── Images
│ ├── forest
│ ├── freeway
│ ├── denseresidential
│ └── golfcourse

├── train.py
├── test.py
├── model.py
└── README.md

## Technologies Used

* Python
* Deep Learning
* PyTorch / TensorFlow
* Computer Vision
* Remote Sensing
* Convolutional Neural Networks (CNN)

## How to Run the Project

Clone the repository

git clone https://github.com/yourusername/land-use-classification-resnet.git

Install dependencies

pip install -r requirements.txt

Run training

python train.py

Run testing

python test.py

## Applications

* Satellite image analysis
* Urban planning
* Environmental monitoring
* Geographic Information Systems (GIS)
* Land cover mapping

## Author

Moksh

[1]: https://huggingface.co/datasets/SatwikKambham/uc_merced_land_use?utm_source=chatgpt.com "SatwikKambham/uc_merced_land_use · Datasets at ..."

