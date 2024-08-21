# Hand-Gesture-and-Speech-recognition

# Overview
This project combines hand gesture recognition and speech recognition to create a multimodal interface for interacting with devices. The system is designed to recognize specific hand gestures and spoken commands, allowing users to control applications or devices using natural inputs.

# Features
 1.Hand Gesture Recognition: Uses computer vision techniques to detect and recognize predefined hand gestures.
 2.Speech Recognition: Integrates speech-to-text capabilities to recognize voice commands.
 3.Multimodal Interaction: Combines both hand gestures and voice commands for more intuitive control.
 4.Real-time Processing: The system processes inputs in real-time, providing immediate feedback and response.

 # Demo
 

# Installation
# Prerequisites
 1.Python 3.7 or higher
 2.Required Python libraries (listed in requirements.txt or see below)
 3.A webcam for gesture recognition
 4.A microphone for speech recognition

# Setup
 # 1.Install the required packages:
    pip install opencv-python
    pip install numpy
    pip install mediapipe
    pip install speechrecognition
    pip install pyaudio
 # 2.Run the application:
    python app.py
# Usage
 1.Gesture Control: Place your hand in front of the webcam. The system will recognize specific gestures and map them to predefined actions.
 2.Voice Commands: Use the microphone to issue voice commands. The system will process the command and execute the corresponding action.

# Project Structure

 1.app.py: Main application file that integrates hand gesture and speech recognition.
 2.Gesture_Controller.py: Handles the logic for recognizing hand gestures using a webcam.
 3.Gesture_Controller_Gloved.py: A variant that supports gesture recognition for gloved hands.
 4.jquery.convform.css: Styling for the web interface (if applicable).







