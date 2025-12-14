# Hassan’s ParticleSync ✋✨  
**Gesture-Reactive 3D Particle System powered by AI Vision & Three.js**

Hassan’s ParticleSync is an immersive, real-time 3D particle system that reacts to **hand gestures captured through your camera**. Built using **Three.js** and **MediaPipe Hands**, this project blends creative coding, AI-powered vision, and interactive design to create a visually striking, futuristic experience.

Particles dynamically morph into multiple templates and respond physically to human gestures such as attraction, repulsion, and shape switching — all in real time.

---

## 🚀 Features

- **Real-Time Hand Tracking** using MediaPipe Hands  
- **Gesture-Based Interaction**
  - 🖐 Open Hand → Repel / Scatter particles
  - 👌 Pinch → Attract particles (gravity effect)
  - ✌️ Victory Sign → Switch particle templates
- **Multiple Particle Templates**
  - Sphere
  - Cube
  - Galaxy
  - DNA Helix
  - Torus
- **High-Performance Rendering**
  - 15,000+ GPU-accelerated particles
  - Additive blending & fog effects
- **Modern HUD & UI**
  - Live gesture status
  - Active shape indicator
  - Camera preview feed
- **Smooth Transitions & Physics-Like Motion**

---

## 🧠 Tech Stack

- **Three.js** — 3D rendering & particle system  
- **MediaPipe Hands** — AI-based hand landmark detection  
- **WebGL** — High-performance graphics  
- **JavaScript (ES Modules)**  
- **HTML5 + CSS3 (Glassmorphism UI)**  

---

## 📷 Demo Preview

- Live camera feed with mirrored hand tracking  
- Real-time gesture recognition  
- Dynamic particle deformation and motion  

> Best experienced on desktop with a webcam and good lighting.

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/particle-sync.git
cd particle-sync
```

### 2️⃣ Run on a Local Server
Camera access **will not work** if opened as a file.

Using VS Code:
```bash
Right-click → Open with Live Server
```

Using Python:
```bash
python -m http.server
```

Then open:
```
http://localhost:8000
```

---

## 🛑 Requirements

- Modern browser (Chrome / Edge recommended)  
- Webcam access enabled  
- Local server (required for MediaPipe)  
- Good lighting for reliable gesture detection  

---

## 🎮 Gesture Guide

| Gesture | Action |
|--------|--------|
| Open Hand 🖐 | Repels nearby particles |
| Pinch 👌 | Attracts particles inward |
| Victory ✌️ | Switches particle shape |

Shape switching includes a cooldown to prevent accidental rapid changes.

---

## 🧩 Project Structure

```
├── index.html
├── README.md
```

All logic, rendering, UI, and gesture handling are contained in a single modular HTML file for simplicity and portability.

---

## 🌌 Use Cases

- Interactive art installations  
- Creative coding experiments  
- AI + graphics demos  
- Portfolio projects  
- Gesture-controlled visual systems  

---

## 🧑‍💻 Author

**Hassan Raza**  
BS Artificial Intelligence  
Passionate about **AI-driven interaction**, **creative coding**, and **immersive systems**

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and build upon it — attribution appreciated.

---

## ⭐ Support

If you like this project:
- ⭐ Star the repository  
- 🍴 Fork it  
- 🧠 Experiment with new shapes & gestures  

> *“Where human motion meets digital matter.”*
