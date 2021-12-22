# Hand Gesture Volume Controller
- ✋ Hand recognition
- 👆 Finger recognition
- 🔊 you can decrease and increase volume

# Code
Firstly I have created a Module "HandTrackingModule.py", this file contains the code which detects our hand, in this file I have created functions for specific tasks in a "class handDetector()". Short description of functions are -

    findHands() - This function detect hands and show landmarks of your hand and it return image in RGB.
    findPosition() - This function finds the position of particular landmark of your hand and it returns a list containing id_of_that_landmark, x_position_of_that_landmark, y_position_of_that_landmark.

Then another file is "main.py", this file uses that HandTrackingModule and contains the code which calculate distance between thumb and first-finger and by pinching-in(decrease distance) and pinching-out(increase distance) you can decrease and increase volume of your PC/Laptop.

This project is created in Python-3 language using OpenCV, Mediapipe and Pycaw libraries.

# About Me
Full name : Abbas Ataei

Learning : Python

Gmail : AbbasAtaei.py@gmail.com

Telegram : https://t.me/Abbasataei_py

More : https://bioly.io/AbbasAtaei
