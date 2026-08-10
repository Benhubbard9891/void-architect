# VOID/ARCHITECT — Abyssal Edition

**Reality Stability Protocol v3.1.0**

A single-file, browser-based 3D voxel construction experience set in a collapsed lattice / abyssal void. Built with Three.js (r128). Place and destroy matter fragments, explore floating Echo entities, and reconstruct structure from nothing.

> *The Lattice has collapsed. Matter fragments drift in the Abyss. You are the last Architect.*

## Live Demo

Open `index.html` directly in any modern browser, or host it statically (GitHub Pages, Netlify, Vercel, local server).

**GitHub Pages** (once enabled): `https://benhubbard9891.github.io/void-architect/`

## Features

- **Instanced voxel system** — up to 10 000 blocks across 5 material types
- **Five matter types** with distinct materials and emissive properties:
  - ✦ Lumina Crystal
  - ◆ Void Stone
  - ● Plasma Core
  - ■ Struct Beam
  - ⚛ Quantum Foam
- **First-person physics** — gravity, jumping, collision, head bob
- **Raycast placement / destruction** with visual feedback
- **Ambient starfield + nebula** and dynamic point lights
- **Echo entities** — wandering octahedron agents that react to player proximity
- **Particle effects** on place/destroy/jump
- **Dual input schemes**: Keyboard+Mouse (pointer lock) and full Touch (virtual joystick + look zone + action buttons)
- **Settings panel**: sensitivity, opacity, lighting, CRT scanlines, FPS counter, control scheme override
- **Glassmorphism UI** with CRT vignette overlay aesthetic

## Controls

### Keyboard + Mouse
| Action | Binding |
|--------|---------|
| Move | `W` `A` `S` `D` |
| Jump | `Space` |
| Place | `Q` |
| Destroy | `E` |
| Select material | `1`–`5` |
| Look | Mouse (pointer lock) |
| Menu | `Esc` |

### Touch
- Left virtual joystick — movement
- Right half of screen — look
- Action cluster (bottom-right): Destroy / Place / Jump
- Hotbar slots for material selection

## Technical Notes

- Pure client-side; no build step required
- Three.js loaded from CDN
- InstancedMesh for efficient block rendering
- Exponential fog + ACES tone mapping
- Soft shadows (PCF)
- Responsive layout with mobile-specific scaling

## License

MIT — free to fork, modify, and deploy.

---

*Reconstruct reality. Stabilize the void.*
