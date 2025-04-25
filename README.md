# 📸 Attendance Recognition System

This project is an **AI-powered Attendance Recognition System** built using **Python**. It leverages facial recognition to automatically mark attendance of individuals in real-time. The system is ideal for educational institutions, offices, or secure access areas where seamless and contactless attendance tracking is required.

---

## 🔧 Tech Stack

- **Python 3**
- **OpenCV** – for real-time image processing
- **face_recognition** – for detecting and recognizing faces
- **dlib** – for facial feature encoding
- **Tkinter** – for building the frontend GUI
- **PIL (Pillow)** – for image handling
- **NumPy** – for numerical operations
- **CSV/Excel** – for attendance logging

---

## 🧠 Features

- Real-time face detection and recognition
- Auto attendance marking with timestamps
- User-friendly GUI built using Python Tkinter
- Stores attendance in CSV/Excel format
- Easy-to-add new faces to the database
- Displays recognized names and confirmation messages

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/attendance-recognition-system.git
   cd attendance-recognition-system
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Add known face images

Place images of known individuals in the images/ folder.

Filenames should match the person's name (e.g., John_Doe.jpg).

Run the application

bash
Copy
Edit
python main.py
📂 Project Structure
graphql
Copy
Edit
attendance-recognition-system/
│
├── images/                # Folder for known face images
├── attendance.csv         # Auto-generated attendance file
├── main.py                # Main Python script
├── gui.py                 # GUI layout and controls
├── face_recog.py          # Face recognition logic
├── utils.py               # Helper functions
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
📸 Sample UI
(You can add a screenshot here)

📌 Future Improvements
Add support for mask detection

Integrate with cloud-based database

Admin panel for attendance records management

SMS/email alerts on recognition

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.












