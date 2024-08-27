# Thai License Plate Recognition with Tesseract OCR

This project demonstrates how to use Python's Tesseract OCR to recognize Thai license plates from images and convert them into text.

## Requirements

- Python 3.12
- Tesseract OCR
- Python libraries: `pytesseract`, `Pillow`

## Installation

1. **Install Tesseract OCR**

   - **Linux**:
     ```bash
     sudo apt-get update
     sudo apt-get install tesseract-ocr
     sudo apt-get install tesseract-ocr-tha
     ```
   - **macOS**:
     ```bash
     brew install tesseract
     ```
   - **Windows**:
     Download the installer from [Tesseract's GitHub page](https://github.com/tesseract-ocr/tesseract) and follow the installation instructions.

2. **Install Python libraries**

   ```bash
   pip install pytesseract Pillow
