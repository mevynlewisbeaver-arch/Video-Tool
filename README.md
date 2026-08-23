[🇻🇳 Tiếng Việt](README.md) | [🇬🇧 English](README.en.md) | [🇨🇳 中文](README.zh.md)

# 🎬 Công Cụ Tổng Hợp Xử Lý Video

## VideoTool

Phần mềm **tất cả trong một** giúp bạn xử lý video và âm thanh nhanh chóng, hỗ trợ đa ngôn ngữ và tự động nhận diện phần cứng máy tính để tối ưu tốc độ xử lý.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyQt5](https://img.shields.io/badge/GUI-PyQt5-green?style=for-the-badge)
![FFmpeg](https://img.shields.io/badge/Powered%20by-FFmpeg-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows)

## 🌟 Tính Năng Nổi Bật

### 🎙️ Tab 1: Giảm Âm Theo Phụ Đề

- Tự động giảm âm lượng video tại các đoạn có hội thoại dựa trên file phụ đề `.SRT` hoặc `.ASS`.
- Có thể tùy chọn nhúng trực tiếp phụ đề lên video.
- Hỗ trợ tăng tốc xử lý bằng:
  - NVIDIA GPU
  - Intel GPU
  - AMD GPU
  - CPU

### 🔊 Tab 2: SRT Sang Giọng Nói (TTS)

- Chuyển đổi file phụ đề `.SRT` thành file âm thanh `.MP3`.
- Âm thanh được ghép chính xác theo các mốc thời gian của phụ đề gốc.
- Hỗ trợ nhiều công nghệ chuyển văn bản thành giọng nói:

| Công nghệ | Chế độ |
|---|---|
| 🎤 Edge TTS | Online |
| 🤖 OpenAI TTS | Online |
| 🔵 Google TTS | Online |
| 🔈 Piper TTS | Offline |

### 🎵 Tab 3: Thêm Âm Thanh Vào Video

- Trộn nhạc hoặc file âm thanh mới vào video có sẵn.
- Điều chỉnh độc lập:
  - Âm lượng video gốc.
  - Âm lượng nhạc hoặc âm thanh được thêm vào.
- Sao chép trực tiếp luồng video (**Copy Video Stream**).
- Không mã hóa lại hình ảnh, giúp tốc độ xử lý nhanh hơn.

## 💻 Yêu Cầu Hệ Thống

- Hệ điều hành: **Windows 10 / Windows 11 64-bit**.
- Không cần cài đặt Python.
- Chỉ cần tải về, giải nén và chạy chương trình.

## ⬇️ Tải Xuống Và Cài Đặt

1. Truy cập mục **Releases** trên trang GitHub của dự án.
2. Tải xuống các file sau:

   - `VideoTool.exe` — Phần mềm chính.
   - `ffmpeg.zip` — Bộ công cụ xử lý video.
   - `piper.zip` — Dữ liệu giọng đọc Offline cho Tab 2 *(tùy chọn)*.

3. Giải nén `ffmpeg.zip` và `piper.zip`.

Sau khi giải nén, đảm bảo cấu trúc thư mục như sau:

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
└── 📁 piper/                      (Tùy chọn - dùng TTS Offline)
    ├── 📄 piper.exe
    ├── 📄 vi_VN-vivos-x_low.onnx
    └── 📁 espeak-ng-data/
```

Sau đó, chỉ cần **click đúp vào `VideoTool.exe`** để khởi động phần mềm.

## 🌍 Đa Ngôn Ngữ

VideoTool hỗ trợ 3 ngôn ngữ:

- 🇻🇳 Tiếng Việt
- 🇬🇧 English
- 🇨🇳 中文

Bạn có thể chọn ngôn ngữ từ menu thả xuống ở góc trên bên phải cửa sổ.

Giao diện sẽ tự động chuyển đổi ngôn ngữ ngay lập tức.

## 📜 Tác Giả

**Tác giả:** `mevynlewisbeaver-arch`


====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/ae976dde-3cdb-4847-b9aa-9ef35880bde8" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/336da7c6-34dc-4a18-be3c-32b29180ea48" />

====================================

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/44bdcad5-6e25-432b-8687-a507ff07d119" />

====================================
