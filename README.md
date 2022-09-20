# Face-Recognition-Auto-Scroller

Requirements:
You can install all dependencies by running this line of code below:
```
pip install opencv-python mediapipe numpy time pyautogui
```

The code uses mediapipe's face recognition model to detect facial landmarks, and after detection pyautogui does automated keypresses to manage scrolling up and down any document.

Steps:
1. Install all the dependencies.
2. Run the AutoScroller.py script.
3. Put the website/pdf/file that you want to scroll on in the foreground.
4. Now whenever you look up or down, it scrolls in that direction.
5. When you want to exit, switch to the OpenCV tab where you can see your face, and press the Esc key on the keyboard.

Cheers!
