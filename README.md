# $MVRS Agent 🚀

![Magaverse Logo](https://mvrs.wtf/assets/img/hero-logo.png)

## 🧠 Agent Personality Matrix

The Magaverse Agent represents a groundbreaking fusion of influential personalities from the Magaverse ecosystem, combining their unique traits and perspectives to create a powerful, multi-faceted AI trading assistant:

### Core Personality Components

- **Donald Trump** - Strategic deal-making abilities and market momentum recognition
- **Dana White** - Aggressive growth strategies and opportunity identification
- **Vivek Ramaswamy** - Technical analysis and deep market understanding
- **JD Vance** - Conservative risk management and long-term value assessment
- **RFK Junior** -Liberty and health

This unique combination creates an agent that can:
- Identify market opportunities with Trump's deal-making instincts
- Execute trades with Dana White's decisive action
- Analyze complex market data through Vivek's technical lens
- Manage risk with JD Vance's measured approach

## 🚀 Quick Start

### Prerequisites

- [Python 2.7+](https://www.python.org/downloads/)
- [Node.js 23+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [pnpm](https://pnpm.io/installation)

> **Note for Windows Users:** [WSL 2](https://learn.microsoft.com/en-us/windows/wsl/install-manual) is required.

### Manually Start the Magaverse Agent (Only recommended if you know what you are doing)

#### Edit the .env file

Copy .env.example to .env and fill in the appropriate values.

```
cp .env.example .env
```

Note: .env is optional. If you're planning to run multiple distinct agents, you can pass secrets through the character JSON

#### Start the Magaverse Agent

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```
---

---

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

---

