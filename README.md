# 🌐 Natural Language Translation Web App

A simple yet powerful **Natural Language Translation Web Application** built using Python and Streamlit, with audio and text processing powered by:
- [`pydub`](https://github.com/jiaaro/pydub) — for audio manipulation
- [`pyaudio`](https://people.csail.mit.edu/hubert/pyaudio/) — for capturing audio input
- [`gTTS`](https://github.com/pndurette/gTTS) — for converting text to speech
- [`googletrans`](https://github.com/ssut/py-googletrans) — for translating text between multiple languages

This application allows you to:
- **Input text or audio**  
- **Translate it to the desired language**  
- **Listen to the translated output**  

🚀 Designed for simplicity — perfect for quick translations and language learning.

---

## ✨ Features
- 📝 **Text Translation** — Type in your text and translate it instantly.
- 🎤 **Audio Input** — Speak into your microphone and convert speech to text for translation.
- 🔊 **Text-to-Speech** — Listen to the translated result in your chosen language.
- 📱 **User-Friendly Interface** — Built with Streamlit for a clean, responsive experience.

---

## 📌 Planned Features
- 🔄 **Direct Audio-to-Audio Translation** — Skip the text step and translate spoken input directly into spoken output in another language.
- 🌍 **Multi-Language Audio Support** — Enable real-time speech translation across several languages.
- ⏱ **Real-Time Mode** — Continuous translation while speaking.
- 🎛 **Custom Voice Selection** — Choose from multiple voices and accents.

---

## 🛠 Installation

pip install -r requirements.txt
streamlit
pydub
pyaudio
gtts
googletrans==4.0.0-rc1
