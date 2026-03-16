# NOVA - AI Voice Assistant

NOVA is a **Python-based AI Voice Assistant** designed to perform everyday tasks through voice commands.

The assistant can listen to the user, understand commands, and perform actions such as opening applications, playing music, searching the web, and responding to questions.

The system combines **offline speech recognition, intent detection, and AI responses** to create a smart assistant experience.

---

## Features

- Voice command recognition
- Open applications using voice
- Play YouTube videos
- Send WhatsApp messages
- Answer general questions
- Offline speech recognition support
- AI-powered chatbot responses

---

## Technologies Used

- Python
- Vosk (Offline Speech Recognition)
- Rasa (Intent Detection)
- OpenRouter API
- Natural Language Processing

---

## Project Architecture

The assistant works through multiple modules:

1. **Speech Recognition**
   - Converts speech to text using Vosk.

2. **Intent Detection**
   - Rasa identifies the user's intent.

3. **Command Processing**
   - Python scripts perform actions based on commands.

4. **AI Response**
   - OpenRouter API generates responses for general queries.

---

## Project Structure

```
nova-ai-voice-assistant
│
├── main.py
├── speak.py
├── listen.py
├── command.py
├── util.py
├── app_control.py
├── model/
└── README.md
```

---

## Example Commands

Users can say commands like:

- "Open Chrome"
- "Play music on YouTube"
- "Send a WhatsApp message"
- "What is the weather today?"

---

## Future Improvements

- Add wake word detection
- Improve conversation ability
- Add smart home control
- Create a graphical interface

---

## Author

Mayank Rana
