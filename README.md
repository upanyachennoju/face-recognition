# Facial Recognition using Machine Learning

## Overview
This project implements facial recognition using machine learning techniques. It utilizes the LFW (Labeled Faces in the Wild) dataset, applies PCA for dimensionality reduction, and trains an SVM classifier for prediction.

## Features
- Loads and preprocesses the LFW dataset
- Applies PCA for feature reduction
- Uses an SVM classifier with hyperparameter tuning
- Evaluates model performance using a classification report and confusion matrix
- Visualizes predictions and model performance

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/upanyachennoju/face-recognition.git
   cd face-recognition
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the script to train the model and evaluate its performance:
```sh
python FaceRecognition.ipynb
```

## Dependencies
The project requires the following Python libraries:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Results
The model is evaluated using classification reports and a confusion matrix heatmap. Sample images with correct and incorrect predictions are also displayed.

## Contributing
Feel free to fork the repository and submit pull requests for improvements or new features.

## License
This project is licensed under the MIT License.

