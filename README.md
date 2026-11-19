# 🪽 Neon Flap (Flappy Bird Clone)

A vibrant, candy-cosmic reimagining of the classic Flappy Bird arcade game built with pure HTML5 Canvas, CSS3, and Vanilla JavaScript. Zero external libraries, zero frameworks, and zero external sound files!

![Game Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Tech](https://img.shields.io/badge/Tech-HTML5%20Canvas%20%7C%20Vanilla%20JS-orange)
![Theme](https://img.shields.io/badge/Theme-Neon%20Candy%20Cosmic-magenta)
![Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-blueviolet)

---

## ✨ Features

- **🎨 Unique Neon Candy Cosmic Theme:**
  - Say goodbye to the boring green pipes! Features glowing cyan & magenta neon crystal pillars with 3D gradient caps.
  - Twilight sky with twinkling stars, distant gradient parallax mountains, and a glowing sunset moon.
  - Candy striped conveyor ground with smooth motion.
  - Adorable glowing phoenix/candy bird with anime eyes, cheek blush, and animated flapping wings.
- **🎮 Physics & Controls:**
  - Smooth 60fps physics using `requestAnimationFrame`.
  - Velocity-based rotation (bird points up on flap, smoothly dips down when falling).
  - Sparkling particle trail emitted from wings upon each flap.
  - Multi-input support: **Spacebar, Up Arrow, W key, Mouse Click, and Touch/Tap**.
- **📈 Progressive Difficulty:**
  - Base scrolling speed ramps up smoothly as your score increases (challenging reflexes!).
- **💥 Visual & Audio Feedback:**
  - Screen shake effect on crash.
  - Real-time sound synthesis with browser **Web Audio API** (flap whoosh, coin ding chime, collision thud, death drop, and victory fanfare).
  - Sound mute/unmute toggle.
- **🏆 High Score & Medal System:**
  - Persisted locally with `localStorage`.
  - Confetti particle explosion when a new personal best is reached.
  - Medals awarded on Game Over screen based on performance:
    - 🥉 **Bronze Wing** (1+ score)
    - 🥈 **Silver Ace** (10+ score)
    - 🥇 **Gold Champion** (25+ score)
    - 💎 **Diamond Legend** (40+ score)
- **📱 100% Mobile & Touch Responsive:**
  - Canvas scales dynamically across all mobile phones, tablets, and desktop displays without stretching or aspect ratio distortion.

---

## 🚀 Play Online via GitHub Pages

1. Navigate to your repository **Settings** > **Pages**.
2. Under **Build and deployment**, set Source to `Deploy from a branch`.
3. Choose branch `main` and folder `/ (root)`, then click **Save**.
4. Play online at: `https://ishtiyaq8811.github.io/flappy-bird-clone/`

---

## 🛠️ How to Play Locally

Simply open `index.html` in any modern web browser!
