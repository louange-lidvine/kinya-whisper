# 🎙️ Kinyarwanda Voice Assistant

A **mini voice assistant** built for **Intelligent Robotics coursework**, designed to understand and respond to **Kinyarwanda** speech.  
It listens to spoken questions, converts them into text, understands the meaning, and speaks back a thoughtful response — all in Kinyarwanda!

---

## 🚀 Features

- 🎧 **Speech Recognition** — Understands Kinyarwanda audio input  
- 🤖 **Natural Language Understanding** — Interprets your spoken questions  
- 🔊 **Voice Response** — Replies using natural-sounding speech  
- 📁 **Logging** — Stores both recognized text and generated answers in the `outputs/` folder

---

## 📋 Requirements

Make sure the following are installed on your machine:

- **Python 3.7+** — Required to run the project  
- **[torch](https://pytorch.org/)** — Used by Whisper for transcription  
- **[openai-whisper](https://github.com/openai/whisper)** — For converting speech to text  
- **[gTTS](https://pypi.org/project/gTTS/)** — For converting text answers to speech in Kinyarwanda  
- **[ffmpeg](https://ffmpeg.org/)** — Required by Whisper to process audio files

### 📦 Install Python dependencies:
```bash
pip install torch openai-whisper gTTS
