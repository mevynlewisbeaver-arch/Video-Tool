[🇻🇳 Tiếng Việt](README.md) | [🇬🇧 English](README.en.md) | [🇨🇳 中文](README.zh.md)

# 🎬 Video Processing Tool

## VideoTool

An **all-in-one application** designed to process video and audio quickly. VideoTool supports multiple languages and automatically detects available hardware to optimize processing speed.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyQt5](https://img.shields.io/badge/GUI-PyQt5-green?style=for-the-badge)
![FFmpeg](https://img.shields.io/badge/Powered%20by-FFmpeg-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows)

## 🌟 Key Features

### 🎙️ Tab 1: Subtitle Volume Reduction

- Automatically reduces video volume during dialogue segments based on `.SRT` or `.ASS` subtitle files.
- Option to burn subtitles directly into the video.
- Supports hardware acceleration with:
  - NVIDIA GPU
  - Intel GPU
  - AMD GPU
  - CPU

### 🔊 Tab 2: SRT to Voiceover (TTS)

- Converts `.SRT` subtitle files into `.MP3` audio files using artificial voices.
- Audio is synchronized accurately with the original subtitle timestamps.
- Supports multiple Text-to-Speech engines:

| Technology | Mode |
|---|---|
| 🎤 Edge TTS | Online |
| 🤖 OpenAI TTS | Online |
| 🔵 Google TTS | Online |
| 🔈 Piper TTS | Offline |

### 🎵 Tab 3: Add Audio to Video

- Mixes a new music or audio file into an existing video.
- Independently adjust:
  - Original video volume.
  - Added music or audio volume.
- Uses **Copy Video Stream** mode.
- No video re-encoding is required, allowing extremely fast processing.

## 💻 System Requirements

- Operating System: **Windows 10 / Windows 11 64-bit**.
- Python installation is not required.
- Simply download, extract, and run the application.

## ⬇️ Download & Installation

1. Go to the **Releases** section of this GitHub repository.
2. Download the following files:

   - `VideoTool.exe` — Main application.
   - `ffmpeg.zip` — Video processing toolkit.
   - `piper.zip` — Offline voice data for Tab 2 *(optional)*.

3. Extract `ffmpeg.zip` and `piper.zip`.

Make sure the folder structure looks like this:

```text
📁 VideoTool/
│
├── 📄 VideoTool.exe
│
├── 📁 ffmpeg/
│   └── 📁 bin/
│       ├── 📄 ffmpeg.exe
│       └── 📄 ffprobe.exe
│
└── 📁 piper/                      (Optional - Offline TTS)
    ├── 📄 piper.exe
    ├── 📄 vi_VN-vivos-x_low.onnx
    └── 📁 espeak-ng-data/
```

Then simply **double-click `VideoTool.exe`** to launch the application.

## 🌍 Multi-language Support

VideoTool supports 3 languages:

- 🇻🇳 Vietnamese
- 🇬🇧 English
- 🇨🇳 Chinese

Select your preferred language from the dropdown menu in the top-right corner of the application.

The interface will update immediately.

## 📜 Author

**Author:** `mevynlewisbeaver-arch`



====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/4364a7a0-45f5-4d97-8b2c-6c3ef5786ffb" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/22db4b40-9263-4e7b-ab81-bb4d829b7016" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/28f4e84d-b25a-4799-b6b6-dfabeeee1497" />

====================================
