# SnapClass Frontend

Welcome to the frontend repository for **SnapClass** – the AI Powered Attendance System. 

SnapClass revolutionizes the classroom with next-gen computer vision and voice biometrics, trusted by educators for speed, accuracy, and security.

## Features

- **AI Face Analysis**: Advanced neural networks recognize every student's face from a single class photo.
- **Sequential Voice ID**: Matches voice biometrics against stored embeddings in real-time.
- **QR-Driven Roster**: Course codes generate unique QR codes for instant student enrollment.
- **Teacher & Student Journeys**: Interactive dashboards, fast enrollments, and actionable records.

## Tech Stack (Overall System)

- **Platform**: Streamlit & Flask
- **Vision AI**: FaceRecognition and Dlib
- **Audio AI**: Resemblyzer and Librosa
- **Storage**: Supabase Cloud

## Running the Landing Page

This repository contains the Flask-based landing page.

1. Clone the repository
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and navigate to `http://localhost:5002`

*Note: The main AI application runs on Streamlit and should be started separately on port 8501 for the "Start AI Attendance" links to work.*
