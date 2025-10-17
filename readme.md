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

---

## ⚙️ How It Works
1. Load known employee faces from `employee_images/`
2. Encode each face using `face_recognition`
3. Process video frames with YOLOv8n-Face for face detection
4. Match detected faces with known encodings
5. Mark recognized faces in `Attendance_C3.csv`
6. Save processed frames with bounding boxes and names

---

## 🧪 Example Output
✅ **Recognized Faces** — green bounding boxes  
❌ **Unknown Faces** — red bounding boxes  

Each detection result is saved in the output folder:

