# Face_Recognition_System


This project is a Python-based attendance system that uses facial recognition to automatically mark attendance in real-time using a webcam.

## 🚀 Features

- Real-time face detection and recognition
- Marks attendance with timestamp and date
- Stores data in a CSV file
- Uses OpenCV for video capture
- Simple and easy-to-use interface

## 🛠️ Technologies Used

- Python
- OpenCV
- face_recognition library
- CSV module

## 📂 Project Structure

face-attendance/
├── images/ # Folder with known faces
├── attendance.csv # Attendance records
├── main.py # Main program
├── README.md # Project description

 

## 🧑‍💻 How It Works

1. Store known faces in the `images/` folder.
2. Run `main.py`.
3. Webcam will open and detect faces in real-time.
4. If a face matches, it marks attendance in `attendance.csv`.

## 📦 Installation

```bash
git clone https://github.com/Mayank417/face-attendance.git
cd face-attendance
pip install opencv-python face_recognition
python main.py
