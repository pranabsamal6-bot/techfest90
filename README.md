# Techfest ’26 – Fly Through the Orbit

A 3D, scroll-driven website concept for Techfest IIT Bombay, built with plain HTML, CSS and Three.js (no build step).

## Concept
Scrolling flies the camera along a curved path through one continuous 3D world. Each section is a stop on the journey.

| Stop | What you see |
|------|--------------|
| Hero | Wireframe torus knot with a glowing core, tilts with the mouse |
| About | Three nested, counter-rotating wireframe shells |
| Arenas | Five interactive solids: Robotics, AI and Data, Hackathon, Astronomy, Design |
| Stats | Counters that count up when reached |
| Register | Fly through seven glowing rings |

## Features
- 3D scroll animation: camera path, sway and roll tied to scroll progress
- Interactive objects: raycaster hover (enlarge, glow, name tooltip) and click (pulse ring, info panel)
- Dynamic transitions: background and fog colour blend between sections, reveal animations, progress bar and section dots
- Responsive layout (phones included) and reduced-motion support

## Tech
- HTML, CSS, JavaScript
- [Three.js r128](https://threejs.org/) loaded from cdnjs

## Run locally
1. Download `index.html`.
2. Open it in a modern browser (internet needed to load Three.js).

## Host on GitHub Pages
1. Create a repo and add `index.html` and `README.md`.
2. Go to Settings > Pages, choose the `main` branch and root folder, and save.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Controls
- Scroll: fly forward
- Mouse move: tilt the world
- Hover a solid: see its name
- Click a solid: pulse and open details

## Author
pranabsamal, Bhadrak Autonomous College – Techfest IIT Bombay campus ambassador task.
