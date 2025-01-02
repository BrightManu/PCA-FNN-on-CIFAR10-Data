# PCA-FNN-on-CIFAR10-Data
This project demonstrates the application of Principal Component Analysis (PCA) for dimensionality reduction and a Feedforward Neural Network (FNN) for image classification on the CIFAR-10 dataset. The goal is to reduce computational complexity while maintaining classification performance.

## Key Features
- **Dataset**: Utilizes the CIFAR-10 dataset containing 60,000 32x32 color images across 10 classes.
- **Dimensionality Reduction**: PCA is applied to reduce the high-dimensional image data to a lower-dimensional feature space.
- **Classification**: A fully connected Feedforward Neural Network is trained on the reduced data to classify images.
- **Evaluation Metrics**: Accuracy, AUROC and per-class accuracy are used to evaluate the model's performance.

## Highlights
- Achieved efficient dimensionality reduction while retaining key features of the dataset.
- Optimized neural network architecture for classification on the reduced feature set.
- Included visualizations of PCA explained variance, ROC curve, FNN training progress among others

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/BrightManu/PCA-FNN-on-CIFAR10-Data.git
   ```
2. Install dependencies:
   ```bash
   pip install package
   ```
   Dependencies
   - numpy
   - matplotlib
   - torch
   - torchvision
   - scikit-learn
  
4. Open the notebook:
   - Launch Jupyter Notebook or any compatible environment.
   - Open the notebook file (`Project-PCA_FNN.ipynb`).

5. Execute all cells sequentially to run the project.

## Acknowledgments
- CIFAR-10 Dataset: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
