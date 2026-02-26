
# Your Assistant

**Your Assistant** is a local-first Windows desktop automation assistant that lets you control system actions, browser tasks, and workflows using **voice or text commands** — without relying on cloud AI or paid APIs.

Built for speed, privacy, and offline usability.

---

## ✨ Features

### 🖥️ System Control
- Open apps like Notepad, Calculator, File Explorer
- Open files and folders
- Tell current date and time
- Shutdown / restart system (optional toggle)

### 🌐 Browser Actions
- Open Google, YouTube, and common sites
- Search Google or YouTube instantly
- Navigate browser back/forward
- Quick YouTube controls

### ⚡ Automation
- Type text into active window
- Scroll actions
- Media key control
- Desktop workflow shortcuts

### 🎙️ Voice + Text Modes
- Execute commands by typing
- Execute commands by speaking
- Wake-word support *(if enabled in config)*
- Talkback voice feedback

---

## 📦 Installation

### ✅ Install via Winget (Recommended)

```powershell
winget install HVS.YourAssistant
````

### 🔄 Upgrade

```powershell
winget upgrade HVS.YourAssistant
```

### 📥 Direct Installer

Download the latest release from GitHub:

[https://github.com/Harshvs2003/Your-s_Assistant_Releases/releases](https://github.com/Harshvs2003/Your-s_Assistant_Releases/releases)

---

## 🚀 Getting Started

1. Install the application
2. Launch **Your Assistant**
3. Type a command or press the microphone button
4. Speak or enter your instruction

Example commands:

```
open notepad
search youtube for lo-fi music
type hello world
what time is it
```

---

## 🔐 Privacy Philosophy

* Core assistant logic runs locally on your device
* No cloud LLM dependency
* No background tracking or analytics

⚠️ Note:
Speech recognition using `recognize_google()` may require internet access for transcription.

---

## 🧠 OCR Support

OCR features are available when the **Tesseract runtime** is bundled with the installer.
Current public build supports **Windows x64 runtime**.

---

## 🛠️ Tech Stack

* Python 3.11
* PySide6 (GUI framework)
* SpeechRecognition
* pyttsx3 (offline TTS)
* pyautogui
* psutil
* PyInstaller packaging
* Inno Setup installer

---

## 🧩 Configuration

Some features depend on configuration flags.

You can control:

* Shutdown command availability
* Wake-word activation
* Voice talkback toggle
* Automation safety restrictions

Future versions will include an in-app settings panel.

---

## 🗺️ Roadmap

* Custom command editor
* Better voice detection in noisy environments
* Plugin system for automation extensions
* Auto-update support
* Improved installer metadata
* Expanded browser automation

---

## 🐞 Troubleshooting

### App installed but not visible in search

Search for:

```
AssistantApp
```

Some installer metadata versions may affect display name.

---

### Winget uninstall not working

Run:

```powershell
winget list assistant
winget uninstall --name "AssistantApp version 1.0.0" --exact
```

Or uninstall via **Windows Installed Apps** page.

---

### SmartScreen / Defender warning

Unsigned desktop apps can trigger warnings.
Always download from official release links only.

---

## 🤝 Contributing

Contributions, ideas, and bug reports are welcome.

When reporting issues, include:

* Windows version
* App version
* Exact command used
* Screenshot or log snippet

---

## ☕ Support Development

If this project helps you, consider supporting:

**Buy Me a Coffee**
[BuyMeACoffee](https://buymeacoffee.com/assistantapp)

**Scan to support:**

<img src="assets/bmc_qr.png" alt="BuyMeACoffee QR" width="280" />

**GitHub Sponsors**
[https://github.com/sponsors/Harshvs2003](https://github.com/sponsors/Harshvs2003)

**UPI Support (India)**

Scan to send support via UPI:

![UPI QR](assets/Payment-UPI-QR.jpeg)
---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## 🔗 Links

**Releases**
[https://github.com/Harshvs2003/Your-s_Assistant_Releases/releases](https://github.com/Harshvs2003/Your-s_Assistant_Releases/releases)

**Winget Package ID**
`HVS.YourAssistant`

---

## ⭐ Show Your Support

If you find this project useful, consider:

* ⭐ Starring the repo
* 🍴 Forking it
* 🐞 Reporting issues
* 💡 Suggesting features

Your feedback helps improve the assistant for everyone.


