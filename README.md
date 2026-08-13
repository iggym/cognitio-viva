# cognitio-viva

# Cognitio Viva

> **Living Interactive Cognition** — A lightweight, zero-dependency engine for serving animated web experiences driven by a `json` database and cognitive neuroscience parameters.

---

## Overview

**Cognitio Viva** is an automated interactive publishing system hosted on GitHub Pages. It translates high-impact scientific, system, and philosophical concepts into standalone, highly engaging single-file web experiences (`.html`). 

Content is generated using a parameterized **Neuroscience Prompt** that targets 10 cognitive mechanisms (novelty interrupts, curiosity loops, embodied simulation, agency ladders, and pattern breaks) to maximize retention, engagement, and shareability.

---

## Architecture Constraints

* **Zero Dependencies:** No frameworks (React/Vue/Svelte), build tools (Vite/Webpack), or node_modules.
* **Single-File Artifacts:** Each experience is an isolated HTML file containing embedded CSS and JS.
* **Client-Side Portal:** The discovery interface is a static `index.html` file fetching `database.json` via standard Fetch API.
* **GitHub Pages Native:** Deploys instantly via static file hosting without compilation steps or build pipelines.

---

## Directory Structure

```text
cognitio-viva/
├── index.html          # Main portal (vanilla JS gallery + iframe modal preview)
├── database.json       # Master database of experience metadata & neuro-parameters
├── README.md           # Repository documentation
└── artifacts/          # Generated standalone interactive experiences
    ├── sleep-glymphatic-cleansing.html
    ├── quantum-double-slit.html
    └── tragedy-of-the-commons.html
