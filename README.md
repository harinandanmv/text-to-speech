# 🗣️ Text-To-Speech Android App

This is a basic Android application that converts user-typed text into speech using **Java** and Android’s native **TextToSpeech (TTS) API**. It is a lightweight and beginner-friendly project designed to demonstrate the integration of TTS features in Android.

---

## ✨ Features

- ⌨️ Accepts text input from the user  
- 🔊 Converts text to spoken audio  
- 🌍 English (US) language support  
- 📲 Simple and responsive UI  

---

## 🛠️ Tech Stack

- 🧑‍💻 Java (Android)  
- 📱 Android SDK  
- 🗣️ TextToSpeech API  
- 🎨 XML for UI layouts  

---

## 🚀 Getting Started

### Prerequisites
- Android Studio
- Android emulator or physical device with API 21+

### Steps to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/harinandanmv/text-to-voice.git
   ```

2. **Open the project in Android Studio**

3. **Build and run** on an emulator or Android device

---

## 📁 Project Structure

```
text-to-voice/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/texttovoice/MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/activity_main.xml
│   │   └── AndroidManifest.xml
├── build.gradle
└── README.md
```

---

## 🧩 How It Works

- The app initializes the `TextToSpeech` engine with `Locale.US`.
- Users enter any message into an `EditText`.
- Pressing the **Speak** button triggers the TTS engine to vocalize the text.
- The layout is optimized with `EdgeToEdge` support and system insets via `ViewCompat`.

---

## 🤝 Contributing

This is a simple educational project open for experimentation and improvements.  
Feel free to fork the repo, play with features, and submit a pull request if you build something interesting.

---

## 👤 Author

Built by [Harinandan](https://github.com/harinandanmv)   
Feel free to explore, star ⭐ the repo, or contribute with new features!
