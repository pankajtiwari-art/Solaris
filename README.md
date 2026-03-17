# 🌌 Genesis Engine - Solaris

**Genesis Engine - Solaris** is a highly immersive, real-time 3D space simulation built using WebGL and Three.js. It leverages custom GLSL shaders, complex particle systems, and cinematic post-processing to render a massive, dynamic star and its surrounding accretion disk in the browser.

🔗 **Live Demo:** [Experience Solaris Here](https://pankajtiwari-art.github.io/Solaris/)

---

## ✨ Key Features

* **Custom Shader Materials (GLSL):** The star's core and shell utilize Perlin noise and complex mathematical functions to simulate dynamic, realistic surface displacement and solar flares.
* **Accretion Disk & Particle Systems:** Thousands of individual particles are animated directly on the GPU via custom shaders, following real-time orbital trajectories without bottlenecking the CPU.
* **Cinematic Auto-Rotation:** Features smooth `OrbitControls` with an idle auto-rotation mechanic. If left untouched, the camera automatically pans into a slow, cinematic orbit around the star.
* **Advanced Post-Processing Stack:** * **UnrealBloomPass:** Creates the intense, atmospheric glow and light emission of the star.
  * **AfterimagePass:** Adds a subtle motion blur and light-trail effect to high-speed moving particles.
  * **FXAA:** Ensures sharp, clean edges and anti-aliasing across the scene.
* **Fully Responsive:** The camera aspect ratio and post-processing resolution dynamically adapt to window resizing.

---

## 🛠️ Tech Stack

* **HTML5 / CSS3:** Structure and minimal full-screen overlay UI.
* **JavaScript (ES6+):** Core logic, animation loops, and scene management.
* **Three.js (WebGL):** 3D rendering engine.
* **GLSL (OpenGL Shading Language):** Custom vertex and fragment shaders for materials and physics.

---

## 🚀 How to Run Locally

To run this project in your local development environment:

1. Clone this repository:
    git clone https://github.com/Pankajtiwari-art/Solaris.git

2. Navigate to the project directory:
    cd Solaris

3. Open the `index.html` file using a local web server to avoid CORS (Cross-Origin Resource Sharing) issues. If you are using VS Code, the **Live Server** extension is highly recommended.

---

## 🗺️ Roadmap (Upcoming Features)

The engine is continuously evolving. Planned features to enhance the physics and visual fidelity include:

- [ ] **Anamorphic Lens Flares:** Adding cinematic, horizontal light streaks that react dynamically to camera movement.
- [ ] **Distance-Based Spatial Audio:** Implementing a deep space solar hum that increases in intensity as the camera zooms into the core.
- [ ] **Gravity Wells (Physics Upgrade):** Introducing massive objects (like black holes) that bend particle trajectories in real-time.
- [ ] **Interactive Control Panel:** Adding a GUI to tweak parameters like core color, particle speed, and bloom force on the fly.

---

## 👨‍💻 About the Author

**Pankaj Tiwari** A developer with a background in building interactive websites and games. Beyond coding, he is the author of two books, including *Control Psychology: The Illusionary Game*, bringing a unique blend of technical problem-solving and philosophical insight into his digital creations. 

*Feel free to explore the code, fork the repo, and contribute!*
