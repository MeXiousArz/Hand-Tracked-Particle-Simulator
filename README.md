**Neural Link Particle Simulation:**
This is an immersive, browser-based generative art experience that bridges the gap between human movement and digital geometry. Using Three.js for high-performance 3D rendering and MediaPipe for real-time computer vision, this project transforms your webcam into a "Neural Link" controller.
The simulation features over 20,000 active particles that morph between complex mathematical structures based on your hand gestures.


**🖐️ Gesture Control Guide:**
The "Neural Link" system is designed to be intuitive and responsive. Position yourself so your hands are clearly visible to your webcam.
- Hand Movement -> Orbit Rotation -> Move your hand left, right, up, or down to rotate the core geometry in 3D space.
- The Pinch -> Hyper-Expansion -> Bring your thumb and index finger together to compress the shape; pull them apart to expand the particles.
- Two-Hand Clap -> Geometry Shift -> Bring both hands close together quickly to trigger a "Vortex Transition" into the next shape.


**🌀 Available Geometries:**
The system cycles through a variety of mathematically generated shapes:
- Celestial: Saturn, Galaxy, Sphere
- Biological: DNA Double Helix, Heart, Butterfly
- Abstract/Nature: Dragon (with Fire Breath), Spring, Flower, Fireworks


**🛠️ Technical Stack:**
- Three.js: Powering the WebGL particle engine and post-processing bloom effects.
- MediaPipe (Hand Landmarker): Providing low-latency, 21-point hand tracking directly in the browser.
- GLSL/Post-Processing: Utilizing UnrealBloomPass for that neon-cyberpunk aesthetic.


**🚀 How to Run Locally:**
- Clone this repository:
  Bashgit clone https://github.com/MeXiousArz/MeXiousArz.git
- Open index.html in any modern web browser (Chrome or Edge recommended for best MediaPipe performance).
- Grant webcam permissions when prompted.
- Wait for the "Neural Link" status to show detected hands and start interacting!
