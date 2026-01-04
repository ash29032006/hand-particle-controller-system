# 🌌 Hand Particle Controller System ✨

> **"Experience the power of a supernova in the palm of your hand."**

![Particle System](https://img.shields.io/badge/Status-Mesmerizing-ppink?style=for-the-badge)
![Tech](https://img.shields.io/badge/Built%20With-Three.js%20%7C%20MediaPipe%20%7C%20WebGL-blue?style=for-the-badge&logo=three.js)

A stunning, interactive 3D web application where **25,000 particles** dance to the movement of your hands. Built with **Three.js** and **MediaPipe**, this project blends high-performance graphics with computer vision to create a magical user experience.

---

## 🚀 Features that make you go "WOW"

### 💥 The "Supernova" Blast
Clench your fist tightly (>65% tension) to trigger a massive **explosive event**.
- **Visuals**: Particles blast outward in a violent red shockwave.
- **Feedback**: A massive **"BOOM!"** overlay strikes the screen.
- **Immersion**: The camera shakes and the universe pulses with energy.

### 🎨 Elegant Glassmorphism UI
- A modern, translucent control panel that floats over the scene.
- Real-time tracking status with a glowing neon indicator.
- Fully responsive design with smooth hover effects.

### 🔮 3D Shape Morphing
Seamlessly transform the particle cloud into various forms:
- 🔵 **Sphere** (Default)
- ❤️ **Heart**
- 🌸 **Flower**
- 🪐 **Saturn** (with rings!)
- 🧘 **Buddha**
- 🎆 **Fireworks**

### ✨ Cinematic Post-Processing
- **Unreal Bloom**: Particles glow with an ethereal light using high-dynamic-range (HDR) bloom.
- **Deep Space Fog**: Adds depth and mystery to the background.
- **Dynamic Color**: Cycles through the spectrum when idle, or reacts to your gestures.

---

## 🛠️ Tech Stack

*   **[Three.js](https://threejs.org/)**: The 3D engine driving the particle simulation.
*   **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)**: Real-time, high-fidelity hand tracking directly in the browser.
*   **WebGL**: For hardware-accelerated graphics.
*   **Vanilla JS/CSS**: No heavy frameworks, just pure performance.

---

## 🎮 How to Play

1.  **Clone the Repo**:
    ```bash
    git clone https://github.com/ash29032006/hand-particle-controller-system.git
    cd hand-particle-controller-system
    ```

2.  **Run a Local Server**:
    (Webcams require a secure context or localhost)
    ```bash
    # Python 3
    python3 -m http.server 8000
    
    # OR using NPM
    npx serve
    ```

3.  **Open in Browser**:
    Go to `http://localhost:8000`

4.  **Grant Camera Access**: The app needs to see your hand to work its magic! ✋

---

## 🧙‍♂️ Controls

| Gesture | Action |
| :--- | :--- |
| **Open Hand** | Interacts with particles (Standard Mode). |
| **Slight Close** | Expands/Pulses the particle cloud based on tension. |
| **FIST CLENCH ✊** | **TRIGGERS THE EXPLOSION!** 💥 |

---

Released with ❤️ by **Ashwin Harish**.
