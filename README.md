# Real-Time-Vision-Proctoring

Real time automated vision proctoring using Computer Vision and Machine Learning.

## Using MediaPipe Framework
MediaPipe ML pipeline consists of two real-time deep neural network models that work together: A detector that operates on the full image and computes face locations and a 3D face landmark model that operates on those locations and predicts the approximate 3D surface via regression. 
It allows the network to dedicate most of its capacity towards coordinate prediction accuracy.
Each landmark consists of the following:
x and y: Landmark coordinates normalized to [0.0, 1.0] by the image width and height respectively.
z: Distance between the camera and the user
visibility: A value in [0.0, 1.0] indicating the likelihood of the landmark being visible (present and not occluded) in the image.

## Proposed Methodology

FACE AND HAND DETECTION 

FACIAL AND HAND LANDMARK DETECTION

CAPTURE THE COORDINATES OF 3D SURFACE AND GENERATE A CSV DATA

TRAINING AND TESTING OF THE DATASET GENERATED


## Pros of the prosposed system
Real-time
No need of huge dataset
Fully automated
Because of MediaPipe no need for common data augmentations like affine transformations consisting of rotations, translation.


## Cons of the prosposed system
Due to small dataset , it leads to overfitting
We aren’t taking any measures for audio related cheating.

## Future Work
We have proposed and implemented an automated proctoring system using computer vision and MediaPipe. This study demonstrates how to avoid cheating in online examinations by employing real time proctoring based on vision capabilities.
 
Add a vision-based function called facial recognition, which will ensure that no one else can take the candidate's place and administer the test in the middle.

Detect multiple faces into a frame.

Develop audio based proctoring system.

## Results




