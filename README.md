# 🚗 Smart Car Parking Slot Detection using OpenCV & Python
   

## 📘 Overview
This project automatically detects **empty and occupied parking spaces** in a parking area using **OpenCV and Python**.  
It analyzes each frame of a video feed (or webcam) and displays:

- 🟩 **Green boxes** → Empty slots  
- 🟥 **Red boxes** → Occupied slots  

💡 The system helps reduce time spent finding parking spaces and can be extended to **real-time smart parking management systems**.

---

## 🧠 Features
✔️ Real-time car detection in parking slots  
✔️ Works on both **video feed** and **live webcam**  
✔️ Displays total number of available slots  
✔️ Easy to extend for **IoT** or **ML** integration  

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| 🐍 Python 3.x | Programming language |
| 📷 OpenCV | Image processing and computer vision |
| 🔢 NumPy | Matrix and numerical operations |
| 🧩 CvZone | Easy drawing and tracking functions |
| 🖥️ Anaconda / VS Code | Development environment |

---

## ⚙️ Installation & Setup

### 🪜 Step 1: Clone this repository
```bash
git clone https://github.com/Rishav-sh/CarPark-Detection.git
cd CarPark-Detection
```
### 🪜 Step 2: Install dependencies
```bash
pip install opencv-python numpy cvzone
```
### 🪜 Step 3: Mark Parking Spaces
```bash
python ParkingSpacePicker.py
```
🖱 Left click → Add parking box
🖱 Right click → Remove parking box

### 🪜 Step 4: Run main detection
```bash
python main.py
```
Press q to exit the video window.
### 🪜 Step 5 (Optional): Run with Webcam
Open main.py and replace:
```bash
cap = cv2.VideoCapture('carPark.mp4')
```
with:
```bash
cap = cv2.VideoCapture(0)
```
## 🎥 Project Output

| Empty Slots | Occupied Slots |
|--------------|----------------|
| 🟩 Green box | 🟥 Red box |

🖼️ **Add your project screenshot below:**  

## 🔮 Future Improvements

Add Machine Learning model for vehicle type detection

Create Flask dashboard for live slot monitoring

Integrate with IoT sensors for real-time data updates

Store occupancy history for Data Science analysis

## 📊 Data Science Integration Ideas

Once you collect slot usage data:

Predict peak parking hours ⏰

Analyze usage trends over days/weeks 📈

Optimize pricing based on demand 💰

Build time series prediction model (ARIMA / LSTM) for parking flow

## 👨‍💻 Author
**Rishav Kumar**  
B.Tech in Computer Science (3rd Year)  
📍 India  
💬 Passionate about Data Science, AI & Computer Vision  
🔗 [GitHub Profile](https://github.com/Rishav-sh)


## 🪪 License
This project is licensed under the **MIT License** – you are free to use and modify it.

---

<p align="center">⭐ Star this repo if you found it helpful!</p>


