"""
MP3 Splitter Script

This script allows you to split an MP3 file into smaller segments based on user-defined durations or timestamps.
It uses the `pydub` library for audio manipulation and requires the `ffmpeg` library to handle MP3 encoding and decoding.

---

## Features:
- Split MP3 files based on a list of start and end timestamps.
- Automatically name the output files for easy organization.

---

## Prerequisites:
- Python 3.x
- Required libraries: `pydub`

Install dependencies:
```bash
pip install pydub
