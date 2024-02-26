
Arabic Letters Classification Project
Overview
This project aims to develop a model for recognizing and classifying Arabic letters using a convolutional neural network (CNN). The dataset consists of 65 different Arabic alphabets, each with variations on the beginning, middle, end, and regular alphabets. Additionally, there are 10 different Arabic words encompassing all Arabic alphabets, along with 3 different paragraphs. The dataset was collected anonymously from 82 different users, with each user providing 10 samples for each alphabet, word, and paragraph. In total, the dataset comprises 53,199 alphabet images, 8,144 word images, and 241 paragraph images.

Dataset Details
Isolated Alphabets Dataset: The file "isolated_alphabets_per_alphabet.zip" contains 53,199 Arabic alphabets organized into folders, each representing a specific alphabet variation.
Dataset Organization

Train Directory:
Contains 65 subdirectories, each representing a class.
Class names are represented by numbers 0-64.

Test Directory:
Contains images for evaluation. Pass these images to your model and save predictions to evaluate model performance.
Notebook Workflow

Environment Setup:
Ensure you have the necessary libraries and dependencies installed.
Use a virtual environment if needed.

Data Visualization:
Explore the dataset to gain insights into the structure and content.
Visualize sample images to understand the data distribution.

Model Definition:
Define the model architecture using a convolutional neural network (CNN) through Keras, a TensorFlow tool.
Utilize the provided code as a starting point for your model definition.
Training the Model:

Train your model on the training dataset.
Fine-tune hyperparameters and monitor training progress.
Prediction:

Use the trained model to make predictions on the test dataset.
Evaluate the model's performance by comparing predictions with ground truth.

Dataset Link
The dataset can be accessed on Kaggle: https://www.kaggle.com/competitions/arabic-letters-classification
