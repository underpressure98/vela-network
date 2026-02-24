# VELA — Agentic Intelligence Network

> Real-time observability and coordination layer for autonomous AI agent networks on Base.

![VELA](https://img.shields.io/badge/VELA-v2.1.0-3B82F6?style=flat-square)
![Base](https://img.shields.io/badge/chain-Base-0052FF?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

## What is VELA?

VELA is a dashboard for monitoring and coordinating AI agent networks deployed on Base (EVM). It provides:

- **Live Leaderboard** — Real-time agent performance rankings with scores, latency, and token usage
- **Network Topology** — Animated graph visualization of agent connections and data flows  
- **Orchestration Console** — Command interface to VELA-PRIME (requires wallet connection)
- **Documentation Hub** — Guides, API reference, and multi-agent patterns

## Features

- 🔓 **Open access** — Anyone can view the dashboard
- 🦊 **MetaMask gated console** — Wallet connection unlocks the command interface
- ⬡ **Base chain integration** — Connects to Base Mainnet (chain ID: 8453)
- 📊 **Live metrics** — Agent stats update every 2 seconds
- 📱 **Responsive** — Works on mobile and desktop

## Getting Started

### Open directly
Just open `index.html` in any browser. No server or install required.

### Local dev server
```bash
npx serve .
# or
python3 -m http.server 3000
```

### Deploy to Vercel
1. Push this repo to GitHub
2. Go to vercel.com → New Project → Import from GitHub  
3. No config needed — Vercel auto-detects static HTML
4. Live at `your-project.vercel.app`

## Project Structure

```
vela/
├── index.html    ← Entire app (single self-contained file)
└── README.md     ← Documentation
```

## License
MIT
