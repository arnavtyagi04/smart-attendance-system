
# Smart Attendance System 🎯

Face Recognition based Smart Attendance System built using **Python** and **Streamlit**.

This project uses real-time face recognition to automatically mark attendance, making the process fast, accurate, and contactless.

---

## 🚀 Features
- Real-time face detection using webcam
- Face recognition using pre-stored images
- Automatic attendance logging with timestamp
- Streamlit-based interactive UI
- Easy to extend for classrooms or offices

---

## 🧠 Tech Stack
- Python
- OpenCV
- face_recognition
- Streamlit
- NumPy
- Pandas

---

## 📁 Project Structure

smart-attendance-system/
│
├── app.py # Streamlit UI
├── smart_attendance_system.py # Core face recognition logic
├── data/
│ └── known_faces/ # Images of registered users
├── output/
│ └── attendance.csv # Attendance records
├── requirements.txt
└── README.md

## ▶️ How to Run

1. Clone the repository

git clone https://github.com/arnavtyagi04/smart-attendance-system.git
cd smart-attendance-system

2.Install dependencies
pip install -r requirements.txt

3.Run the application
streamlit run app.py

📸 How It Works

Add clear face images inside data/known_faces/

Click Start Attendance on the Streamlit app

The system recognizes faces and marks attendance automatically

📌 Use Cases

-->College / School attendance

-->Office employee attendance

-->Event entry tracking

👨‍💻 Author

Arnav Tyagi
B.Tech CSE | Machine Learning Enthusiast
📍 New Delhi, India
