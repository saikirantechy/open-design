<p align="center">
  <img src="https://img.shields.io/badge/Open%20Design-AI-black?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/saikirantechy/open-design-ai?style=for-the-badge&color=yellow" />
  <img src="https://img.shields.io/github/forks/saikirantechy/open-design-ai?style=for-the-badge&color=green" />
  <img src="https://img.shields.io/github/issues/saikirantechy/open-design-ai?style=for-the-badge&color=red" />
  <img src="https://img.shields.io/github/license/saikirantechy/open-design-ai?style=for-the-badge&color=blue" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Multi--Agent-AI-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Design%20Systems-72-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Skills-31-success?style=flat-square" />
  <img src="https://img.shields.io/badge/BYOK-Supported-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/TypeScript-Enabled-blue?style=flat-square&logo=typescript" />
</p>

---

# 🚀 Open Design AI

> **AI-powered multi-agent design workspace for creators, startups, and developers.**
> Local-first · BYOK · Web-deployable · Part of the [SKT Nexus](https://github.com/saikirantechy) ecosystem.

**Open Design AI** is a next-generation AI design engineering platform that combines multi-agent workflows, composable design systems, and a local-first runtime into a single creative operating system.

Whether you're a solo founder, a startup team, or a design engineer — Open Design AI gives you a fully private, customizable AI design workspace powered by your own API keys and coding agents.

```
AI Agents + Design Systems + Prompt Engineering + Local Runtime = Open Design AI
```

Built for: **Creators · Startups · Developers · Designers · AI Builders**

---

## ✨ Features

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
| 📡 **Real-Time Streaming UI** | Live artifact preview as AI generates code |
| 🔌 **MCP Integration** | Model Context Protocol support for agent interop |

---

## ✅ What's Included

- ✅ 16+ AI Coding Agent Integrations
- ✅ 31 Creative AI Skills
- ✅ 72+ Production Design Systems
- ✅ Multi-Provider BYOK Support
- ✅ Real-Time Streaming UI
- ✅ Local-First Architecture
- ✅ Next.js 16 + Electron
- ✅ AI Design Engineering Workflows
- ✅ Artifact Preview & Export
- ✅ MCP Integration Support

---

## 🧩 Supported AI Agents

Open Design AI auto-detects and integrates with:

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
│   ├── web/           # Next.js web interface
│   ├── desktop/       # Electron desktop app
│   ├── daemon/        # Local CLI daemon
│   └── landing-page/  # Marketing site
├── packages/
│   ├── contracts/     # Shared TypeScript contracts
│   ├── platform/      # Core platform logic
│   ├── sidecar/       # AI sidecar runtime
│   └── sidecar-proto/ # Protocol definitions
├── tools/
│   ├── dev/           # Development toolchain
│   └── pack/          # Packaging toolchain
├── design-systems/    # 72+ design system definitions
└── skills/            # 31 AI design skills
```

---

## ⚡ Quick Start

### Prerequisites

- [Node.js 24+](https://nodejs.org/)
- [pnpm 10.33.2+](https://pnpm.io/) — `npm install -g pnpm@10.33.2`
- At least one AI agent CLI installed (Claude Code, Gemini CLI, etc.)

### Installation

```bash
git clone https://github.com/saikirantechy/open-design-ai.git
cd open-design-ai
pnpm install
pnpm tools-dev run web
```

Then open the URL printed in the terminal (e.g. `http://127.0.0.1:61663/`).

### Desktop App

```bash
pnpm tools-dev run desktop
```

---

## 🔑 BYOK Setup

Open Design AI **never stores your API keys in the cloud.** Configure them locally in Settings:

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

## 🛠️ Tech Stack

- **Next.js 16** — Web interface
- **React 18** — UI components
- **TypeScript** — Type safety throughout
- **Electron** — Desktop runtime
- **SQLite** — Local-first data storage
- **Express.js** — Daemon API server
- **MCP** — Model Context Protocol integration
- **esbuild** — Fast bundling

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
# Run web workspace in dev mode
pnpm tools-dev run web

# Type check all packages
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

## 🌐 Share This Project

<p align="center">
  <a href="https://www.reddit.com/submit?url=https://github.com/saikirantechy/open-design-ai&title=Check%20out%20Open%20Design%20AI%20🚀">
    <img src="https://img.shields.io/badge/share%20on-reddit-orange?style=for-the-badge&logo=reddit" />
  </a>
  <a href="https://news.ycombinator.com/submitlink?u=https://github.com/saikirantechy/open-design-ai&t=Open%20Design%20AI">
    <img src="https://img.shields.io/badge/share%20on-hacker%20news-black?style=for-the-badge&logo=ycombinator" />
  </a>
  <a href="https://twitter.com/intent/tweet?url=https://github.com/saikirantechy/open-design-ai&text=Check%20out%20Open%20Design%20AI%20🚀">
    <img src="https://img.shields.io/badge/share%20on-twitter-blue?style=for-the-badge&logo=twitter" />
  </a>
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://github.com/saikirantechy/open-design-ai">
    <img src="https://img.shields.io/badge/share%20on-facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/sharing/share-offsite/?url=https://github.com/saikirantechy/open-design-ai">
    <img src="https://img.shields.io/badge/share%20on-linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

🚀 Help this project reach more developers by sharing it!

---

## ❤️ Contributors

Thanks to all the amazing open-source contributors supporting Open Design AI.

<a href="https://github.com/saikirantechy/open-design-ai/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=saikirantechy/open-design-ai" />
</a>

---

## 👤 Creator

**Sai Kiran BK**
AI Design Engineer · Founder of [SKT Nexus](https://github.com/saikirantechy)
Building the AI-native creative operating system for the next generation of makers.

> *"Design is no longer just visual — it's a conversation between human intent and machine intelligence."*

🔗 LinkedIn: [linkedin.com/in/saikirantech](https://linkedin.com/in/saikirantech)
🐙 GitHub: [github.com/saikirantechy](https://github.com/saikirantechy)

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
