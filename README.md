# QRAuthentication

This project utilizes machine learning techniques for QR code classification, leveraging TensorFlow, OpenCV, and scikit-learn.

## Features
- Loads and processes QR code images
- Uses Convolutional Neural Networks (CNNs) for classification
- Employs Support Vector Machines (SVM) for additional analysis
- Visualizes results with Matplotlib and Seaborn

## Installation
Ensure you have the required dependencies installed:
```bash
pip install tensorflow opencv-python numpy matplotlib seaborn scikit-learn tqdm
```

## Usage
Run the Jupyter Notebook to train and evaluate the model:
```bash
jupyter notebook "QRCode.ipynb"
```

## Dataset
The dataset should be stored in the following path:
```
/content/drive/MyDrive/Assignment_Data/
```
Ensure the dataset contains correctly labeled QR code images.

## Model Training
The notebook includes:
- Data preprocessing
- Model training using TensorFlow/Keras
- Evaluation using SVM and performance metrics

## Results
- Confusion matrix visualization
- Classification report with accuracy, precision, and recall


