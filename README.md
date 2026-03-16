 <p align="center">
  <a href="https://github.com/ishaan1201/Pulse">
    <img src="https://github.com/ishaan1201/Pulse/blob/main/public/assets/512.png?raw=true" alt="Pulse Logo" width="150px">
  </a>
</p>

<h1 align="center">Pulse</h1>

<p align="center">
  <strong>An open-source, privacy-respecting, ad-free music app.</strong>
</p>

<p align="center">
  <a href="https://github.com/ishaan1201/Pulse">Website</a> -
  <a href="https://ko-fi.com/monochromemusic">Donate</a> -
  <a href="#features">Features</a> -
  <a href="#usage">Usage</a> -
  <a href="#self-hosting">Self-Hosting</a> -
  <a href="CONTRIBUTING.md">Contributing</a>
</p>

<p align="center">
  <a href="https://github.com/ishaan1201/Pulse/stargazers">
    <img src="https://img.shields.io/github/stars/ishaan1201/Pulse?style=for-the-badge&color=ffffff&labelColor=000000" alt="GitHub stars">
  </a>
  <a href="https://github.com/ishaan1201/Pulse/forks">
    <img src="https://img.shields.io/github/forks/ishaan1201/Pulse?style=for-the-badge&color=ffffff&labelColor=000000" alt="GitHub forks">
  </a>
  <a href="https://github.com/ishaan1201/Pulse/issues">
    <img src="https://img.shields.io/github/issues/ishaan1201/Pulse?style=for-the-badge&color=ffffff&labelColor=000000" alt="GitHub issues">
  </a>
</p>

---

## What is Pulse?

**Pulse** is an open-source, privacy-respecting, ad-free [TIDAL](https://tidal.com) web UI, built on top of Hi-Fi. It provides a beautiful, minimalist interface for streaming high-quality music without the clutter of traditional streaming platforms.

<p align="center">
  <a href="https://github.com/ishaan1201/Pulse">
    <img width="2559" height="1439" alt="Image of 'NASIR' By Nas On Pulse" src="https://i.samidy.xyz/NASIR.png"  alt="Pulse UI" width="800">
  </a>
</p>

<p align="center">
  <a href="https://github.com/ishaan1201/Pulse">
    <img width="2559" height="1439" alt="Image of 'Jump Out' By Osamason On Pulse" src="https://i.samidy.xyz/jumpout.png"  alt="Pulse UI" width="800">
  </a>
</p>

---

## Features

### Audio Quality

- High-quality High-Res/lossless audio streaming
- Support for local music files
- API caching for improved performance

### Interface

- Dark, minimalist interface optimized for focus
- Animated Album Covers For Supported Albums
- High-quality Music Videos
- Customizable themes & Community Theme Store
- Accurate and unique audio visualizer
- Offline-capable Progressive Web App (PWA)
- Media Session API integration for system controls

### Library & Organization

- Recently Played tracking for easy history access
- Comprehensive Personal Library for favorites
- Queue management with shuffle and repeat modes
- Playlist import from other platforms
- Public playlists for social sharing
- Smart recommendations for new songs, albums & artists
- Infinite Recommendation Radio
- Explore Page (Hot & New) for discovering newly added music and whats trending overall or within each genre

### Lyrics & Metadata

- Lyrics support with karaoke mode
- Genius integration for lyrics
- Track downloads with automatic metadata embedding

### Integrations

- Account system for cross-device syncing
- Customizable & Public Profiles
- Last.fm and ListenBrainz integration for scrobbling
- Unreleased music from [ArtistGrid](https://artistgrid.cx)
- Dynamic Discord Embeds
- Artist Biography + Social Links for learning more about your favorite artists
- Multiple API instance support with failover

### Power User Features

- Keyboard shortcuts & Command Palette (CTRL+K) for power users

---

## Quick Start

### Live Instance

Our Recommended way to use Pulse is through our official instance:

**[monochrome.tf](https://monochrome.tf)** / **[monochrome.samidy.com](https://monochrome.samidy.com)**


For alternative instances, check [INSTANCES.md](INSTANCES.md).

---

## Self-Hosting

### Option 1: Docker (Recommended)

```bash
git clone https://github.com/ishaan1201/Pulse.git
cd pulse
docker compose up -d
```

Visit `http://localhost:3000`

### Option 2: Manual Installation

#### Prerequisites

- [Bun](https://bun.sh/) (Preferred) or [Node.js](https://nodejs.org/) (Version 20+ or 22+ recommended)

#### Local Development

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ishaan1201/Pulse.git
    cd pulse
    ```

2. **Install dependencies:**

    ```bash
    bun install
    # or
    npm install # NPM is included with Node.js
    ```

3. **Start the development server:**

    ```bash
    bun run dev
    # or
    npm run dev
    ```

4. **Open your browser:**
   Navigate to `http://localhost:5173/`

#### Building for Production

```bash
bun run build
# or
npm run build
```

---

## Usage

### Basic Usage

1. Visit the [Website](https://monochrome.tf) or your local development server
2. Search for your favorite artists, albums, or tracks
3. Click play to start streaming
4. Use the media controls to manage playback, queue, and volume

### Keyboard Shortcuts

| Shortcut      | Action                       |
| ------------- | ---------------------------- |
| `Space`       | Play / Pause                 |
| `→`           | Seek forward 10s             |
| `←`           | Seek backward 10s            |
| `Shift` + `→` | Next track                   |
| `Shift` + `←` | Previous track               |
| `↑`           | Volume up                    |
| `↓`           | Volume down                  |
| `M`           | Mute / Unmute                |
| `S`           | Toggle shuffle               |
| `R`           | Toggle repeat                |
| `Q`           | Open queue                   |
| `L`           | Toggle lyrics                |
| `/`           | Focus search                 |
| `Esc`         | Close modals                 |
| `[`           | Previous visualizer preset   |
| `]`           | Next visualizer preset       |
| `\`           | Toggle visualizer auto-cycle |
| `Ctrl` + `K`  | Command Palette              |

### Account Features

To sync your library, history, and playlists across devices:

1. Click the "Accounts" Section
2. Sign in with Google or Email
3. Your data will automatically sync across all devices

---

## Contributing

We welcome contributions from the community! Please see our [Contributing Guide](CONTRIBUTING.md) for:

- Setting up your development environment
- Code style and linting
- Project structure
- Before You Contribute
- Commit message conventions
- Deployment information

---

<p align="center">
  <a href="https://fmhy.net/audio#streaming-sites">
    <img src="https://raw.githubusercontent.com/ishaan1201/Pulse/refs/heads/main/public/assets/asseenonfmhy880x310.png" alt="As seen on FMHY" height="50">
  </a>
</p>

<p align="center">
  <a href="https://notbyai.fyi">
    <img src="https://i.samidy.xyz/Developed-By-Humans-Not-By-AI-Badge-black%402x.png" alt="Developed by Humans" height="50">
  </a>
</p>

<p align="center">
  Made with ❤️ by the Pulse team
</p>

## Star History

<a href="https://www.star-history.com/#ishaan1201/Pulse&type=date&logscale&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ishaan1201/Pulse&type=date&theme=dark&logscale&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ishaan1201/Pulse&type=date&logscale&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ishaan1201/Pulse&type=date&logscale&legend=top-left" />
 </picture>
</a>
