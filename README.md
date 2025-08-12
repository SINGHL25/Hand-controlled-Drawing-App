# Hand-controlled-Drawing-App
webcam detects your hand and lets you draw on screen without a mouse — just finger tracking.
# Hand Draw — Finger Painting with Webcam

A small browser-only web app that uses MediaPipe Hands (client-side) and an HTML5 `<canvas>` so you can draw with your finger using your webcam.

## Features
- Real-time fingertip tracking (MediaPipe Hands JS)
- Draw using index finger (landmark 8)
- Color and brush size controls, clear, save PNG
- Toggle webcam preview for performance

## How to run locally
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/hand-draw-webapp.git
   cd hand-draw-webapp
