# Open Design AI

> **AI-powered multi-agent design workspace for creators, startups, and developers.**  
> Local-first · BYOK · Web-deployable · Part of the [SKT Nexus](https://github.com/saikirantechy) ecosystem.

---

## ✨ What is Open Design AI?

**Open Design AI** is a next-generation AI design engineering platform that combines multi-agent workflows, composable design systems, and a local-first runtime into a single creative operating system.

Whether you're a solo founder, a startup team, or a design engineer — Open Design AI gives you a fully private, customizable AI design workspace powered by your own API keys and coding agents.

```
AI Agents + Design Systems + Prompt Engineering + Local Runtime = Open Design AI
```

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🤖 **Multi-Agent Workflows** | Orchestrate Claude, Gemini, GPT-4, Codex, and 12+ more AI agents |
| 🎨 **72+ Design Systems** | Brand-grade, production-ready UI libraries out of the box |
| 🧠 **31 Composable Skills** | AI skills engine for layout, typography, color, animation & more |
| 🔒 **Local-First Runtime** | All data stays on your machine. No cloud lock-in |
| 🔑 **BYOK (Bring Your Own Key)** | Use your own OpenAI, Anthropic, Google AI keys |
| 🌐 **Web-Deployable** | Run as a local server or deploy to Vercel/Netlify/cloud |
| ⚡ **16 CLI Integrations** | Claude Code, Gemini CLI, Cursor, Copilot, Aider, and more |
| 🖥️ **Desktop + Web** | Electron desktop app + Next.js web interface |

---

## 🧩 Supported AI Agents

Open Design AI detects and integrates with the following coding agents:

- **Claude Code** (Anthropic)
- **Gemini CLI** (Google)
- **GitHub Copilot**
- **Cursor**
- **Aider**
- **Continue**
- **Cody** (Sourcegraph)
- **Amazon Q**
- **Tabnine**
- **Cline**
- **Windsurf**
- **Zed AI**
- **OpenAI Codex**
- **Grok**
- and more...

---

## 🏗️ Architecture

```
open-design-ai/
├── apps/
│   ├── web/          # Next.js web interface
│   ├── desktop/      # Electron desktop app
│   ├── daemon/       # Local CLI daemon
│   └── landing-page/ # Marketing site
├── packages/
│   ├── contracts/    # Shared TypeScript contracts
│   ├── platform/     # Core platform logic
│   ├── sidecar/      # AI sidecar runtime
│   └── sidecar-proto/# Protocol definitions
├── tools/
│   ├── dev/          # Development toolchain
│   └── pack/         # Packaging toolchain
├── design-systems/   # 72+ design system definitions
└── skills/           # 31 AI design skills
```

---

## ⚡ Quick Start

### Prerequisites

- [Node.js 24+](https://nodejs.org/)
- [pnpm 10.33.2+](https://pnpm.io/) (`npm install -g pnpm@10.33.2`)
- At least one AI agent CLI installed (Claude Code, Gemini CLI, etc.)

### Installation

```bash
# Clone the repo
git clone https://github.com/saikirantechy/open-design-ai.git
cd open-design-ai

# Install dependencies
pnpm install

# Start the web workspace
pnpm tools-dev run web
```

Then open the URL printed in the terminal (e.g. `http://127.0.0.1:61663/`).

### Desktop App

```bash
pnpm tools-dev run desktop
```

---

## 🔑 BYOK Setup

Open Design AI never stores your API keys in the cloud. Configure them locally in Settings:

1. Open the app → **Settings** → **AI Providers**
2. Add your keys:
   - `ANTHROPIC_API_KEY` for Claude
   - `GOOGLE_GENERATIVE_AI_API_KEY` for Gemini
   - `OPENAI_API_KEY` for GPT / Codex
3. Select your preferred agent and start designing

---

## 🎨 Design Systems Included

72+ production-grade design systems spanning:

- **SaaS Dashboards** — analytics, admin panels, CRMs
- **E-Commerce** — storefronts, product pages, checkout flows
- **Mobile-First** — responsive layouts, PWA-ready components
- **Startup Landing Pages** — hero sections, pricing tables, CTAs
- **Developer Tools** — code editors, terminal UIs, CLI dashboards
- **AI/ML Interfaces** — chat UIs, prompt workspaces, model comparisons

---

## 🧠 Skills Engine

31 composable AI skills for design automation:

- **Layout** — Grid generation, spacing harmony, responsive breakpoints
- **Typography** — Font pairing, hierarchy, readability scoring
- **Color** — Palette generation, contrast checking, brand theming
- **Components** — Button systems, card layouts, navigation patterns
- **Animation** — Micro-interactions, transitions, scroll effects
- **Accessibility** — WCAG checks, ARIA labels, color contrast

---

## 🗺️ Roadmap

- [ ] **v0.6** — Figma plugin integration
- [ ] **v0.7** — Real-time collaboration (Liveblocks)
- [ ] **v0.8** — One-click Vercel/Netlify deploy
- [ ] **v0.9** — Custom skill marketplace
- [ ] **v1.0** — Open Design AI Cloud (optional hosted tier)

---

## 🛠️ Development

```bash
# Run all packages in watch mode
pnpm tools-dev run web

# Type check
pnpm typecheck

# Run tests
pnpm test
```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your branch: `git checkout -b feature/my-feature`
3. Commit: `git commit -m "Add my feature"`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 👤 Creator

**Sai Kiran BK**  
AI Design Engineer · Founder of [SKT Nexus](https://github.com/saikirantechy)  
Building the AI-native creative operating system for the next generation of makers.

> "Design is no longer just visual — it's a conversation between human intent and machine intelligence."

---

## 📄 License

Apache 2.0 — see [LICENSE](./LICENSE)

---

## 🙏 Credits & Inspiration

This project draws inspiration from the open-source AI design tooling community.  
Built with ❤️ as part of the **SKT Nexus** ecosystem.

---

<div align="center">

**[⭐ Star this repo](https://github.com/saikirantechy/open-design-ai)** · **[🐛 Report a bug](https://github.com/saikirantechy/open-design-ai/issues)** · **[💡 Request a feature](https://github.com/saikirantechy/open-design-ai/issues)**

Made with ❤️ by [Sai Kiran BK](https://github.com/saikirantechy) · SKT Nexus

</div>
