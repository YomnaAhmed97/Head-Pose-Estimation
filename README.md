# Head-Pose-Estimation
In this project I've worked on AFLW2000-3D dataset which is a dataset of 2000 images that have been annotated with image-level 68-point 3D facial landmarks, with various head poses.
By using mediapipe to extract faces landmarks which are 468 points in 3D, but we used X & Y only.
The regression model of predicting the 3 angles (pitch - yaw - roll) of head pose estimation was XGboost Regressor.

## Data
 You can download from http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip 
 This data contains different pictures for human faces with different poses.
 
 ## Steps:
  1) Preparing data for model training ( we used MediaPipe and CV2 libraries for extracting points and for face detection from pictures).
  2) Spliting the data to training, validation and testing.
  3) Using regression model.
  4) Detecting a random pic to validate the model from dataset.

## Conc:
 - https://drive.google.com/file/d/1RwTD1i-DmeRcXFli0syQhl9FwazVI30f/view?usp=sharing
 
 - https://drive.google.com/file/d/1R0c40IpKj0w7qftg1swEiE-hb-PUg2qW/view?usp=sharing




## For more information about mediapipe:
 https://google.github.io/mediapipe/solutions/face_mesh.html
