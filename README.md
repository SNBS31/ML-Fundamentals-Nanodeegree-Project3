# Project: Landmark Classification & Tagging for Social Media

## Project Overview

In this project, I applied the skills acquired in the Convolutional Neural Network (CNN) course to build a landmark classifier. The aim was to develop a model that can automatically predict the location of an image based on discernible landmarks depicted in it. This is particularly useful for photo sharing and storage services that rely on location data to enhance user experience through features like automatic tagging and photo organization.

## Project Steps

The project consists of three major steps, each carried out in a corresponding Jupyter Notebook:

1. **Create a CNN to Classify Landmarks (from Scratch)**  
   - Visualized the dataset and processed it for training.
   - Built a convolutional neural network from scratch to classify the landmarks.
   - Described decisions around data processing and network architecture.
   - Exported the best network using Torch Script.

2. **Create a CNN to Classify Landmarks (using Transfer Learning)**  
   - Investigated different pre-trained models and selected one for the classification task.
   - Trained and tested the transfer-learned network.
   - Explained the reasoning behind the choice of pre-trained network.
   - Exported the best transfer learning solution using Torch Script.

3. **Deploy the Algorithm in an App**  
   - Developed a simple app to allow users to find the most likely landmarks depicted in an image using the best model.
   - Tested the model and reflected on its strengths and weaknesses.

## Starter Code and Instructions
The project includes starter code provided in the project workspace, available for download for local work. The following notebooks guide the project work:

- `cnn_from_scratch.ipynb`: Create a CNN from scratch.
- `transfer_learning.ipynb`: Use transfer learning.
- `app.ipynb`: Deploy the best model in an app and generate the submission file.


## Results

The initial model achieved an accuracy of 57%.
 Transfer learning with ResNet18 was implemented, resulting in a 
 significantly improved accuracy of 73%.

## Project Submission

At the end of the `app.ipynb` notebook, instructions are provided to generate a submission file (e.g., `submission_2022-03-31T00h55m.tar.gz`) containing all notebooks and code. This file can be submitted for review.

## Conclusion

This project was a comprehensive exercise in applying machine learning techniques to real-world problems. It enhanced my understanding of CNNs, data preprocessing, model training, and deployment.
