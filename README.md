Overview
The Smart Assistant is an interactive voice and text chatbot built with Flask and Socket.IO.
It integrates Cohere AI for natural language understanding and ElevenLabs for realistic text-to-speech synthesis.
The assistant supports real-time Arabic speech recognition, text chat, and audio responses in a friendly conversational tone.

✨ Features
💬 Text chat with real-time AI responses.

🎤 Arabic speech-to-text with live transcription.

🔊 AI-generated voice replies using ElevenLabs.

📡 WebSocket support for instant communication.

🌐 Simple web-based frontend.

🛠️ Requirements
Python 3.8+

Cohere API key

ElevenLabs API key

Install Python dependencies:
bash
pip install flask flask-socketio flask-cors cohere elevenlabs RealtimeSTT scipy numpy
🚀 How to Run
Clone the repository:

bash


git clone https://github.com/USERNAME/REPO.git
cd REPO
Set your API keys in Chatbot.py:

python


self.cohere = cohere.Client("YOUR_COHERE_API_KEY")
self.elevenlabs = ElevenLabs(api_key="YOUR_ELEVENLABS_API_KEY")
Run the server:

bash
python Chatbot.py
Open your browser at:

cpp


http://127.0.0.1:5000
# chatbot
