<p align="center">
 <strong>Voxelith — Portable Browser Client</strong><br/>
 A browser-hosted EaglercraftX 1.8 Offline package distributed as a single static HTML file.<br/>
 Designed for simple local use, static hosting, and zero-build deployment.
</p>

<p align="center">
 <img src="./logo.svg" alt="Voxelith Logo" width="220" />
</p>

<p align="center">
 <a href="https://eaglercraft.com">
  <img src="https://img.shields.io/badge/EaglercraftX-1.8-blue" alt="EaglercraftX 1.8" />
 </a>
 <img src="https://img.shields.io/badge/Build-Static%20HTML-success" alt="Static HTML" />
</p>

---

## Overview

Voxelith packages an EaglercraftX 1.8 Offline browser client into a single `index.html` file.

There is no package manager, compilation step, application server, or framework setup required. The project can be opened directly or served by practically any static web server.

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

- EaglercraftX 1.8 Offline client
- Single-file deployment
- No dependency installation
- No package manager
- No build process
- No backend runtime
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

The packaged client is contained inside `index.html`.

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

## Upstream & Attribution

Voxelith does **not** claim authorship of EaglercraftX or Minecraft.

The packaged browser client identifies itself as EaglercraftX 1.8 Offline.

Upstream project:

https://eaglercraft.com

EaglercraftX, Minecraft-related code, assets, names, and trademarks remain the property of their respective authors and rights holders.

Anyone redistributing or modifying the packaged client should review the applicable upstream licensing, distribution terms, and third-party rights.

---

<p align="center">
 <strong>Single file. Static hosting. No build step.</strong>
</p>