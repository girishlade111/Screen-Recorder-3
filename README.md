# Screen Recorder

A single-file browser-based screen recorder. Capture your screen, window, or tab with optional microphone audio — everything happens locally in the browser using the MediaRecorder API. No signup, no server, no uploads.

## Features

- Screen / window / tab capture via `getDisplayMedia`
- Optional microphone audio
- Live recording timer and status indicator
- Preview and download recordings (WebM)
- Dark/light theme toggle
- Installable (PWA-style install banner)
- Single `index.html` — fully client-side

## Tech Stack

- Single HTML file (HTML + Tailwind CSS + vanilla JS)
- MediaRecorder API + getDisplayMedia

## Quick Start

Open `index.html` in a modern browser (Chrome/Edge recommended) — or serve it:

```bash
npx serve .
```

Click "Start Recording", choose what to share, then stop and download.

> Note: screen capture requires a secure context (HTTPS or localhost). The deployed GitHub Pages version works fine.

## Project Structure

```
├── index.html   # The entire app — capture, timer, preview, download
└── README.md
```

## Deploy

Fully static — host `index.html` on any static host (GitHub Pages, Cloudflare Pages, Netlify).

---

Built by Girish Lade — https://ladestack.in
