https://kyraprak.github.io/the.matrix-1/

---

# 🦠 The Matrix – HTML/CSS Animation Project

## Overview

**The Matrix** is a lightweight front-end project that recreates a cinematic “Matrix-style” interface using only **HTML and CSS**—no JavaScript required. The project consists of two connected pages: a boot/loading screen and an animated “access granted” screen featuring falling green code reminiscent of *The Matrix* films.

The goal of this project is to explore CSS animations, layout techniques, and visual effects while keeping the implementation simple and performant.

---

## Features

* **Pure HTML & CSS**

  * No JavaScript or external libraries
  * Runs entirely in the browser

* **Boot / Loading Screen**

  * Animated progress bar using CSS keyframes
  * Futuristic terminal-style typography and glow effects
  * “Enter Matrix” call-to-action

* **Matrix Rain Animation**

  * Vertical streams of binary characters
  * Individual animation speeds and positions for variation
  * Glowing green text with depth and motion
  * Foreground content layered cleanly over the animation

* **Responsive & Full-Screen**

  * Uses viewport units (`vh`, `vw`)
  * Scales smoothly across screen sizes
  * No scrolling or layout shifts

---

## Project Structure

```
/index.html       → Boot / loading screen
/matrix.html      → Matrix rain animation + access message
```

Each page is self-contained, with embedded CSS for simplicity and portability.

---

## How It Works

* **CSS Keyframes** drive all animations:

  * Progress bar fill animation
  * Falling “code rain” effect
* **Vertical text flow** is achieved using:

  * `writing-mode: vertical-rl`
  * `text-orientation: upright`
* **Layering** is handled with `z-index`, allowing animated backgrounds without blocking user interaction.
* **Glow effects** are created using `text-shadow` and `box-shadow`.

---

## Purpose

This project was built as:

* A creative experiment with CSS animations
* A demonstration of visual design without JavaScript
* A fun homage to *The Matrix* aesthetic
* A portfolio-ready front-end micro-project

---

## Possible Improvements

* Randomized characters or columns
* JavaScript-driven procedural animation
* Sound effects or timed page transitions
* Mobile-specific optimizations
* Dark/light theme variations

---

## License

This project is open for learning, experimentation, and inspiration.
Feel free to modify or build upon it.

