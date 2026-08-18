# MindMove-AI-Powered-Posture-Wellness-Monitor
AI-powered real-time posture, movement, and wellness monitoring prototype using MediaPipe and a smartphone camera.

## Features

- Real-time camera monitoring
- AI-based pose detection using MediaPipe
- Posture score
- Movement detection
- Stress-level prototype indicator
- Guided breathing exercise
- Session history
- Improvement suggestions

## Technologies Used

- HTML
- CSS
- JavaScript
- MediaPipe Pose Landmarker
- Python HTTP Server
- ngrok

## How to Run

### 1. Start the local server

Open terminal in the project folder and run:

```bash
python -m http.server 8000
```
### 2. Create a public HTTPS link

Open another Command Prompt and run:
```bash
ngrok http 8000
```
ngrok will display a forwarding URL:

Open:
```bash
https://example.ngrok-free.dev/main.html
```
on a phone to test the prototype.

Important

Keep both the Python server and ngrok running while using the public link.
