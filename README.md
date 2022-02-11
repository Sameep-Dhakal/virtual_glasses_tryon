# virtual_glasses_tryon

repositoy contains code for facial landmark detection and using landmarks to automatically place the glasses on face. 

#### training and validation loss
![train_and_valid_loss](https://github.com/Sameep-Dhakal/virtual_glasses_tryon/blob/master/screenshots/train_screenshot.png?raw=true)

### explanation of facial landmark detection:
https://towardsdatascience.com/face-landmarks-detection-with-pytorch-4b4852f5e9c4
you can see how landmark is detected from this page above.



### For virtual-tryon:
#### plotted eye landmarks on the face by harrcascase eye landmarks:
the face image was sent and after that trained model was used to predict the eye landmarks.

![landmarks](https://github.com/Sameep-Dhakal/virtual_glasses_tryon/blob/master/screenshots/eyes_landmark.png?raw=true)

#### plotted landmarks along with markers
min and max points were analysed and plotted markers to visualise those points on the landmarks.
![landmarks_with_markers](https://github.com/Sameep-Dhakal/virtual_glasses_tryon/blob/master/screenshots/eye_landmark_with_marker.png)

#### overlaying with glasses
after min and max points of eyes detection glasses were overlayed on face with some corrections on positions
![glasses_overlay](https://github.com/Sameep-Dhakal/virtual_glasses_tryon/blob/master/screenshots/eye_with_glasses.png?raw=true)


overall basic implementation the project is also explained in code itself, about the use of some basic functions .

Future works:
1. try on real time image and video.
2. Better adjustment of glasses on face.
3. use of better algorithm for face detection.






 
