# AI-Gym-Coach
AI Gym Coach: Exercise Form Detection Using Convolutional Neural Networks (CNN)

# Table of Content
- # Info
- # Demo
- # Technologys and Tools
- # Setup
- # Processes
- # Features


# Info
This project utilizes Convolutional Neural Networks (CNN) in conjunction with PoseNet to detect whether the training data is true or false.
The combination of CNN and PoseNet allows for accurate detection of poses and classification of training data.

## Demo
- correctTrain
![CorrectTrain](https://github.com/shnooo0/AI-Gym-Coach/blob/main/Images/correct_Train.png)
- IncorrectTrain
![IncorrectTrain](https://github.com/shnooo0/AI-Gym-Coach/blob/main/Images/Incorrect_Train.png)

## Technologies and Tools

- Python
- TensorFlow
- Keras
- PoseNet
- open-cv
- jupyter notebook


## Setup

1. Clone the repository:

  ```bash
   git clone https://github.com/shnooo0/AI-Gym-Coach 
  ```

2. Install dependencies:
 ```bash
   pip install -r requirement.txt
  ```

3. To run project:
- "optionally" update code ```Pose_extract.ipynb``` with your dataset to extract Pose Features from Dataset
- "Optionally" if you run the previous code ```Pose_extract``` you can use the extracted pose features that you get as output or in case you don't run it you can use our PoseDataset on [DriveLink](https://drive.google.com/drive/u/0/folders/1aBBl88ddYuxOkktYSYWYdPf8SDtqS0ev) to run this code ```Models_Training.ipynb```
- download the models from [DriveLink](https://drive.google.com/drive/u/0/folders/1aBBl88ddYuxOkktYSYWYdPf8SDtqS0ev) and load it in the code ```Using_Models.ipynb``` by replace the path of the model by your model local path

## Processes

1. Data Collection: Gather training data consisting of labeled poses.
2. Data Preprocessing: Prepare the data for training by normalizing, augmenting, and splitting.
3. Model Training: Train the CNN model using the preprocessed data.
4. Pose Detection: Utilize PoseNet for detecting poses in new data.
5. Classification: Classify the detected poses using the trained CNN model.


## Features

- Pose detection using PoseNet
- Training data classification with CNN
