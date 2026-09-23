<p align="center">
 <strong>Voxelith — Browser-Based Voxel Client</strong><br/>
 An actively developed browser client inspired by EaglercraftX, with custom modifications and ongoing project-specific development.<br/>
 Distributed as a self-contained static browser build for straightforward hosting, experimentation, and continued iteration.
</p>

<p align="center">
 <img src="./logo.svg" alt="Voxelith Logo" width="220" />
</p>

<p align="center">
 <a href="https://eaglercraft.com">
  <img src="https://img.shields.io/badge/Inspired%20by-EaglercraftX-blue" alt="Inspired by EaglercraftX" />
 </a>
 <img src="https://img.shields.io/badge/Status-Active%20Development-success" alt="Active Development" />
 <img src="https://img.shields.io/badge/Build-Static%20HTML-informational" alt="Static HTML" />
</p>

---

## Overview

Voxelith is an actively developed browser-based voxel client inspired by EaglercraftX and maintained as its own project.

It is **not** intended to be a stock or untouched EaglercraftX Offline distribution. Voxelith includes custom modifications, project-specific changes, and continued development built around the browser-based gameplay foundation.

The current repository is distributed as a self-contained `index.html` build. It can be opened directly or served through a normal static web server without requiring a runtime backend.

## Quick Start

Clone the repository:

```bash
git clone https://github.com/bleonheart/Voxelith.git
cd Voxelith
```

Serve the directory locally:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

For browsers that permit it, `index.html` can also be opened directly from disk.

## Features

- Actively developed and maintained
- Inspired by EaglercraftX rather than distributed as an untouched upstream build
- Custom project-specific modifications and continued iteration
- Self-contained browser deployment
- Single-file distribution in the current repository
- No runtime backend required
- Portable static hosting
- Embedded browser runtime resources
- Suitable for GitHub Pages and conventional static hosts

## Repository Structure

```text
Voxelith/
├── .gitattributes
├── README.md
└── index.html
```

The current Voxelith browser build is contained inside `index.html`.

## Hosting

Because Voxelith is fully static, it can be served through:

- GitHub Pages
- Nginx
- Apache
- Python's built-in HTTP server
- Local static-file servers
- Other static hosting platforms

No server-side application code is required.

## Deployment Example

Using Python:

```bash
python -m http.server 8000
```

Using a conventional web server, place `index.html` in the desired document root and expose it as a normal static page.

## Inspiration & Attribution

Voxelith is inspired by EaglercraftX and may retain technology or components derived from that ecosystem, but it is maintained as an actively developed project with its own modifications and direction.

Voxelith is not presented as the official EaglercraftX distribution and does not claim authorship of EaglercraftX or Minecraft.

Reference project:

https://eaglercraft.com

EaglercraftX, Minecraft-related code, assets, names, and trademarks remain the property of their respective authors and rights holders. Redistribution and modification should respect the applicable upstream licensing, distribution terms, and third-party rights.

---

<p align="center">
 <strong>Inspired by EaglercraftX. Actively developed as Voxelith.</strong>
</p>