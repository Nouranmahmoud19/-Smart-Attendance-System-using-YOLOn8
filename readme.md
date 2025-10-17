# 🎯 Smart Attendance System using YOLOv8 and Face Recognition

This project is an **AI-based attendance system** that automatically detects and recognizes employees' faces from video footage or live camera streams using **YOLOv8** and **Face Recognition**.  
The system logs attendance with timestamps in real time and saves processed frames with bounding boxes.

---

## 🚀 Features
- 🧠 **YOLOv8n-Face** for high-speed face detection  
- 🤖 **Face Recognition** for identifying known employees  
- ⚡ **Hybrid detection pipeline** — fallback to general YOLO model if no face detected  
- 🕒 **Automatic attendance logging** with name, time, and date  
- 💾 Saves processed images with bounding boxes and names  
- 🔥 GPU support for maximum speed (CUDA compatible)  
- 🧩 Adjustable frame skipping to balance accuracy and performance  

---

## 🧰 Technologies Used
- **Python 3.10+**
- **YOLOv8** (`ultralytics`)
- **face_recognition**
- **OpenCV**
- **NumPy**
- **PyTorch**
- **tqdm**

---

## 🏗️ Project Structure
