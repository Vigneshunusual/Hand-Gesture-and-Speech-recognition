# Hand-Gesture-and-Speech-recognition

# Overview
This project combines hand gesture recognition and speech recognition to create a multimodal interface for interacting with devices. The system is designed to recognize specific hand gestures and spoken commands, allowing users to control applications or devices using natural inputs.

# Features
 1.Hand Gesture Recognition: Uses computer vision techniques to detect and recognize predefined hand gestures.
 
 2.Speech Recognition: Integrates speech-to-text capabilities to recognize voice commands.
 
 3.Multimodal Interaction: Combines both hand gestures and voice commands for more intuitive control.
 
 4.Real-time Processing: The system processes inputs in real-time, providing immediate feedback and response.

 # Demo

 Application view of Speech Module
 
 ![speech to text using python](https://github.com/user-attachments/assets/72c8f836-a57f-48b6-a747-d877fa9bd436)
 
 Speech and Gesture Recognition
 
 ![speech and gesture recognition](https://github.com/user-attachments/assets/1fd0ca91-2406-4597-bf31-b096cd5b557c)

Recognition Of Mouse

![recognising the mouse](https://github.com/user-attachments/assets/76a7d4d5-cec6-4e20-acd6-a5118a536eec)

Movement Of Mouse

![movement of mouse](https://github.com/user-attachments/assets/c68c2719-a2c2-49d3-8735-83d9db82d8fa)

Zoom In and Zoom Out

![zoom in and zoom out](https://github.com/user-attachments/assets/2596c334-be87-4c1b-b4b4-6ee50cc9ed7a)

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







