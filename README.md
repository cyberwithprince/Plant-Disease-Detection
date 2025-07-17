# Plant Disease Detection Using Deep Learning

This project uses Convolutional Neural Networks (CNN) and ResNet architectures to classify plant leaf images into healthy or diseased categories. The goal is to help automate plant disease detection using image data.

## Features
- Image classification using custom CNN and ResNet models
- Data augmentation and normalization
- Training, validation, and test dataset splits
- Model evaluation with accuracy, F1 score, precision, recall, and confusion matrix
- Visualization of training and validation performance
- Prediction functions for single and multiple images

## Project Structure
```
Plant-Disease-Detection/
├── CNN-Model.ipynb           # CNN model notebook
├── Resnet-model.ipynb        # ResNet model notebook
├── requirements.txt          # Python dependencies
├── dataset/                  # Image dataset (Train, Test, Validation)
├── output/                   # Model outputs and visualizations
├── example/                  # Example images for testing
```

## Requirements
Install dependencies with:
```
pip install -r requirements.txt
```

## Usage
1. Place your dataset in the `dataset/` folder, organized by class (Healthy, Rust, Powdery, etc.).
2. Open and run `CNN-Model.ipynb` or `Resnet-model.ipynb` in Jupyter or VS Code.
3. Train the model and evaluate its performance.
4. Use the provided prediction functions to classify new images.

## Dataset Structure Example
```
dataset/
  Train/
    Train/
      Healthy/
      Rust/
      Powdery/
  Test/
    Test/
      Healthy/
      Rust/
      Powdery/
  Validation/
    Validation/
      Healthy/
      Rust/
      Powdery/
```

## Notes
- Update file paths in the notebooks if your dataset is in a different location.
- The notebooks include code for both training and evaluating models, as well as making predictions on new images.

