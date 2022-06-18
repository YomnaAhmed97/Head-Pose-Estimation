# Head-Pose-Estimation
In this project I've worked on AFLW2000-3D dataset which is a dataset of 2000 images that have been annotated with image-level 68-point 3D facial landmarks, with various head poses for humans and animations.
By using mediapipe to extract faces landmarks which are 468 points in 3D, but we used x-axis & y-axis.
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

 ### Humans:
 - https://drive.google.com/file/d/1RwTD1i-DmeRcXFli0syQhl9FwazVI30f/view?usp=sharing

  ![tryfromerror (1)](https://user-images.githubusercontent.com/32110361/174424057-76d96d78-f2f6-4d89-a658-54a202166bbf.gif)


 
 - https://drive.google.com/file/d/1R0c40IpKj0w7qftg1swEiE-hb-PUg2qW/view?usp=sharing

![Ataf-pose-estimation](https://user-images.githubusercontent.com/32110361/174424062-a395af30-5c82-4837-9b6e-a155f4942231.gif)


 ### Animation:
   - https://drive.google.com/file/d/1XTgzZG1BckDbh1RiaLAkxQ6lxp183B-m/view?usp=sharing

![hunter](https://user-images.githubusercontent.com/32110361/174424078-1ba40e00-c62a-42b7-84a8-75400611b03b.gif)





## For more information about mediapipe:
 https://google.github.io/mediapipe/solutions/face_mesh.html
