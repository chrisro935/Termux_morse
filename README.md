# 🛰️ Termux Morse Code Tool

A colorful, audio-enhanced Morse code encoder and decoder script for Termux!

## 🎯 Features

- 🔤 Encode text to Morse with colored output
- 🔊 Plays beeps for dot and dash (`dot.wav` & `dash.wav`)
- 🗣️ Decodes Morse code and speaks the output with `termux-tts-speak`
- 🎨 Colorful and fun terminal UI

## 📦 Installation

1. Clone the repo or download as ZIP:
   ```bash
   git clone https://github.com/chrisro935/Termux_morse.git
   cd morse.sh

2. Make the file executable
   ```bash
   chmod +x morse.sh

3. Ensure you have Termux required packages
   ```bash
   pkg install termux-api termux-media-player

4. Run the tool
   ```bash
   ./morse.sh

## 📁 Files Included

morse.sh — The main Morse encoder/decoder

dot.wav — Beep for dot

dash.wav — Beep for dash


## 💡 Notes

Designed for Termux on Android

Requires termux-api and termux-media-player

Place all files in one directory — do not move .wav files


## 📜 License

MIT
