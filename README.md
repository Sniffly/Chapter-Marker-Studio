# Chapter Marker Studio

![App Screenshot](cms_screenshot.png)

Chapter Marker Studio is a simple Python GUI for managing video chapter metadata. Forked from https://github.com/thurmansevolution/Chapter-Marker-Studio

## Features
- Embedded video player for precise marking.
- Add/Remove chapter markers.
- Scan for and edit  existing markers
- Scan for black frames (powered by `mkchap` by Jason Doves).

## Changes from original
- Added XML file export (for use with ErsatzTV)

## Status & License
This project is open source and free to use. Feel free to fork and edit the code.

## Prerequisites
- Python 3.8+
- `ffmpeg`
- `ffprobe`

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/Chapter-Marker-Studio.git
cd Chapter-Marker-Studio
```

2. Install Python dependencies:
```bash
pip install PySide6 pygame
```

## How to Run
```bash
python main.py
```

## Future plans
- Audio sync fixes/ability to avoid audio extraction prior to playback
- Reading existing XML data
- Targeted black frame scanning
