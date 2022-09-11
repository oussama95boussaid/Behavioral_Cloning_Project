# Behavioral_Cloning_Project : Predicting Steering Angles from Captured By Camera 

This project performs behavioral cloning, training an AI agent to mimic human driving behavior in a simulator. Using the vehicle's camera images collected from the human demonstration, we train a deep neural network to predict the vehicle's steering angle.  

The final trained model is tested on the same test track that was run during the human demonstration.

<img src ="img/projectStructure.png" >

# Objective of the project

- Use the simulator to collect data of good driving behavior
- Design, train and validate a model that predicts a steering angle from image data
- Use the model to drive the vehicle autonomously around the first track in the simulator. The vehicle should remain on the road for an entire loop around the track.
- Summarize the results with a written report

# Dependencies

- Python 3.10 / 3.7
- TensorFlow
- Keras
- PIL
- Numpy
- h5py
- Scikit Learn
- Pandas
- OpenCV
- Matplotlib (Optional)
- Udacity behavioral cloning simulator

# Project Stepts :

- step 1 : Collecting data ( from the human demonstration) using simulator for good driving behavior
- step 2 : Load The data
- step 3 : Split data into trainig and validation sets
- step 4 : Define a generator function to be used through training
- step 5 : Use the defined generator for training set and validation set
- step 6 :  Using keras, build a regression model based on nvidia architecture  to predict the steering angle

# My project includes the following files 

