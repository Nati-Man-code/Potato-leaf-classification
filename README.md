Potato-leaf-classification 
Project Overview
This project is centered on the classification of potato leaves, distinguishing them from other objects. The main objective is to create a model that can accurately identify potato leaves and detect non potato images, serving as a foundational component for future models. In the subsequent phase, the model will categorize potato leaves into four specific classes:

Potato Healthy 
Potato Late Blight
Potato Early Blight
Non Potato

Structure
api/: Contains main.py for testing the project. test this on postman by using the provided port. when we test each image from each class it show us the class and confidence but if the image is not potato it respond Image is not potato
saved_models/: this is saved models and scripts related to the model architecture.
training/: Contains different dataset classified on four classes for our potato classification.
requirements.txt: this is a Lists of all dependencies required to run the project.

Getting Started
To initiate this project, clone the repository and install the required dependencies:
use virtual environment
