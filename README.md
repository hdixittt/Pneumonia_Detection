# Pneumonia_Detection
# 🧠 Pneumonia Detector Dashboard

A smart AI-powered web application for detecting Pneumonia from chest X-rays with interactive features like symptom checker, chatbot, QR report sharing, and more. Built using Flask, CNN, and Gemini API.

---

## 🚀 Features

### ✅ Pneumonia Classification
- Upload chest X-rays and get real-time predictions (Positive / Negative)
- CNN-based deep learning model trained on labeled data

### ✅ Symptom Checker
- Check symptoms like fever, cough, chest pain, and fatigue before upload
- Alerts user if symptoms don’t match pneumonia criteria

### ✅ Gemini AI Chatbot
- Ask medical-related questions via an integrated chatbot
- Powered by Google Gemini API
- Voice-enabled input for better accessibility

### ✅ Downloadable Diagnosis Report
- One-click `.txt` report download after prediction

### ✅ QR Code for Report Sharing
- Generate a QR code after prediction to share the diagnosis quickly on any mobile device

### ✅ Theme Toggle
- Light/Dark theme switcher for comfort and style

### ✅ Secure Sessions
- Maintains individual chat history and predictions per session using Flask-Session

---

## 🧪 Tech Stack

**Frontend:** HTML, CSS, Bootstrap, JavaScript  
**Backend:** Flask (Python)  
**AI Model:** CNN using TensorFlow/Keras  
**Chatbot API:** Google Gemini Pro  
**Voice Recognition:** Web Speech API  
**QR Code:** Google Charts QR API

---

## 🗂️ Project Structure
/project-root │ ├── app.py # Main Flask backend ├── models/ │ └── pneu_cnn_model.h5 # Trained CNN model ├── static/ │ └── uploaded images, CSS, etc. ├── templates/ │ └── index.html # Dashboard UI └── README.md


---

## 🎯 Real-World Impact

- Makes pneumonia screening faster and accessible
- Useful in remote or under-resourced clinics
- Adds conversational AI to ease user navigation and awareness

---

## 📬 Contact

For support or queries, contact: [support@codecure.ai](mailto:support@codecure.ai)

