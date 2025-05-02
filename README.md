🧠 Object Detection

🚀 Description
Object Detection is a deep learning-based computer vision project designed to detect custom objects such as bottles, people, fruit items, and more in images or video feeds. This solution uses a combination of TensorFlow, Keras, and OpenCV, and supports real-time object detection using pre-trained or custom-trained models. It is ideal for use in retail automation, surveillance, smart fridges, or any scenario where object presence needs to be detected and tracked.


📦 Installation

🔧 Requirements

Python 3.8+

TensorFlow

Keras

NumPy

Matplotlib

OpenCV (opencv-python)

CVlib (cvlib)

HTML

Flask (for backend)


python detect.py
This script will open the webcam and begin detecting objects like bottles, persons, and fruits in real time using CVlib and OpenCV.

To run detection on an image:


bash
Copy
Edit
python detect.py --image path/to/image.jpg


🧪 Training (Optional)

If we want to train a custom model (instead of using built-in CVlib/YOLO), prepare own dataset and use Keras with TensorFlow backend. 


✨ Features

Detects custom objects (e.g. bottle, person, fruits)

Real-time webcam detection using cvlib and OpenCV

Option to train custom models with Keras + TensorFlow

Easily extendable to new classes and datasets





📬 Contact
Created by Harshita Havele – feel free to reach out or open an issue!




