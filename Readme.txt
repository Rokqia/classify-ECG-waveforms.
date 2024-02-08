# ECG Signal Classification Project

## Overview
This project involves the classification of ECG (Electrocardiogram) signals using deep learning techniques. The signals are loaded from MATLAB files, preprocessed, and then used to train a ResNet50-based convolutional neural network (CNN) for classification.

## Project Structure
- **Data:**
  - ECGData.mat: MATLAB file containing raw ECG signals.
  - ECG_data.csv: CSV file with preprocessed ECG data.
  - Labels.csv: CSV file containing corresponding labels for the ECG signals.

- **Scripts:**
  - `ecg_classification.ipynb`: Jupyter Notebook containing the code for data loading, preprocessing, signal visualization, and CNN training.

- **Figures:**
  - Folder containing spectrogram images generated during signal visualization.

- **Models:**
  - `mymodel.h5`: Saved trained ResNet50 model.

## Instructions
1. **Data Preparation:**
   - Raw ECG signals are stored in ECGData.mat.
   - Preprocess the data using the provided CSV files (ECG_data.csv and Labels.csv).

2. **Signal Visualization:**
   - Run the cell for signal visualization in `ecg_classification.ipynb`.
   - Spectrogram images will be saved in the 'Figures' folder.

3. **CNN Model Training:**
   - Run the cells for CNN model training in `ecg_classification.ipynb`.
   - The trained model will be saved as `mymodel.h5`.

4. **Evaluation:**
   - Evaluate the model on test data to check accuracy and performance.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- pandas
- matplotlib
- scipy

