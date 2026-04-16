# 🚗 AI-Powered Safety & Mobility System

## 📌 Overview

This project is an **AI-based Safety & Mobility Web Application** designed to reduce road accidents and improve driving safety using real-time monitoring, smart navigation, and alert systems.

The system integrates **computer vision, mapping services, and web technologies** to provide a complete driver assistance solution.

---

## 🎯 Problem Statement

Road accidents are often caused by:

* Driver drowsiness 😴
* Distraction 📱
* Delayed emergency response 🚑

Existing systems lack **real-time monitoring and intelligent alerts**, leading to increased risks.

---

## 💡 Solution

Our system provides:

* Real-time **driver drowsiness detection**
* **Smart navigation** with route visualization
* **Accident-prone area heatmaps**
* **Emergency alert system**

---

## 🚀 Features

### 👁️ Driver Monitoring (AI)

* Real-time detection using **YOLOv8 + OpenCV**
* Detects:

  * Drowsiness
  * Yawning
  * Distraction
* Instant alerts when unsafe behavior is detected

---

### 🗺️ Smart Navigation

* Integrated with **Google Maps Platform**
* From → To route planning
* Distance and ETA display

---

### 📍 Live Location Tracking

* Uses **Geolocation API**
* Tracks user location in real time

---

### 🔥 Accident Heatmap

* Displays accident-prone areas across India
* Visualized using heatmap layers
* Helps in safer route planning

---

### 🚨 Alert System

* Visual and sound alerts for drowsiness
* Optional SMS alerts via **Twilio**

---

## 🏗️ System Architecture

Frontend → Backend → AI Model → External APIs

* **Frontend:** User Interface (HTML/CSS/JS or React)
* **Backend:** API handling (Flask/FastAPI)
* **AI Engine:** YOLOv8 + OpenCV
* **APIs:** Maps, Location, Alerts

---

## 📂 Project Structure

```
project/
│
├── frontend/
│   ├── pages/
│   ├── components/
│   └── index.html / App.js
│
├── backend/
│   ├── app.py
│   ├── routes/
│   ├── services/
│
├── models/
│   └── yolov8.pt
│
├── utils/
├── requirements.txt
└── README.md
```

---

## ⚙️ Tech Stack

### Frontend

* HTML, CSS, JavaScript / React

### Backend

* Python (Flask / FastAPI)

### AI/ML

* YOLOv8
* OpenCV

### APIs

* Google Maps API
* Geolocation API
* Twilio API

---

## 🔧 Installation & Setup

### 1. Clone Repository

```
git clone <your-repo-link>
cd project
```

### 2. Install Backend Dependencies

```
pip install -r requirements.txt
```

### 3. Run Backend

```
python app.py
```

### 4. Run Frontend

* Open `index.html`
  OR

```
npm install
npm start
```

---

## ▶️ How to Use

1. Open the web application
2. Click **Start Camera**
3. System begins monitoring driver
4. If drowsiness detected → alert triggered
5. Enter **From → To** location for navigation
6. View accident heatmap on map

---

## 🧠 Future Enhancements

* Voice assistant integration 🎙️
* IoT-based vehicle sensors 🚗
* Cloud analytics dashboard ☁️
* AI-based safe route prediction

---

## 🌍 Impact

* Reduces road accidents
* Improves driver awareness
* Enhances emergency response
* Promotes safer mobility

---

## 🏆 Hackathon Value

* Real-time AI system
* Practical real-world application
* Scalable architecture
* Strong social impact

---

## 🤝 Contributors

* Your Name
* Team Members

---

## 📜 License

This project is for educational and hackathon purposes.

---

## ⭐ Acknowledgements

* YOLOv8 (Ultralytics)
* OpenCV
* Google Maps Platform
* Twilio API

---

## 📞 Contact

For queries or collaboration:

* Email: [your-email@example.com](mailto:your-email@example.com)

```
```
