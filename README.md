# Attendance System Using Facial Recognition

## Overview
This project is a **Face Recognition-Based Attendance System**, developed as a final year engineering project. It uses real-time facial recognition to automatically mark attendance, making the process efficient and secure by preventing proxy attendance.

## Features
- Real-time face detection and recognition
- Auto-marking of attendance with CSV logging
- User interface built with HTML, CSS, and Python (Flask)
- Face image storage for training
- Pre-trained model using face encodings
- Attendance report generation (CSV)

## Technologies Used
- **Python**
- **OpenCV** – Face detection
- **face_recognition** – Face encoding & comparison
- **Flask** – Web framework
- **HTML/CSS** – Front-end interface
- **SQLite / CSV** – Attendance storage
- **Haarcascade** – Face detection model

## Folder Structure

face-recognition-based-attendance-system-master/ │ ├── app.py                     # Main Flask app ├── haarcascade_frontalface_default.xml ├── static/ │   ├── faces/                 # Stored face images │   ├── styles.css             # Frontend styling │   └── face_recognition_model.pkl ├── Attendance/                # Attendance CSV files ├── README.md └── ss.png                     # Screenshot

## How to Run (Once You Have a PC)
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/attendance-system

2. Navigate to the folder:

cd attendance-system


3. Install dependencies:

pip install -r requirements.txt


4. Run the app:

python app.py


5. Open http://127.0.0.1:5000/ in your browser.






Author

[Abhishek Ananta Gadmale]

LinkedIn: [https://www.linkedin.com/in/abhishek-gadmale-1309b8353?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app]

Email: [agadmale335@gmail.com]
