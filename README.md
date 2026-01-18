🌌 Aura: AI Particle Controller
Aura is an interactive 3D visualizer that merges computer vision with high-performance computer graphics. By leveraging your webcam, the application tracks hand movements to manipulate thousands of particles in real-time, allowing you to scale, rotate, and swap 3D constellations with simple physical gestures.

[Image Placeholder: GIF or Screenshot of the Saturn/Hearts particles in action]

✨ Key Features
Real-time Hand Tracking: Uses MediaPipe Hands to detect landmarks and calculate distances for gesture recognition.

Gesture-Based Interaction:

Pinch/Spread: Dynamically scale the particle system by changing the distance between your thumb and pinky.

Wrist Swapping: Move your hand to the extreme edges of the camera to cycle through 3D templates (Saturn, Hearts, Flower).

Interactive 3D Engine: Powered by Three.js using PointsMaterial and BufferGeometry for high-performance rendering of 10,000+ particles.

Dynamic UI: Includes a Tweakpane control panel to manually adjust colors and templates.

Glassmorphism Design: A modern, blurred overlay panel for a futuristic aesthetic.

🛠️ Tech Stack
Graphics: Three.js (WebGL)

AI/Vision: @mediapipe/hands

UI Controls: Tweakpane

Styling: CSS3 (Radial Gradients & Backdrop Filters)
