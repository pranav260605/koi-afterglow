# KOI AFTERGLOW — Interactive Digital Pond

A tranquil, interactive web experiment where origami paper koi swim through continuous dark-water currents. Built with vanilla HTML5 Canvas 2D and CSS. Inspired by the interaction patterns of [Noise Garden](https://github.com/NathanRullier/noise-garden) by Nathan Rullier.

## Features
- **Procedural Origami Rendering**: Origami fish crafted dynamically via Canvas 2D polygon path drawing featuring multi-faceted body geometry, side fins, tail fins, and paper fold lines.
- **Boids Steering Physics**: Smooth flocking algorithms combined with dynamic pointer wakes and water disturbance repulsion.
- **Interactive Water Ripples**: Click or tap anywhere on the canvas to emit physical expanding wave ripples that bend the swimming trajectories of nearby koi.
- **Scene Speed Controls**: Toggle between **Stillness** (calm, slow drift) and **Current** (normal flow speed).
- **Optional Sound Mode**: Micro-reactive Web Audio analyzer mode that alters koi swimming speeds based on live ambient audio levels.
- **Responsive & Accessible**: Auto-adapts to retina/mobile screens and respects the browser's `prefers-reduced-motion` settings.

## Controls
- **Mouse Movement**: Move the cursor across the pond to stir wakes and guide nearby fish.
- **Click / Tap**: Click anywhere to emit expanding circular ripples.
- **Stillness**: Reduces swimming speed to create a calm, restful state.
- **Current**: Restores normal, fluid swimming velocity.
- **Pause / Resume**: Freezes and resumes the canvas animation loop.
- **Reset**: Re-initializes the school positions and clears active water ripples.
- **Sound Mode**: Requests optional microphone access to drive fish speeds with ambient audio.

## Technology Stack
- **Language**: Standard HTML5, CSS3, JavaScript (ES6+)
- **Graphics Engine**: HTML5 Canvas 2D Context
- **Audio Engine**: Web Audio API (`AudioContext`, `AnalyserNode`)
- **Dependencies**: None (Zero build step, zero third-party packages)

## Running Locally
1. Clone or download this repository to your computer.
2. Open the project folder in Visual Studio Code.
3. Launch `index.html` directly in any web browser, or use the VS Code **Live Server** extension.

## Deployment to GitHub Pages
This project includes a pre-configured GitHub Actions workflow in `.github/workflows/pages.yml`.

1. Push your changes to the `main` branch of your GitHub repository.
2. In GitHub, navigate to **Settings** -> **Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. The site will deploy automatically to `https://<your-username>.github.io/<repository-name>/`.

## Attribution & License
- Inspired by [Noise Garden](https://github.com/NathanRullier/noise-garden) by Nathan Rullier.
- License: MIT open license.