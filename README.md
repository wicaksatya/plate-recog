# Vehicle Number Plate Detection and Recognition

## Introduction
This project aims to detect and recognize vehicle number plates using OpenCV for image processing and Tesseract for Optical Character Recognition (OCR). This application can be used for various purposes including automated toll collection, traffic management, and security.

## Prerequisites
Ensure you have the following libraries installed:
- `numpy`
- `OpenCV`
- `matplotlib`
- `tensorflow`
- `pandas`
- `pytesseract`
- [Tesseract OCR engine](https://github.com/UB-Mannheim/tesseract/wiki)

## Tesseract Setup

1. Download and install [Tesseract OCR](https://github.com/UB-Mannheim/tesseract/wiki) from the github
2. Set the Tesseract executable path in your Python code using pytesseract.pytesseract.tesseract_cmd = '/path/to/tesseract.exe' (replace with your actual path).

## Customization:

* Adjust noise reduction parameters based on image quality.
* Refine contour filtering based on your specific plate format.
* Experiment with Tesseract configuration options (e.g., --psm 6 for single block characters).
