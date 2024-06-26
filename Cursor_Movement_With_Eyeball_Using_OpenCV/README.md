EyeBall Cursor Control
EyeBall Cursor Control is a Python application designed for hands-free control of the computer cursor using real-time eye tracking. It utilizes computer vision techniques to track eye movements through a webcam and translates them into mouse cursor movements on the screen. The application also includes blink detection to simulate mouse clicks or other predefined actions.


Features
Real-time Eye Tracking: Tracks user's eye movements in real-time using webcam input.
Cursor Movement: Moves the computer cursor based on the direction of the user's gaze.
Blink Detection: Detects user blinks to trigger mouse clicks or other actions.
Adjustable Sensitivity: Allows users to adjust sensitivity settings for precise cursor control.
Cross-Platform Compatibility: Works on multiple operating systems with Python and required dependencies.
 
Step 1:Installation:
Clone the repository:
git clone https://github.com/Nikhitha_opensource/Cursor_Movement_With_Eyeball_Using_OpenCV.git

cd Cursor_Movement_With_Eyeball_Using_OpenCV

Step 2: Install dependencies:
pip install -r requirements.txt

Step 3: Run the application:
streamlit run app.py

NOTE: To get better results make sure to run in virtual Environment

Working: 
1.Position your face in front of the webcam.

2.Use your gaze to control the mouse cursor on the screen.

3.Blink to simulate mouse clicks or perform other predefined actions.

Dependencies
opencv-python: For computer vision tasks.
mediapipe: For face mesh and landmark detection.
pyautogui: For controlling the mouse cursor.
streamlit: For creating the web interface.
streamlit-webrtc: For integrating webcam input in Streamlit.

Contributing:
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.