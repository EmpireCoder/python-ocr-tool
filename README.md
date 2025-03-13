# Python OCR Tool

A powerful OCR (Optical Character Recognition) tool with GUI interface for screen text recognition and monitoring.

## Features

- Real-time screen monitoring and OCR
- Configurable screen regions
- Training mode for improved accuracy
- Socket server for remote access
- Playback functionality
- User-friendly GUI interface

## Requirements

- Python 3.6+
- Tesseract OCR engine
- Required Python packages (see requirements.txt)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/EmpireCoder/python-ocr-tool.git
cd python-ocr-tool
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Install Tesseract OCR engine:
- Windows: Download and install from https://github.com/UB-Mannheim/tesseract/wiki
- Linux: `sudo apt-get install tesseract-ocr`
- Mac: `brew install tesseract`

## Usage

Run the main application:
```bash
python allOcr.py
```

1. Select a process to monitor
2. Configure screen regions for OCR
3. Use the training mode to improve recognition accuracy
4. Monitor text in real-time

## Configuration

- Screen Configuration: Define multiple screen regions for monitoring
- Read Areas: Configure specific areas for text recognition
- Training Mode: Improve OCR accuracy by providing corrections
- Playback: Record and replay screen interactions

## License

MIT License