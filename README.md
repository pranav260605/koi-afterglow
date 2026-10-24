# 🐟 Chroma Afterglow

*A 60-minute creative coding sprint to turn a blank canvas into a living digital pond.*

I stumbled across the idea of interactive particle systems and wondered: what if instead of generic dots or glowing orbs, we had something that felt organic? Something with an actual head, tail, and fluid movement? 

One hour, zero frameworks, and a lot of Canvas 2D math later, **Chroma Afterglow** was born. It's a lightweight, interactive web experiment where procedural koi fish swim through a simulated current that responds to your mouse movements and clicks. 

No React. No Three.js. No `npm install`. Just pure vanilla JavaScript and a bit of boids flocking algorithm magic.

## ✨ What's happening on screen?
* **Procedural Koi:** Every fish is drawn on the fly using curved paths (quadratic curves for the win) so their tails actually sweep and wiggle based on their current velocity.
* **Flocking (Boids):** The fish naturally group up, align their swimming direction, and avoid crashing into each other.
* **Fluid Interaction:** Moving your cursor stirs the water, leaving a fading wake that gently pushes and pulls the school. Clicking or tapping drops a ripple that scatters them.
* **Micro-reactive:** There's an experimental (and entirely optional) Sound Mode that ties their swimming speed to the ambient noise in your room.

## 🚀 How to run this (It's stupidly simple)
Because I wanted to keep this purely static without any local servers or build steps:
1. Clone this repo or download the ZIP.
2. Double-click `index.html` to open it in your browser.
3. That's literally it.

## 🛠️ Tech Stack
* **HTML5 Canvas 2D** (Doing all the heavy lifting)
* **Vanilla JavaScript** (ES6 classes and vector math)
* **CSS3** (CSS variables and backdrop-filters for the glass UI)
* Deployed straight to GitHub Pages via Actions.
