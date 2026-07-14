# Git Agents

### 🤖 Deploy Autonomous AI Agents

*A platform for deploying, sharing, and monetizing autonomous AI agents*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange?style=for-the-badge)](CONTRIBUTING.md)

[🌐 Website](#) · [🐛 Report Bug](../../issues/new?template=bug_report.md) · [💡 Request Feature](../../issues/new?template=feature_request.md)

---

## 📌 About

Git Agents is a landing page and platform concept for deploying autonomous AI agents — think of it as a marketplace where agents can be built, forked, and run by the community, with usage tracked on-chain via a native token (GIT).

This repository contains the front-end landing page, including:

- Marketing hero section with animated background
- Live activity feed simulation
- Pricing section
- Full login / register authentication UI (demo, in-memory only — no real backend)

## 🚀 Quick Start

Clone the repository and open `index.html` directly in your browser — no build step required.

```bash
git clone https://github.com/<your-username>/Git-Agents.git
cd Git-Agents
open index.html   # or just double-click the file
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 📂 Project Structure

```
Git-Agents/
├── .github/            # Issue templates & community health files
├── docs/               # Additional documentation
├── assets/             # Images, icons, and other static assets
├── index.html          # Main landing page (single-file HTML/CSS/JS)
├── CONTRIBUTING.md      # Contribution guidelines
├── CODE_OF_CONDUCT.md   # Community code of conduct
├── SECURITY.md          # Security policy
└── README.md            # You are here
```

## ⚠️ Note on the Demo Auth System

The login/register flow in `index.html` is a **front-end only demo**. Accounts are stored in memory (a plain JavaScript object) and reset on every page reload. Do **not** use this as-is for a real production authentication system — you'll need a real backend, hashed passwords, and secure session handling before deploying this publicly.

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

## 📄 License

Licensed under the [MIT License](LICENSE).

---

**⭐ If this project helps you, consider starring the repo!**
