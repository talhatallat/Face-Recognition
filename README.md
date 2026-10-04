# Face-Recognition

### **Project Description:**

Facial recognition is a computer vision technology used to detect, identify, or verify individuals from images, videos, or live camera feeds. The system analyses facial features and compares them with stored facial data to determine whether an individual can be recognised.

The project consists of two main components:
* <b>Face Detection</b> – detecting human faces
* <b>Face Recognition</b> – identifying individuals

The system is primarily designed for **security, surveillance, and identity verification**, with potential applications in areas such as **access control, workplace security, residential security, retail, healthcare facilities, and smart-building systems**.

For example, the system could be integrated into an **automated access-control system**, where a camera detects a person and compares their facial features against authorised user data stored in a database. If a match is identified, the system could trigger an appropriate action, such as granting access or recording the event.

The project focuses on the **core facial recognition process**, including facial data collection, detection, database storage, model training, identification, and real-time testing. Rather than developing a complete commercial security solution, the project demonstrates and evaluates the underlying technology and its potential for real-world security applications.


### **Project Aim:**

Develop a real-time facial detection and recognition system for security and surveillance, capable of detecting, and recognising human faces using a live camera or images.


The project is divided into several different objectives parts that are required to complete this project.

##### Face Detection:
1. Capture live video stream.
2. Detect faces from live camera feeds or images.

##### Face Recognition:
1. Capture live video from a camera.
2. Detect faces using OpenCV and Haar-Cascade.
3. Create a database to collect, store, and assign unique IDs to facial data.
4. Train a classifier to recognize individuals.
5. Test the system using images and live camera feeds.
6. Optimise the system's recognition reliability.


The chosen solution requires the use of Anaconda, Python, OpenCV and HaarCascade to be able to process the image or video for recognizing a face. 
Also, a camera is required to discover & identify the face features over live video. 
Importantly OpenCV was a huge step to this project since it uses machine learning algorithms to search and identify faces within a picture.

**Block diagram of Face Recognition:**

![image](https://user-images.githubusercontent.com/73076876/135737701-5cc8bf77-1841-4fa8-b466-51233052b1df.png)

**Face Recognized:**

![image](https://user-images.githubusercontent.com/73076876/135737723-7176f8bd-db54-475b-b610-18a2b5edd6df.png)
