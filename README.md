# 3D Keep-Ups

A football keep-ups game in the browser, using webcam motion tracking and 3D physics. Just your webcam, knees, and feet!

🎮 Play here: **[https://collidingscopes.github.io/keep-ups/](https://collidingscopes.github.io/keep-ups/)**

## How to Play

1. Allow webcam access when prompted
2. Position yourself so your full body is visible to the camera
3. Use your knees and feet to keep the soccer ball in the air
4. Perform a T-pose (arms stretched out horizontally) for 1 second to reset the ball

## Features and Tech

- No downloads or installations required
- Real-time pose detection using Mediapipe
- Three.js for 3D rendering
- Rapier3D for physics simulation
- Vanilla JavaScript, HTML5, and CSS3

## Privacy

The game processes all webcam data locally in your browser. No video or images are sent to any server.

## Development

To run locally:
1. Clone the repository
2. Serve the files using a local server (e.g., `python -m http.server`)
3. Open in your browser at `localhost:8000`