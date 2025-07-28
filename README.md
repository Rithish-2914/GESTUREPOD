Gesture Drop

A gesture-based application for quickly transferring text and images from your computer to your mobile device using hand gestures.

Features

Copy text on your computer and send it to your phone with a closed fist gesture
Display text and images on your mobile device

Control content display using hand gestures on your mobile device

Simple web interface for both computer and mobile

How It Works

The desktop application (gesture_sender.py) monitors your webcam for hand gestures

When you make a closed fist gesture, it sends the content of your clipboard to the server

Open the web interface on your mobile device to see the transferred content

Use different hand gestures on your mobile to control what content is displayed:

Open palm: Show both text and image

Thumbs up with fingers down: Show image only

Requirements

Python 3.x

Webcam on your computer

Modern mobile browser with camera access

Installation

Clone the repository:

git clone 

cd gesture-drop

Install the required packages:


pip install -r requirements.txt

Run the server:

python server.py

In a separate terminal, run the gesture detection app:


python gesture_sender.py

Open your browser on your mobile device and navigate to your computer's IP address on port 5000 (e.g., http://192.168.1.100:5000)


Usage

Copy text on your computer

Make a closed fist gesture in front of your webcam

The text will be transferred to your phone

To send images, visit http://your-ip:5000/upload on your computer and upload an image

Use hand gestures on your phone to control the display
License
This project is licensed under the MIT License - see the LICENSE file for details.# GESTUREPOD
