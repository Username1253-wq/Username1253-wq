# 🌐 Ai Smash Bros

A zero-player, fully autonomous 2D platform fighter simulation inspired by *Super Smash Bros*. Built entirely in vanilla JavaScript and HTML5 Canvas inside a single file. Two distinct AI agents battle endlessly on a floating stage using linear physics, directional state loops, and instant knockback scaling vectors.

---

## 🚀 Quick Start

Because this project uses vanilla technologies, it requires **no installation, no Node.js dependencies, and no local build steps**.

All you need to do is go here to launch the game:
---

## 🎮 Features

- **Autonomous FSM Engine:** Both bots operate on an automated Finite State Machine (FSM) determining tactical states like `IDLE`, `APPROACH`, `ATTACK`, `HITSTUN`, and `RECOVER`.
- **Smash Netcode Physics:** Implements genuine platform fighter knockback physics where `Force = Damage Percentage * Move Power / Weight`. High percentages mean massive velocity spikes.
- **Dynamic Control Dashboard:** Adjust Aggression rates and Weight mass metrics on the fly using HTML5 range sliders to watch immediate playstyle evolutions.
- **Visual Juice Particles:** Built-in impact particle systems and color shifts immediately highlight when critical strikes land.

---

## 📁 Architecture Overview

Everything is contained neatly inside a single ecosystem for frictionless editing:


Fully vibecoded with Deepseek v4.1 flash.
