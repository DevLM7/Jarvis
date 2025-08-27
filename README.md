# 🤖 Jarvis – AI Voice Assistant with GUI

Jarvis is a Python-based **AI voice assistant** with a modern **PyQt5 graphical user interface (GUI)**. It combines **speech recognition**, **text-to-speech**, and multiple APIs to help you automate daily tasks hands-free. Inspired by Iron Man’s Jarvis, this project allows you to interact with your computer naturally using voice commands.

---

## ✨ Features

* 🎙 **Voice Interaction** – Wake Jarvis with your voice and give natural commands.
* 🔎 **Information Search** – Search Wikipedia and Google via voice.
* 📺 **Entertainment** – Open YouTube, play music, tell jokes.
* 📂 **System Control** – Open Command Prompt, switch windows, launch apps.
* 📸 **Utilities** – Take screenshots, read PDFs, open camera, tell the time/date.
* 📰 **News Updates** – Fetches the latest tech news from NewsAPI.
* 📍 **Location Awareness** – Tells your current city/country using IP-based geolocation.
* 📧 **Email & Messaging** – Send emails with attachments, schedule WhatsApp messages.
* 📷 **Social Media** – Open Instagram profiles and optionally download profile pictures.
* 🖥 **GUI Interface** – Interactive PyQt5 GUI with animated visuals, live time/date, and control buttons.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **PyQt5** – GUI framework
* **pyttsx3** – Text-to-speech
* **SpeechRecognition** – Voice input
* **wikipedia, webbrowser, requests** – Search and APIs
* **cv2 (OpenCV)** – Camera access
* **pywhatkit, pyautogui** – Automation and messaging
* **smtplib & email.mime** – Email sending
* **PyPDF2** – PDF reading
* **instadownloader** – Instagram profile media

---

## 🚀 How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/jarvis-assistant.git
   cd jarvis-assistant
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**

   ```bash
   python jarvis.py
   ```

4. The **PyQt5 GUI** will open. Click the **Run button** 🎛 to start voice recognition.

---

## 📋 Example Voice Commands

* “Open YouTube”
* “Search Wikipedia for Artificial Intelligence”
* “What’s the time?”
* “Open a PDF”
* “Send a mail”
* “Play music”
* “Where am I?”
* “Take a screenshot”
* “Close yourself”

---

## 🔮 Future Enhancements

* Add wake word detection (“Hey Jarvis”).
* Integrate ChatGPT or other LLMs for conversational AI.
* Add calendar/task management features.
* Cross-platform support (Linux/Mac).

---

## 👨‍💻 Author

Developed by **Darshan** 🚀
Feel free to fork, improve, and contribute!

