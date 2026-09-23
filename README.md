<p align="center">
 <strong>GMODCraft</strong><br/>
 A self-contained browser-hosted copy of EaglercraftX 1.8 Offline.<br/>
 Packaged as a single static HTML file for simple local use or static-site hosting.<br/>
</p>

<p align="center">
 <a href="https://eaglercraft.com">
  <img src="https://img.shields.io/badge/EaglercraftX-1.8-blue" alt="EaglercraftX 1.8" />
 </a>
</p>

<h1 align="center">GMODCraft</h1>

---

## Overview

GMODCraft contains a single-file EaglercraftX 1.8 Offline browser client.

The repository is designed to make the client easy to:

- Open locally
- Host as a static page
- Keep as a portable single-file build
- Deploy through services such as GitHub Pages

No compilation or project build process is required.

## Quick Start

Clone the repository:

```bash
git clone https://github.com/bleonheart/GMODCraft.git
cd GMODCraft
```

You can open `index.html` directly in a browser or serve the directory locally:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Features

- EaglercraftX 1.8 Offline client
- Single self-contained `index.html`
- No package manager
- No build system
- No server-side runtime required
- Suitable for static hosting
- Embedded browser client resources
- Relay configuration included in the packaged client

## Repository Structure

```text
GMODCraft/
└── index.html
```

The HTML file contains the packaged EaglercraftX client and its embedded runtime resources.

## Hosting

Because the project is completely static, it can be hosted with any normal static-file server.

Examples include:

- GitHub Pages
- Nginx
- Apache
- Python's built-in HTTP server
- Other static web hosting platforms

## Upstream & Attribution

This repository does **not** claim authorship of EaglercraftX.

The packaged client identifies itself as **EaglercraftX 1.8 Offline** and references the Eaglercraft project:

https://eaglercraft.com

EaglercraftX and Minecraft-related code, assets, names, and trademarks belong to their respective authors and rights holders. Review the applicable upstream terms before redistributing or modifying the packaged client.
