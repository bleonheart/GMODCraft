<p align="center">
 <img src="./logo.svg" alt="Voxelith Logo" width="220" />
</p>

<h1 align="center">Voxelith</h1>

<p align="center">
 Browser-based voxel client distributed as a self-contained static build.
</p>

<p align="center">
 <img src="https://img.shields.io/badge/Status-Active%20Development-success" alt="Active Development" />
 <img src="https://img.shields.io/badge/Build-Static%20HTML-informational" alt="Static HTML" />
</p>

## Overview

Voxelith is an actively developed browser-based voxel client with project-specific modifications and its own branding.

The public entry point is `index.html`. The packaged browser runtime is stored in `runtime.html` and is loaded automatically by the Voxelith launcher.

## Quick Start

```bash
git clone https://github.com/bleonheart/Voxelith.git
cd Voxelith
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Features

- Voxelith-branded browser launcher
- Automatic startup with no legacy countdown screen
- Self-contained static deployment
- No runtime backend required
- GitHub Pages compatible
- Portable to conventional static hosts

## Repository Structure

```text
Voxelith/
├── .gitattributes
├── README.md
├── index.html
├── runtime.html
└── logo.svg
```

## Hosting

Voxelith can be served through GitHub Pages, Nginx, Apache, Python's built-in HTTP server, or another static hosting platform.

No server-side application code is required.
