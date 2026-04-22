 🚀 AI-Based Augmented Reality System using YOLO

📌 Overview

This project is an "AI-powered Augmented Reality (AR) system" designed to enhance road safety by detecting objects, traffic signs, and lanes in real-time.
The system uses **YOLO (You Only Look Once)** for fast object detection and integrates "computer vision + AR overlay + voice alerts" to provide real-time assistance to users (drivers).

🎯 Problem Statement

Road accidents often occur due to:

* Lack of real-time awareness
* Delayed reaction to obstacles or traffic signs
* Poor visibility of lanes and surroundings

This project aims to assist drivers by providing intelligent real-time alerts using AI and AR technologies.

💡 Solution
The system captures live video input and processes it using deep learning and image processing techniques to:

* Detect objects (vehicles, pedestrians, etc.)
* Recognize traffic signs
* Identify road lanes
* Overlay information on screen (AR)
* Generate voice alerts for safety
* 
 ✨ Key Features

* 🔍 **Real-time Object Detection** using YOLO
* 🚦 **Traffic Sign Recognition** using Haar Cascade
* 🛣️ **Lane Detection** using OpenCV techniques
* 🧠 **Augmented Reality Overlay** for visual feedback
* 🔊 **Voice Alerts (Text-to-Speech)** for warnings
* 💻 **GUI Interface** using CustomTkinter

 🛠️ Technologies Used

| Technology    | Purpose                           |
| ------------- | --------------------------------- |
| Python        | Core programming                  |
| OpenCV        | Image processing & video handling |
| YOLO (v3/v8)  | Object detection                  |
| NumPy         | Numerical operations              |
| CustomTkinter | GUI development                   |
| pyttsx3       | Voice alerts                      |

🧠 System Architecture

1. Capture video input (camera/video file)
2. Process frames using OpenCV
3. Apply YOLO for object detection
4. Detect lanes using edge detection techniques
5. Recognize traffic signs using Haar Cascade
6. Overlay results (AR visualization)
7. Generate voice alerts
📂 Project Structure

AR-project
│── Home.py                  # Main application file
│── requirements.txt        # Dependencies
│── coco.names              # YOLO class labels
│── yolov3.cfg              # YOLO configuration
│── haarcascade_stop.xml    # Stop sign detection
│── haarcascade_trafficsigns2.xml
│── back.png                # UI background

 ▶️ Installation & Setup
 1. Clone Repository
git clone https://github.com/Sakshi1628/AR-project.git
cd AR-project
 2. Install Dependencies
pip install -r requirements.txt
3. Run the Project
python Home.py

📸 Output / Results

* Real-time detection of objects on road
* Lane marking visualization
* Traffic sign identification
* Voice-based alerts for detected objects

1. Object Detection (YOLO)
 <img width="730" height="387" alt="image" src="https://github.com/user-attachments/assets/aecf58d9-f687-431a-a4ec-e17196d3e3ab" />
 <img width="1032" height="829" alt="image" src="https://github.com/user-attachments/assets/bf2a122d-7345-4a76-b6fe-537bb14da07c" />

2. Traffic Sign Detection
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/69f06442-64a4-40ed-ab92-979e741394fd" />
<img width="471" height="470" alt="image" src="https://github.com/user-attachments/assets/99b79e23-edd4-495d-af27-db10064cdefc" />

3. Lane Detection
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/48608b25-8909-4344-acac-67c012730bc7" />
<img width="800" height="502" alt="image" src="https://github.com/user-attachments/assets/9baba55d-c464-488c-8e5d-c2624e6a340d" />

4. AR Overlay Output
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/c2d032f6-c6d6-4b45-bf67-59a7123ddf19" />
<img width="1070" height="601" alt="image" src="https://github.com/user-attachments/assets/d6eac993-94d1-4d3c-a0d3-48ef52104d5a" />

 🎯 Applications

* 🚗 Driver Assistance Systems
* 🚦 Smart Traffic Monitoring
* 🛣️ Road Safety Enhancement
* 🤖 Autonomous Vehicle Support

⚠️ Challenges Faced

* Handling large YOLO model files
* Optimizing real-time performance
* Integrating multiple detection modules
* Managing GitHub file size limitations

🔮 Future Enhancements

* Integration with live camera feed (webcam/mobile)
* Use of advanced YOLO versions (YOLOv8)
* Cloud-based processing
* Mobile application deployment
* GPS-based alerts

 👩‍💻 Author
Sakshi

⭐ Acknowledgement

This project is developed for academic and learning purposes in the field of **AI, Computer Vision, and Augmented Reality**.

📌 GitHub Repository

👉 https://github.com/Sakshi1628/AR-project

 🙌 Support

If you like this project, give it a ⭐ and share it!
