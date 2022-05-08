# Smart-India-Hackathon-2022
An AI and IoT based interactive robot and lifestyle management system for elderly care. 
- Aim:
<br>To help the elderly enjoy a greater deal of independence by aiding their day to day tasks.
<br>To facilitate better health and quality of life during old-age.
<br>To enable regular interactions with peers to drive away solitude.


### CAD
<img src="https://github.com/maanvisingh/Smart-India-Hackathon-2022/blob/main/cad.jpeg" width="200" >

### Features

- 7 inch capacitive touch screen, featuring state of the art microprocessor.
- Autonomous navigation and IOT based home automation.
- Houses a kettle, medicine cabinet and a detachable tray for carrying medicines.

### Technology Stacks

- Hector SLAM Navigation Stack
- Google Assistant Custom API 
- Dialogue flow 
- Staying connected to all devices in house via WSN 
- Home Security using SSD (Single Shot Detection)

## Object Recognition and Fall Detection
YOLO is being used for performing real time object detection. 
MediaPipe is used for pose estimation which is further being used to detect falls and informing the emergency contacts when necessary.

<img src="https://github.com/maanvisingh/Smart-India-Hackathon-2022/blob/main/Object_Recognition.jpeg" width="400" >

## Navigation
Hector SLAM is being used to process the data from the LiDAR and localising the bot in the home environment. The LiDAR values are also being used for obstacle avoidance. Certain coordinates for areas such as Kitchen, Bedroom, Living Room etc. are stored with repect to the map so that the bot can be directly instructed to reach there.

<img src="https://github.com/maanvisingh/Smart-India-Hackathon-2022/blob/main/Navigation.png" width="400" >

## Codes
- [DL Implementation](https://github.com/maanvisingh/Smart-India-Hackathon-2022/blob/main/DL_Implementation/YOLOV4_webcam_colab.ipynb.txt)
- [ROS Package](https://github.com/maanvisingh/Smart-India-Hackathon-2022/tree/main/ROS_Package)
