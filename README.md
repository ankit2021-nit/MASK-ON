# Real-Time Face Mask & Specs Detector

## Overview

This project is a web-based real-time face mask and spectacles (specs) detector using TensorFlow.js and BlazeFace. It uses your webcam to detect faces, checks if a mask is worn, and identifies if the person is wearing specs—all in the browser, with no server required.

## Features
- **Real-Time Detection:** Instantly detects faces, masks, and specs from your webcam stream.
- **Interactive UI:** Modern, responsive design with animated bounding boxes and status indicators.
- **No Installation Needed:** Runs entirely in your browser.
- **Accessibility:** Keyboard navigation and clear error messages.
- **Mobile Friendly:** Works on desktop and mobile browsers.

## How It Works
- **Face Detection:** Uses BlazeFace model to locate faces and facial landmarks.
- **Mask Detection:** Analyzes pixel color variance in the lower face region to guess if a mask is present.
- **Specs Detection:** Uses a custom or pre-trained model to identify spectacles (specs) on detected faces.

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ankit2021-nit/MASK-ON.git
cd MASK-ON
```

### 2. Start a Local Server
You need a local server for webcam access. Use Python:
```bash
python -m http.server 8000
```
Then open [http://localhost:8000/index.html](http://localhost:8000/index.html) in your browser.

### 3. Use the App
- Click **Enable Webcam** to start detection.
- See bounding boxes and labels for mask/specs status.
- Errors and status updates are shown interactively.

## Customization
- Change styles in `index.html` for your own theme.
- Integrate other models for more features (e.g., age, emotion).

## Contributing
Pull requests and suggestions are welcome! Please open an issue for bugs or feature requests.

---
**Made with TensorFlow.js, BlazeFace, and ❤️ by Ankit
