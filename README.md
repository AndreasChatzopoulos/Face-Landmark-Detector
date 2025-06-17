
# Facial Landmark Detection with HOG and Ridge Regression

This project detects 5 facial landmarks using machine learning with handcrafted image features.

## Features
- Data augmentation (flipping, brightness/contrast)
- Feature extraction using Histogram of Oriented Gradients (HOG)
- Ridge Regression model for landmark coordinate prediction
- Comparative baseline using SIFT + PCA

## Dataset
- 2811 training images and 554 test images (96x96 grayscale)

## Results
- HOG + Ridge Regression achieved 4.11 px mean landmark error
- Outperformed SIFT baseline

## How to Run
Open the `task_2_final.ipynb` notebook and execute all cells. Ensure the dataset is correctly referenced and dependencies installed.

## Requirements
```bash
pip install numpy pandas matplotlib scikit-image scikit-learn opencv-python
```

## Author
[Your Name]
