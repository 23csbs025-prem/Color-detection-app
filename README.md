# Color Detection App

A simple web application to detect the color of a pixel in an uploaded image.

## Features

- Upload an image (PNG, JPG, JPEG).
- Click on any point in the image to detect color.
- Display:
  - RGB values of the pixel clicked.
  - Closest color name from a dataset.
  - A color box showing the detected color.

## Getting Started

### Prerequisites

- Python 3.7 or newer

### Installation

```bash
git clone <your-repo-url>
cd color_detection_app
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
pip install -r requirements.txt
