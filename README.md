## Driver_drowsiness_detection
Drowsy driver detection is one of the potential applications of intelligent vehicle systems.The main approaches to drowsiness detection primarily make pre-assumptions about the relevant behavior, 
focusing on blink rate, eye closure, and yawning. These  learning-based classifiers such as Haar cascade classifier Head motion information was collected through automatic eye tracking and an accelerometer.
The system was able to predict sleep and crash episodes on a simulator with 98% accuracy across subjects.

Architecture Diagram :

![image ](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/3a6f1e03-dba0-4e59-adfa-6f20b9943733)

Requirements:

  HARDWARE REQUIRMENTS

      1.Camera

	    2.Personal computer

  SOFTWARE REQUIREMENTS:

	  Python 2.7 or above versions
   
ALGORITHM:

  Haar Cascade classifier Algorithm
    
    Haar Cascade is a machine learning (also in deep learning) object detection algorithm used to identify objects in an image or video and based on the concept of ​​ features proposed
     Paul Viola and Michael Jones
     
  The algorithm has four stages:
        
    1.Haar Feature Selection
    2.Creating integral images
    3.Adaboost training
    4.Cascading Classifiers

Haar Feature Selection:

![image](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/13bf80fd-40aa-4f93-a59e-99b28135a0f3)

Cascade Classifier 
   
![image](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/df47c082-15d4-40ed-b60c-ec0c2225f44a)

activity Diagram:

![image](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/4442a049-19f9-4f56-8822-74b6dbef91c2)

MODEL OUTPUT:

  ![image](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/d6126bdf-5505-46f6-b3d7-b2062d577fcd)

Camera capture the blinking of eyes  then  Drowsiness Alert Message in audio.Based upon the conditions of activities are connected,
accurecy <5 alert (or) >5 no alert  on blink rate.

  ![image](https://github.com/dileepsahoo/driver_drowsiness_detection/assets/140527606/115c7d21-e07c-4577-984b-ea873650f6fa)

1.The driver abnormality monitoring system developed is capable of detecting drowsiness, drunken and reckless behaviours of driver in a short time. 

2.The Drowsiness Detection System developed based on eye closure of the driver can differentiate normal eye blink and drowsiness and detect the drowsiness
while driving.

3.The proposed system can prevent the accidents due to the sleepiness while driving. 

4.The system works well even in case of drivers wearing spectacles and even under low light conditions if the camera delivers better output.



