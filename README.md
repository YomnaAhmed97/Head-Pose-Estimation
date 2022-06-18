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




https://user-images.githubusercontent.com/32110361/174423427-08643058-e081-4080-ae0c-0723825e6ec9.mp4



## For more information about mediapipe:
 https://google.github.io/mediapipe/solutions/face_mesh.html
