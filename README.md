# 🧠 Smart Assistant – Voice & Text Chatbot

## 📌 Overview
The **Smart Assistant** is an interactive **voice and text chatbot** built with **Flask** and **Socket.IO**.  
It integrates **Cohere AI** for natural language understanding and **ElevenLabs** for realistic text-to-speech synthesis.  
The assistant supports **real-time Arabic speech recognition**, text chat, and audio responses in a friendly conversational tone.

---

## ✨ Features
- 💬 Text chat with real-time AI responses.
- 🎤 Arabic **speech-to-text** with live transcription.
- 🔊 AI-generated **voice replies** using ElevenLabs.
- 📡 WebSocket support for instant communication.
- 🌐 Simple web-based frontend.

---

## 🛠️ Requirements
- **Python 3.8+**
- Cohere API key
- ElevenLabs API key

### Install Python dependencies:
```bash
pip install flask flask-socketio flask-cors cohere elevenlabs RealtimeSTT scipy numpy
```

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/USERNAME/REPO.git
   cd REPO
   ```
2. **Set your API keys** in `Chatbot.py`:
   ```python
   self.cohere = cohere.Client("YOUR_COHERE_API_KEY")
   self.elevenlabs = ElevenLabs(api_key="YOUR_ELEVENLABS_API_KEY")
   ```
3. **Run the server:**
   ```bash
   python Chatbot.py
   ```
4. **Open your browser** at:
   ```
   http://127.0.0.1:5000
   ```

---

## 📷 Screenshot
![Smart Assistant Screenshot](screenshot.png)

> Replace `screenshot.png` with your actual image file of the interface.

---

## 📄 License
This project is licensed under the **MIT License** – feel free to use and modify it.
