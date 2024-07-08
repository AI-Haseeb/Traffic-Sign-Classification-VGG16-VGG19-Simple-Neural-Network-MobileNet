# Traffic Sign Classification using VGG16

This project focuses on classifying traffic signs using the VGG16 model. The dataset is split into training and testing sets, achieving 95% accuracy after 5 epochs.

## Project Structure

- `data/`: Contains the entire dataset.
- `train/`: Contains 80% of the data for training.
- `test/`: Contains 20% of the data for testing.
- `traffic-sign-classification-vgg16.ipynb`: Google Colab notebook containing the project code.

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
   - Train the model for 5 epochs.

5. **Evaluation**:
   - Achieve 95% accuracy on the test set.

## Usage

To run the project:
- Open `traffic-sign-classification-vgg16.ipynb` in Google Colab Notebook.
- Follow the step-by-step instructions to execute the code.

