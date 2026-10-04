# 🐠 Aquarium 3D Ultra

An interactive, photorealistic 3D aquarium simulation built with Three.js and WebGL.

![Aquarium 3D Preview](https://images.unsplash.com/photo-1522069169874-c58ec4b76be5?w=1200&q=80)

## ✨ Features

- **Anatomical 3D Fish Models**:
  - 🐠 **Ocellaris Clownfish (Amphiprion ocellaris)**: Vibrant orange body, accurate white bars with dark borders, rounded fins.
  - 🐟 **Blue Tang (Paracanthurus hepatus)**: Royal blue body, black palette swirl pattern, and bright yellow tail wedge.
  - 🐡 **Turquoise Discus (Symphysodon)**: Majestic tall disc profile with intricate iridescent striations and ruby eyes.
  - ⚡ **Neon Tetras (Paracheirodon innesi)**: Schooling fish with electric luminous cyan stripe and fiery carmine-red lower body.
- **Hydrodynamic Swimming Kinematics**:
  - Propulsive traveling-wave spine undulation (head remains steady while caudal fin produces realistic thrust).
  - Dynamic turning curvature: fish realistically bend into turns.
  - Banking tilt when executing sharp maneuvers.
  - Fluttering pectoral fins and flexible caudal fin phase lag.
- **Underwater Ecosystem**:
  - Swaying aquatic plants (Vallisneria and grass) reacting to water currents.
  - Sculpted organic reef rocks with moss layers and smooth river pebbles.
  - Dynamic animated water caustics dancing on the sandy floor.
  - Volumetric godrays and atmospheric depth fog.
  - Continuous rising aeration bubble streams (🫧) with pop physics.
- **Interactivity**:
  - **Feeding**: Click anywhere in the tank or tap "Покормить рыбок" to drop food flakes; fish actively detect and swim to eat the flakes.
  - **3 Lighting Modes**: ☀️ Day, 🌅 Sunset, and 🌙 Neon Night.
  - **Camera Modes**: Orbit inspection, cinematic fish tracking (Follow camera), and front perspective.
  - **Synthesized Ambient Audio**: Relaxing procedural underwater bubbling and drone sound effects powered by Web Audio API.

## 🚀 Getting Started

Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari) — no build step or dependencies required!

```bash
# Or run with any static server:
npx serve .
```

## 🛠️ Tech Stack

- HTML5 / CSS3 (Glassmorphism UI)
- Vanilla JavaScript
- [Three.js](https://threejs.org/) (WebGL rendering, PCFSoftShadowMap, ACESFilmicToneMapping)
- Web Audio API (procedural aquatic audio synthesis)
