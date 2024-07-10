# Traffic Sign Classification using VGG16, VGG19, Simple Neural Network, and MobileNet

This project focuses on classifying traffic signs using various models: VGG16, VGG19, Simple Neural Network, and MobileNet.

## Project Structure

- `data/`: Contains the entire dataset.
- `train/`: Contains 80% of the data for training.
- `test/`: Contains 20% of the data for testing.

## Steps Overview

1. **Import Libraries and Dataset Inspection**:
   - Import necessary libraries.
   - Check the number of images in each folder inside the `data` directory.

2. **Data Preparation**:
   - Split the dataset into 80% training and 20% testing.
   - Move the split data into `train` and `test` directories.

3. **Data Preprocessing**:
   - Balance the dataset to handle class imbalance.

4. **Model Building and Training**:
   - Implement the VGG16 model architecture.
   - Implement the VGG19 model architecture.
   - Implement a Simple Neural Network.
   - Implement the MobileNet architecture.
   - Train the models for 5 epochs, 15 epochs or 30 epochs.

5. **Evaluation**:
   - Evaluate the performance of each model on the test set.

## Usage

To run the project:
- Open files in Google Colab Notebook.
- Follow the step-by-step instructions to execute the code.
