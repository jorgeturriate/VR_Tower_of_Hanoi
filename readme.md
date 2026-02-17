# 🗼 VR Tower of Hanoi – Three.js Implementation

## 📌 Overview

This project is a **Virtual Reality implementation of the classic Tower of Hanoi puzzle** developed using **Three.js**.

The application allows users to interact with the puzzle in both:

- 💻 **Web (desktop) mode**
- 🥽 **Virtual Reality mode** compatible with Meta headsets and other WebXR-supported devices.

The goal of the game is to move all disks from the first tower to the last one while respecting the classical Tower of Hanoi rules.

---

## 🎯 Features

- Interactive 3D Tower of Hanoi puzzle
- Real-time disk manipulation
- Web-based VR support using WebXR
- Dual mode:
  - Standard browser visualization
  - Immersive VR experience
- Lightweight and fully client-side

---

## 🛠️ Technologies Used

- **Three.js** — 3D rendering engine
- **WebXR API** — VR interaction support
- **JavaScript / HTML / CSS**
- **Meta VR Headsets** (tested on Meta devices)

---

## ▶️ How to Run the Project

Because browsers block local file access for WebXR and modules, you must run the project using a **local server**.

### Step 1 — Install a local server

Run in your terminal:

```bash
npx serve
```

If prompted:

```bash
Need to install the following packages:
serve@14.x.x
Ok to proceed? (y)
```

Type:
```bash
y
```

### Step 2 — Launch the application

Run in your terminal:

Once the server is running:

💻 Web Version

Open:
```bash
index.html
```
This runs the game in standard 3D mode.

🥽 VR Version

Open:
```bash
index_VR.html
```
Then click Enter VR using a compatible headset.

## 🎮 Controls

### Because browsers

* Desktop Mode

* Mouse: rotate view

* Click/drag: move disks

### VR Mode

* Use VR controllers to grab and move disks

## 🎥 Demo

A VR demonstration video is available in this repository.

[VR Demo](./demo/vr_demo.mp4)

## 📚 Academic Context

This project was developed as part of a Virtual Reality coursework project, focusing on:

* Web-based VR interaction

* 3D scene design

* User interaction in immersive environments

## 👨‍💻 Author

Jorge Turriate
MSc in Mechatronics, Machine Vision & AI
Background in Telecommunications Engineering, Computer Vision, and Robotics

## 📄 License

This project is for academic and educational purposes.
