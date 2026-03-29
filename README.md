<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:b45309,50:fbbf24,100:f59e0b&text=ICONIC%20BEAM&fontColor=ffffff&fontSize=65&fontAlignY=35&desc=by%20AVANT%20ICONIC&descSize=15&descAlignY=50&animation=scaleIn" alt="iconic beam header" width="100%" />

<br />

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=24&pause=1100&color=F59E0B&center=true&vCenter=true&width=980&lines=10+Bespoke+CSS+Nodes+designed+for+maximum+impact.;GPU+optimized+animations+using+CSS+Houdini.;Zero+dependency+visual+energy+for+modern+web+apps." alt="Typing SVG" />

<br />

<video src="video.mov" width="100%" autoplay loop muted controls></video>

<br />
<br />

<p align="center">
  <a href="#overview"><img src="https://img.shields.io/badge/overview-111827?style=for-the-badge&logo=readme&logoColor=white" alt="Overview" /></a>
  <a href="#features"><img src="https://img.shields.io/badge/features-f59e0b?style=for-the-badge&logo=sparkles&logoColor=white" alt="Features" /></a>
  <a href="#technical-breakdown"><img src="https://img.shields.io/badge/tech-d97706?style=for-the-badge&logo=cpu&logoColor=white" alt="Tech" /></a>
  <a href="#getting-started"><img src="https://img.shields.io/badge/getting_started-b45309?style=for-the-badge&logo=rocket&logoColor=white" alt="Getting Started" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/AVANT-ICONIC/iconic-beam?style=flat-square&color=fbbf24" alt="stars" />
  <img src="https://img.shields.io/github/forks/AVANT-ICONIC/iconic-beam?style=flat-square&color=f59e0b" alt="forks" />
  <img src="https://img.shields.io/github/issues/AVANT-ICONIC/iconic-beam?style=flat-square&color=d97706" alt="issues" />
  <img src="https://img.shields.io/github/license/AVANT-ICONIC/iconic-beam?style=flat-square&color=b45309" alt="license" />
  <img src="https://img.shields.io/github/last-commit/AVANT-ICONIC/iconic-beam?style=flat-square&color=92400e" alt="last commit" />
</p>

<p align="center">
  <strong>ICONIC BEAM</strong> is a high-performance visual experiment featuring 10 unique CSS-driven nodes optimized for hardware-accelerated smoothness.
</p>

<p align="center">
  <a href="https://github.com/AVANT-ICONIC/iconic-beam">Repository</a>
  ·
  <a href="index.html">Live Demo</a>
  ·
  <a href="screenshot.png">Screenshot</a>
</p>

</div>

---

## Overview

> **One-line pitch:** A collection of 10 bespoke animation nodes that leverage CSS Houdini and conic gradients to create surgical-precision lighting effects.

Built for the modern web with zero dependencies (Tailwind via CDN for layout). Each node is a standalone visual study in motion, color, and GPU-accelerated rendering.

### Why this exists

Most web loaders and background effects are either too heavy (Lottie/Video) or too simple. `ICONIC BEAM` hits the sweet spot:
- **Lightweight:** Pure CSS/JS logic.
- **High Fidelity:** Conic gradients provide a depth that standard linear gradients can't match.
- **Performant:** Uses `@property` for sub-pixel smooth animations.

---

## Features

<table>
<tr>
<td width="33%">

### Visual Fidelity

- 10 unique animation variants
- Custom glow and pulse states
- Dynamic color mapping
- High-contrast "Bespoke" aesthetic

</td>
<td width="33%">

### Tech Stack

- CSS Houdini (@property)
- Conic Gradients
- Tailwind CSS (Layout)
- Vanilla JS (Generation)

</td>
<td width="33%">

### Performance

- GPU Accelerated
- Low CPU overhead
- Sub-pixel smooth motion
- Zero external assets

</td>
</tr>
</table>

<details>
<summary><strong>Variant Catalog</strong></summary>

<br />

- **PULSE:** High-freq neon blue
- **TWIN FIRE:** Dual-axis combustion
- **TRIPLE NEON:** Multi-spectrum overlap
- **GLACIAL:** Minimalist white resonance
- **RADAR:** Tactical sweep
- **POLICE:** High-alert tactical flash
- **GHOST:** Subtle Slate-gray echo
- **STAR:** Multi-point gold sparkle
- **VOID:** Slow-decay pink resonance
- **TOXIC:** High-energy green/lime decay

</details>

---

## Technical Breakdown

The core of the effect relies on the **CSS Houdini `@property`** API, allowing us to animate custom variables that would otherwise be static.

```css
@property --angle {
    syntax: '<angle>';
    initial-value: 0deg;
    inherits: false;
}
```

By animating the `--angle` across a `conic-gradient`, we achieve a "spinning beam" effect that is rendered directly by the GPU's painting engine rather than a heavy JS loop.

---

## Getting Started

### Run it locally

No build steps. No `npm install`. Just open the file.

```bash
git clone https://github.com/AVANT-ICONIC/iconic-beam.git
cd iconic-beam
open index.html
```

---

## Project Structure

```text
.
├── README.md           # The file you are reading
├── index.html          # The entire application logic
├── video.mov           # Hero showcase
└── screenshot.png      # High-res preview
```

---

## Quality Bar

- **No Mystery Logic:** The CSS is readable and commented.
- **No Heavy Assets:** Everything is procedurally generated.
- **No Jitter:** Tested for 60fps+ on modern displays.

---

<div align="center">

<strong>If these nodes light up your project, a star is a fair trade.</strong>

<br />
<br />

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=130&color=0:b45309,50:fbbf24,100:f59e0b" alt="iconic beam footer" width="100%" />

</div>

