# ✋ Air Canvas

A real-time gesture-based drawing application that lets you paint on a virtual canvas using just your index finger — no mouse or stylus needed.


# How It Works

The app uses your webcam to detect hand landmarks in real time using **MediaPipe**. Your **index fingertip** acts as the brush. Bringing your **thumb close to the index finger** lifts the pen (stops drawing). Color buttons and the clear button are activated by hovering your fingertip over them in the top bar.


# Features

- Real-time hand tracking via webcam
- Draw with 4 colors: Blue, Green, Red, Yellow
- Clear canvas button
- Separate paint window + live camera feed
- Pen-lift detection using thumb-index pinch


# Tech Stack

- Python
- OpenCV
- MediaPipe
- NumPy


# Installation
```bash
git clone https://github.com/your-username/air-canvas.git
cd air-canvas
pip install opencv-python mediapipe numpy
```

---

# Usage
```bash
python air_canvas.py
```

- Point your **index finger** at the screen to draw
- Hover over the **color buttons** at the top to switch colors
- Hover over **CLEAR** to reset the canvas
- **Pinch** thumb and index finger to lift the pen
- Press **`q`** to quit



# Future Improvements

- Eraser tool
- Adjustable brush size
- Save canvas as image
- Multi-hand support

