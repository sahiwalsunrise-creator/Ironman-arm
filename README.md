# Robot Arm 3D: Interactive Industrial Robotic Arm in Three.js

> A real-time 3D scene of a futuristic industrial robotic arm mounted on a wheeled base, built with Three.js and Vite. Articulated joints, dynamic lighting and orbit controls, running in any modern browser.

[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://get.webgl.org/)

![Robotic arm scene](https://github.com/user-attachments/assets/dafd8cfb-338f-4ce5-9ea3-1d172109ac00)

## What it does

An interactive WebGL scene featuring a multi-joint industrial robot arm on a mobile wheeled platform. Drag to orbit the camera, scroll to zoom, and watch the arm articulate through its range of motion with realistic materials and lighting.

## Features

- **Articulated joints**: multi-segment arm with a believable range of motion
- **Orbit controls**: click and drag to rotate, scroll to zoom, right-drag to pan
- **Dynamic lighting**: real-time shadows and metallic material response
- **Wheeled base**: full mobile platform, not just a floating arm
- **Runs anywhere**: pure WebGL, no plugins, works on desktop and mobile browsers

## Getting started

### Prerequisites

Node.js 18 or newer.

### Installation

```bash
git clone https://github.com/AnubhavChaturvedi-GitHub/Iron-Man-Robot-Hand.git
cd Iron-Man-Robot-Hand
npm install
npm run dev
```

Open the localhost URL that Vite prints.

### Build

```bash
npm run build
npm run preview
```

The static bundle lands in `dist/` and can be hosted on GitHub Pages, Netlify or Vercel.

## Controls

| Input | Action |
|---|---|
| Left click and drag | Orbit the camera |
| Scroll wheel | Zoom in and out |
| Right click and drag | Pan the view |

## Project structure

```
index.html     page shell and canvas
main.js        scene, geometry, lighting, animation loop
style.css      layout and page styling
```

## Tech stack

Three.js, Vite, vanilla JavaScript, WebGL.

## Contributing

Issues and pull requests are welcome.

## License

See the repository license file.

## Author

**Anubhav Chaturvedi**, founder of [NetHyTech](https://www.youtube.com/@NetHyTech), a developer community of 30,000+ members.

[![YouTube](https://img.shields.io/badge/YouTube-NetHyTech-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@NetHyTech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anubhav-chaturvedi-/)

If this project saved you time, a star on the repo helps other people find it.
