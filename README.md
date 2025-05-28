
## 🔊 Voice Assistant – Python Project

This is a beginner-friendly **Voice Assistant** built using Python as part of my internship with **Oasis Infobyte**. The assistant can understand and respond to voice commands, making it interactive and user-friendly.

## 💡 Features

* 👋 Responds to greetings like "Hello"
* 🕒 Tells the current **time** and **date**
* ☁️ Provides **weather updates** (via OpenWeatherMap API)
* 📚 Answers general questions using **Wikipedia**
* 🎙️ Takes voice input using `SpeechRecognition`
* 🔊 Speaks responses using `pyttsx3`

## 🛠️ Tech Stack

* Python 3.x
* SpeechRecognition
* pyttsx3
* Wikipedia API
* OpenWeatherMap API
* datetime
* requests

## 📦 How to Run

1. Install the dependencies:

   ```bash
   pip install speechrecognition pyttsx3 wikipedia requests
   ```

2. Replace the `api_key` in the `get_weather()` function with your OpenWeatherMap API key:

   ```python
   api_key = "YOUR_API_KEY"
   ```

3. Run the Python script:

   ```bash
   python voice_assistant.py
   ```

4. Speak commands like:

   * "Hello"
   * "What is the time?"
   * "Tell me the weather"
   * "Who is Elon Musk?"

## 🎯 Goal

To create a foundation for a natural language-based assistant capable of answering questions and performing simple tasks using voice interaction.

## Output Screens
![Screenshot 2025-05-28 230047](https://github.com/user-attachments/assets/57ff07f5-1bbf-4779-87b6-58e8d829f743)


## Video Reference
https://github.com/user-attachments/assets/583ff008-21d8-40ff-aeb0-b880fa4ad63b

