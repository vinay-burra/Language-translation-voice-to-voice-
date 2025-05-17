# 🎙️ Voice-to-Voice Translator

This is a real-time voice-to-voice translation app that allows you to speak in English and receive translated audio responses in **Spanish**, **Turkish**, and **Japanese**. Built with Python and powered by **Gradio**, **AssemblyAI**, **ElevenLabs**, and the `translate` library.

## 🌐 Demo

🎤 Speak into the microphone, and hear your translated voice in:

- 🇪🇸 Spanish  
- 🇹🇷 Turkish  
- 🇯🇵 Japanese  

## ✨ Features

- 🎧 **Voice Input**: Record your voice using a microphone.
- 📝 **Speech Recognition**: Converts your speech to text using [AssemblyAI](https://www.assemblyai.com/).
- 🌍 **Translation**: Automatically translates English text into Spanish, Turkish, and Japanese using the `translate` Python package.
- 🔊 **Text-to-Speech**: Uses [ElevenLabs](https://www.elevenlabs.io/) to generate natural-sounding voice output in each translated language.
- 🖥️ **Gradio Interface**: User-friendly web interface for seamless interaction.

## 📦 Installation

Make sure you have Python 3.7+ installed. Then install the required packages:

```bash
pip install gradio assemblyai translate elevenlabs
API Keys
You'll need API keys for:

AssemblyAI

ElevenLabs

Important: Never commit API keys to a public repository. Store them securely using environment variables or .env files.
aai.settings.api_key = "your_assemblyai_api_key"
api_key="your_elevenlabs_api_key"
