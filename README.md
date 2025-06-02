🎙️ JARVIS: A Python Voice Assistant
JARVIS is a simple voice-activated assistant created in Python. It can perform tasks like web browsing, fetching Wikipedia summaries, playing music, telling the time, and sending emails.

🛠 Features
Speech recognition via microphone

Text-to-speech responses using pyttsx3

Wikipedia search and summary

Open websites (YouTube, Google, Stack Overflow)

Play music from a local directory

Report current time

Launch Visual Studio Code

Send emails via Gmail

📦 Requirements
Install the required Python packages:

bash
Copy
Edit
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia
pip install pyaudio  # May require additional setup depending on OS
🔧 Note for PyAudio:

On Windows, use: pip install pipwin then pipwin install pyaudio

On Linux: sudo apt install portaudio19-dev and then pip install pyaudio
