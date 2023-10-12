# Computer_Vision-Face_Detection

![image](https://github.com/ChidimmaIdika/Computer_Vision-Face_Detection/assets/137975543/93d0aea3-8c5f-48f1-bc45-befb9e9a216e)


## Face Detection using OpenCV

## Table of Contents
1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [How to Use](#how-to-use)
4. [Implementation Details](#implementation-details)
5. [Sample Output](#sample-output)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Author](#author)
9. [Contact](#contact)


## Overview
This project demonstrates real-time face detection using Python and the OpenCV library.    
I leveraged Haar-cascade classifiers to detect faces in a webcam feed and draw rectangles around them.

## Prerequisites
Before running the code, ensure you have the following dependencies installed:

- Python (>=3.6)
- OpenCV (4.8.1.78 or higher)
- NumPy (>=1.19.3)

You can install OpenCV and NumPy using pip:   
!pip install opencv-python   
!pip install numpy

## How to Use
1. Clone this repository:    
git clone https://github.com/ChidimmaIdika/Computer_Vision-Face_Detection.git
cd face-detection
2. Run the face_detection.py script:   
   python face_detection.py
3. Press the 'q' key to exit the webcam feed.

## Implementation Details
The key components of this project are as follows:

- I used Haar-cascade classifiers provided by OpenCV to detect frontal faces.   
- The detect function takes the grayscale image and the original frame and returns the frame with rectangles drawn around detected faces.

## Sample Output
![image](https://github.com/ChidimmaIdika/Computer_Vision-Face_Detection/assets/137975543/0ea70ac0-31cf-4307-a67d-be684dfb613a)
![FD](https://github.com/ChidimmaIdika/Computer_Vision-Face_Detection/assets/137975543/da5d103f-b5fa-4c7a-bfb6-213ef1ffca17)


## License
This project is licensed under the MIT License.

## Acknowledgments
- [OpenCV](https://github.com/opencv/opencv/tree/4.x/data/haarcascades) for providing the Haar-cascade classifiers.
- [10Alytics](https://github.com/10Alytics)

## Author
[Chidimma Idika](https://github.com/ChidimmaIdika)

## Contact
For any inquiries or suggestions, please [send me an email](chidimmaidika@gmail.com).
