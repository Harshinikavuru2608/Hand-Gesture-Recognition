# HAND GESTURE RECOGNITION
## Objective:
1) Apply motion detection and background subtraction as a precursor to gesture  recognition.
2) Segment the hand and finger regions from an image using motion detection.
3) Use the Malima et al. method for hand gesture recognition in real-time video streams.
4) Build a computer vision system that can add two numbers together based on  our hand gestures.

## Input methods:
In order to perform gesture recognition, we first need to define a method of data input. While much research has been performed in video and image based hand gesture recognition, there are additional tools that can be used to increase detection accuracy.
Some of them are:
1) Wired Gloves
2) stereo and depth-aware cameras
3) controller-based gestures
4) single camera

## Types of gesture recognition algorithms:
1) 3D models
2) Skeletal-based models
3) Appearance-based models.

## Block diagram:
<img width="402" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/1e646417-012d-4c19-8c2b-56d0df83bf55">

## Firmware Development:
Inside the gesture_recognition sub-module of image, we’ll define two files: gesturedetector.py and motiondetector.py, used to handle gesture recognition and background subtraction, respectively. 
In this part of the project, we’ll be focusing on implementing motiondetector.py, while our next lesson will review how to define our hand gesture recognizer. 
We’ll also define two driver scripts, detect.py , which will be an example Python script on how to use our simple motion detector, followed by recognize.py, which will glue together both motiondetector.py  and gesturedetector.py  to form our complete hand gesture recognition pipeline.
<img width="309" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/aa6254e4-9ef7-4508-91e1-317b21dbcab2">

## Output of Segmentation:
<img width="385" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/07229dd5-8a8e-4458-9832-809e020a59ef">

<img width="360" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/e229a263-50f4-44b9-a784-2b69581fe066">

## Outputs:
<img width="452" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/3039e47f-d52c-4a0b-ab72-376a5dac4fda">
<img width="453" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/6e9f3f22-8b08-4c18-b91c-d79727095044">
<img width="452" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/3724d892-4c05-4f52-8b1c-4f07bcb385ec">
<img width="452" alt="image" src="https://github.com/Harshinikavuru2608/Hand-Gesture-Recognition/assets/125713954/13ef0bc0-1720-49af-b447-164f8866ca3f">







