# Cat vs Dog Image Classification Using SVM

## Project Overview
This project implements a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs using the popular Kaggle Dogs vs Cats dataset. The images are preprocessed, resized, and converted to grayscale before being fed into the SVM model.

## Dataset
The dataset used is from the Kaggle Dogs vs Cats competition (available [here](https://www.kaggle.com/c/dogs-vs-cats/data)).  
- The images are stored in a `train` folder.  
- Images are labeled by their filename prefix (`cat` or `dog`).

## Features
- Image loading and preprocessing using OpenCV  
- Resizing images to 100x100 pixels  
- Grayscale conversion  
- Dataset creation with labels (0 for cat, 1 for dog)  
- Ready to be used for training an SVM model

## How to Run
1. Download and place the `train` folder inside the `predict_image` directory.  
2. Set your current working directory to `predict_image`.  
3. Run the Python script to create the dataset:  
```bash
python create_dataset.py
Requirements
Python 3.x

OpenCV (opencv-python)

NumPy

tqdm

Install dependencies via pip:

bash
Copy
Edit
pip install opencv-python numpy tqdm
Next Steps
Train an SVM classifier using extracted features

Evaluate the model on test images

Experiment with color images or other feature extraction methods
