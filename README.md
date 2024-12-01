# Face Detection and Recognition Using OpenCV in Python

This project demonstrates a face detection and recognition system using OpenCV in Python. It employs advanced computer vision techniques to identify and recognize faces in images or live video streams.

## Features
- Detects faces in images or videos using Haar cascades.
- Recognizes faces using pre-trained models.
- Real-time face recognition from webcam or video feed.
- Easy-to-use interface and customizable settings.

## Installation
Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/jyoti112421/Face_recognition.git
   cd Face_recognition/face/Face-Detection-Recognition-Using-OpenCV-in-Python
Install the required Python packages:
pip install -r requirements.txt
Ensure you have OpenCV installed. If not, install it:
pip install opencv-python opencv-contrib-python
Usage
Run the Face Detection Script
To detect faces in an image:

bash
Copy code
python face_detection.py
Run the Face Recognition Script
For real-time face recognition:

bash
Copy code
python face_recognition.py
Customizing Input

Modify the script to use a specific image or video file.
Change the parameters in the script to adjust detection settings (e.g., scale factor, min neighbors).
Project Structure
face_detection.py: Detects faces in an image or video.
face_recognition.py: Recognizes and labels detected faces.
requirements.txt: Contains the list of dependencies.
haarcascade_frontalface_default.xml: Pre-trained Haar cascade model for face detection.
Screenshots
Include screenshots of your system detecting and recognizing faces. Replace this text with images using the format:

markdown
Copy code
![Face Detection Example](path_to_image)
Dependencies
Python 3.7 or higher
OpenCV
NumPy
Other libraries as mentioned in requirements.txt
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Make your changes and commit:
bash
Copy code
git commit -m "Added a new feature"
Push the changes:
bash
Copy code
git push origin feature-name
Open a pull request.
