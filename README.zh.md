[🇻🇳 Tiếng Việt](README.md) | [🇬🇧 English](README.en.md) | [🇨🇳 中文](README.zh.md)

# 🎬 视频综合处理工具

## VideoTool

这是一款**多合一视频和音频处理软件**，可帮助您快速处理视频和音频文件。软件支持多语言，并能够自动检测计算机硬件，以优化处理速度。

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyQt5](https://img.shields.io/badge/GUI-PyQt5-green?style=for-the-badge)
![FFmpeg](https://img.shields.io/badge/Powered%20by-FFmpeg-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows)

## 🌟 主要功能

### 🎙️ 选项卡 1：根据字幕降低音量

- 根据 `.SRT` 或 `.ASS` 字幕文件，在对话片段自动降低视频音量。
- 支持将字幕直接烧录到视频画面中。
- 支持以下硬件加速方式：
  - NVIDIA GPU
  - Intel GPU
  - AMD GPU
  - CPU

### 🔊 选项卡 2：SRT 转语音（TTS）

- 将 `.SRT` 字幕文件转换为人工智能语音 `.MP3` 文件。
- 音频可根据原始字幕时间戳进行准确同步。
- 支持多种文本转语音引擎：

| 技术 | 模式 |
|---|---|
| 🎤 Edge TTS | 在线 |
| 🤖 OpenAI TTS | 在线 |
| 🔵 Google TTS | 在线 |
| 🔈 Piper TTS | 离线 |

### 🎵 选项卡 3：添加音频到视频

- 将新的音乐或音频文件混入现有视频。
- 可以分别调整：
  - 原始视频音量。
  - 添加的音乐或音频音量。
- 使用 **Copy Video Stream** 模式。
- 无需重新编码视频，因此处理速度非常快。

## 💻 系统要求

- 操作系统：**Windows 10 / Windows 11 64位**。
- 无需安装 Python。
- 下载、解压后即可运行。

## ⬇️ 下载与安装

1. 前往本 GitHub 项目的 **Releases** 页面。
2. 下载以下文件：

   - `VideoTool.exe` — 主程序。
   - `ffmpeg.zip` — 视频处理工具。
   - `piper.zip` — 选项卡 2 使用的离线语音数据 *(可选)*。

3. 解压 `ffmpeg.zip` 和 `piper.zip`。

请确保文件夹结构如下：

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
└── 📁 piper/                      （可选 - 离线 TTS）
    ├── 📄 piper.exe
    ├── 📄 vi_VN-vivos-x_low.onnx
    └── 📁 espeak-ng-data/
```

然后只需**双击 `VideoTool.exe`** 即可启动软件。

## 🌍 多语言支持

VideoTool 支持 3 种语言：

- 🇻🇳 越南语
- 🇬🇧 English
- 🇨🇳 中文

您可以在软件窗口右上角的下拉菜单中选择所需语言。

选择后，软件界面会立即切换。

## 📜 作者

**作者：** `mevynlewisbeaver-arch`



====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/70587bbb-8680-4876-96dd-dc0a438f51f7" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/aaa5201e-c390-4031-8a9a-fcee2f46d3c5" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/8f458cde-8d4a-499e-bf4d-debd43af678c" />

====================================
