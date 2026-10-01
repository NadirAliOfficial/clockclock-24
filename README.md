# ClockClock 24 — Kinetic Time Sculpture

A recreation of the iconic kinetic clock sculpture **ClockClock 24** (inspired by *Humans since 1982*), built entirely in a single, zero-dependency HTML file.

24 individual analog clock faces arranged in an 8-column × 3-row grid work in synchronized harmony to display the time digitally through geometric hand alignments and mesmerizing fluid choreographies.

![ClockClock 24 Preview](https://img.shields.io/badge/Design-Humans_since_1982-black?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Pure Web Tech](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-orange?style=flat-square)

---

## Features

- **Precision Kinetic Time Display**:
  - 24 analog clocks forming 4 digits (`HH:MM`).
  - Digits 0–9 mapped to precise geometric angles with smooth shortest-path rotation.
  - Supports both **12-Hour format** (`12:xx AM/PM`) and **24-Hour format** (`00:xx`).
  - Pulsing colon indicator and synchronized second ticking.

- **Kinetic Ballet Choreographies**:
  - **Cosmic Wave**: Diagonal propagating waves across all 24 dials.
  - **Vortex Swirl**: Concentric circular swirl radiating from the matrix center.
  - **Windmill Spin**: High-speed synchronous and counter-rotating row sweeps.
  - **Kaleidoscope**: Expanding and contracting geometric flower rings.
  - **Chaos to Order**: Random multi-speed rotations that gradually decelerate and lock into the exact current time.

- **4 Display & Interactive Modes**:
  - **Time Mode**: Live real-time clock with smooth minute transitions.
  - **Ambient Art Screensaver**: Continuous generative choreography loop for ambient wall or desk displays.
  - **Interactive Cursor Follow**: Hands dynamically orient and follow the mouse cursor; clicking any clock sends a radial wave outward.
  - **World Clocks Mode**: Each of the 24 clocks acts as an independent analog timepiece for 24 major global cities (Tokyo, London, New York, Sydney, Dubai, etc.).

- **Acoustic Precision**:
  - Synthesized physical micro-stepper motor clicks and soft whirs powered by the **Web Audio API** (toggle with Sound button or <kbd>M</kbd>).

- **4 Luxury Themes**:
  - **Matte Black**: Museum gallery dark mode.
  - **Studio White**: Signature minimalist white edition.
  - **Luxury Brass**: Rich walnut background with warm brushed brass hands.
  - **Cyberpunk**: Neon cyan glow over deep navy.

- **Layout Customization**:
  - **Separated**: Digit spacing with central colon dots.
  - **Monolith 8x3**: Seamless, monolithic continuous grid.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| <kbd>Space</kbd> | Trigger Kinetic Ballet Dance |
| <kbd>T</kbd> | Cycle Visual Themes |
| <kbd>M</kbd> | Toggle Stepper Motor Sound |
| <kbd>F</kbd> | Toggle Fullscreen Mode |
| *Click Clock* | Radial wave originating from clicked dial |

---

## Quick Start

Open `index.html` directly in any web browser. No build steps, bundlers, servers, or external libraries required.

```bash
open index.html
```

---

## License

MIT License. Designed as an artistic web hommage inspired by the original ClockClock 24 sculpture by *Humans since 1982*.
