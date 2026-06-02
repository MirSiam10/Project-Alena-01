# 🤖 Alena - AI Voice Assistant

An intelligent voice-controlled assistant built with Python that can listen to voice commands, open websites, play music, fetch news headlines, and answer questions using AI.

---

## 🚀 Features

* 🎤 Voice Recognition using SpeechRecognition
* 🔊 Text-to-Speech Responses using gTTS
* 🌐 Open Popular Websites (Google, YouTube, Facebook, LinkedIn)
* 🎵 Play Music from a Custom Music Library
* 📰 Fetch Latest News Headlines via NewsAPI
* 🤖 AI-Powered Responses using OpenAI
* 🗣️ Wake Word Activation ("Alena")

---

## 🛠️ Tech Stack

| Technology        | Purpose                   |
| ----------------- | ------------------------- |
| Python            | Core Programming Language |
| SpeechRecognition | Voice Input               |
| gTTS              | Text-to-Speech            |
| Pygame            | Audio Playback            |
| OpenAI API        | AI Responses              |
| NewsAPI           | Latest News Retrieval     |
| Webbrowser        | Website Automation        |

---

## 📂 Project Structure

```text
Alena/
│
├── main.py
├── client.py
├── musicLibrary.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/alena-ai-assistant.git

cd alena-ai-assistant
```

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / Mac

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configuration

Replace the following placeholders with your own API keys:

### OpenAI API Key

```python
api_key="YOUR_OPENAI_API_KEY"
```

### NewsAPI Key

```python
newsapi = "YOUR_NEWS_API_KEY"
```

---

## 🎤 Usage

Run the assistant:

```bash
python main.py
```

Wake Word:

```text
Alena
```

Example Commands:

```text
Open Google
Open YouTube
Play Wolf
Play Thorfinn
Tell me the news
What is Artificial Intelligence?
```

---

## 🎵 Available Music Commands

Current music library:

* The Knight
* Medieval
* Thorfinn
* Wolf

You can add your own songs inside:

```python
musicLibrary.py
```

---

## 🔄 How It Works

1. Waits for the wake word "Alena"
2. Activates listening mode
3. Processes voice command
4. Executes predefined tasks
5. Uses OpenAI for general questions
6. Responds through voice output

---

## 🚧 Future Improvements

* GUI Interface
* Chat History
* Local LLM Support
* Weather Updates
* WhatsApp Integration
* Smart Home Automation
* Voice Authentication
* Multiple Wake Words

---

## 🤝 Contributing

Contributions are welcome.

Fork the repository, create a feature branch, and submit a pull request.

---

## 👨‍💻 Author

**Mir Siam**

CSE Student | AI Enthusiast | Python Developer

GitHub: https://github.com/MirSiam10

---

## ⭐ Support

If you find this project useful, consider giving it a star on GitHub.
