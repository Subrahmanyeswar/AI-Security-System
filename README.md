# 🛡️ Real-Time AI Security System  

An AI-powered real-time security system that detects **faces, objects, and unauthorized access** using **YOLOv8 + DeepFace**.  
When an intruder or unknown object is detected, the system raises an **alarm** and records video evidence automatically.  

---

## 🚀 Features
- 🔍 Real-time face recognition (authorized vs unauthorized)  
- 🎯 Object detection with YOLOv8  
- 📹 Automatic recording of intrusions (saved in `recordings/`)  
- 🔔 Instant alarm sound for alerts  
- 🗂️ Supports multiple authorized users  

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- YOLOv8 (Ultralytics)  
- DeepFace (Face Recognition)  
- OpenCV  

---

## ⚡ How to Run
```bash
# 1. Clone the repo
git clone https://github.com/Subrahmanyeswar/AI-Security-System.git
cd AI-Security-System

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the system
python main.py
