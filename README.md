# Image Recommendation System Using CNN and KNeighbors

## Overview
This project implements an image recommendation system using Convolutional Neural Networks (CNN) and the K-Nearest Neighbors (KNeighbors) algorithm. The system extracts features from images using a pre-trained ResNet50 model and recommends similar images based on these features.

## Dataset
Download the Fashion Images dataset from Kaggle (https://www.kaggle.com/datasets/vikashrajluhaniwal/fashion-images) and extract it into the data directory.

## Setup Instructions
### 1. Clone the Repository
git clone https://github.com/yourusername/image-recommendation-system.git
cd image-recommendation-system

### 2. Download the Dataset
Extract the downloaded dataset into the data directory so it looks like this:
image-recommendation-system/
└── data/
    ├── img (1).jpg
    ├── img (2).jpg
    └── ...


### 3. Install Dependencies
* opencv-python
* numpy
* tensorflow
* scikit-learn
* tqdm

### 4. Running the Code
Run the provided Python scripts in a Jupyter notebook or directly in your Python environment.