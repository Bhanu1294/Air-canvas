# Air Canvas 🎨

Air Canvas is a Python-based project that allows users to draw in the air using hand gestures. It uses computer vision techniques and OpenCV to track hand movements and translate them into drawings on a virtual canvas.

## Features ✨
- Hand gesture tracking using OpenCV and MediaPipe
- Draw in the air using finger movements
- Change colors and brush thickness with gestures
- Erase parts of the drawing with a specific gesture

## Installation ⚙️

Clone the repository and install dependencies:
```bash
git clone https://github.com/Bhanu1294/Air-canvas.git
cd Air-canvas/canvas
pip install -r requirements.txt
```

## Usage 🚀
Run the script to start the Air Canvas:
```bash
python air_canvas.py
```

## Dependencies 📦
- Python 3.x
- OpenCV
- MediaPipe
- NumPy

Install dependencies using:
```bash
pip install opencv-python mediapipe numpy
```

## How It Works 🖐️
1. The camera detects your hand using MediaPipe's Hand Tracking model.
2. Specific finger movements act as drawing or erasing commands.
3. The virtual brush moves according to your hand gestures, allowing you to draw in the air.



