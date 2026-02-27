# TorlyAI Desktop

AI-powered business plan assistant for **UK Innovator Founder Visa** applications.

TorlyAI Desktop gives you a team of 6 specialized AI agents that work together to research your market, write your business plan, build financial projections, and prepare you for endorsement body interviews — all running locally on your machine with full privacy.

[**中文版 →**](README.zh-CN.md)

---

## Download

Visit **[torly.ai/download](https://torly.ai/download)** for the latest release, or download directly below:

| Platform | Architecture | Download |
|----------|-------------|----------|
| macOS | Apple Silicon (M1/M2/M3/M4) | [TorlyAI-arm64.dmg](https://github.com/torlyai/desktop/releases/latest) |
| macOS | Intel | [TorlyAI-x64.dmg](https://github.com/torlyai/desktop/releases/latest) |
| Windows | x64 | [TorlyAI-Setup.exe](https://github.com/torlyai/desktop/releases/latest) |

---

## Installation — macOS

### Step 1: Check which Mac you have

Click the **Apple menu** () in the top-left corner of your screen → **About This Mac**.

- If it says **Apple M1**, **M2**, **M3**, or **M4** → download `TorlyAI-arm64.dmg`
- If it says **Intel** → download `TorlyAI-x64.dmg`

### Step 2: Download and install

1. Click the download link above for your Mac type.
2. Once downloaded, find the `.dmg` file in your **Downloads** folder and **double-click** it. A window opens showing the TorlyAI icon and an Applications folder.
3. **Drag the TorlyAI icon** onto the Applications folder.
4. Close the installer window.
5. You can now eject the TorlyAI disk image from Finder's sidebar.

### Step 3: Launch TorlyAI

Open TorlyAI using one of these methods:

- **Spotlight (fastest):** Press `Cmd + Space`, type `TorlyAI`, press `Enter`
- **Finder:** Open **Finder** → **Applications** → double-click **TorlyAI**
- **Launchpad:** Click the Launchpad icon in your Dock, find TorlyAI

### Step 4: First-launch security (unsigned builds only)

> **Note:** Signed and notarized releases will open without any warnings. Skip this step if the app opens normally.

If macOS shows: _"TorlyAI can't be opened because it is from an unidentified developer"_

**Method A — System Settings (recommended):**
1. Open **System Settings** (click  → System Settings)
2. Click **Privacy & Security** in the sidebar
3. Scroll down — you'll see a message about TorlyAI being blocked
4. Click **Open Anyway**
5. Enter your Mac password when prompted
6. TorlyAI will now open normally every time

**Method B — Right-click:**
1. Find TorlyAI in your Applications folder
2. **Right-click** (or hold `Control` and click) the app icon
3. Click **Open** from the menu
4. Click **Open** again in the confirmation dialog

---

## Installation — Windows

### Step 1: Download the installer

Click the **TorlyAI-Setup.exe** download link in the table above.

Your browser may show a warning — this is normal for new software:
- **Chrome:** Click the `^` arrow next to the download → **Keep**
- **Edge:** Click **Keep** → **Keep anyway**
- **Firefox:** Click **OK** to save

### Step 2: Run the installer

1. Open your **Downloads** folder (press `Win + E`, then click **Downloads** in the sidebar).
2. **Double-click** `TorlyAI-Setup.exe`.

3. **Windows SmartScreen warning** — If you see _"Windows protected your PC"_:
   - Click **More info** (the small blue text link)
   - Click **Run anyway**
   - This warning appears for new software and goes away once we have enough installations for Microsoft to trust the certificate.

4. **Installation options:**
   - Choose your preferred installation folder (the default location is fine)
   - Leave "Create desktop shortcut" and "Create Start Menu shortcut" checked
   - Click **Install**

5. Installation takes about 10-30 seconds. Click **Finish** when done.

### Step 3: Launch TorlyAI

Open TorlyAI using one of these methods:

- **Desktop shortcut:** Double-click the **TorlyAI** icon on your Desktop
- **Start Menu:** Click the **Start** button (or press `Win` key), type `TorlyAI`, click the app
- **Taskbar pin (recommended):** Right-click the Desktop shortcut → **Pin to taskbar** for one-click access

> **Note:** TorlyAI installs to your user folder (`%LOCALAPPDATA%\Programs\TorlyAI`), so no administrator rights are needed. No `Program Files` access required.

---

## Setup Wizard

When TorlyAI launches for the first time, the **Setup Wizard** guides you through everything you need:

| Step | What Happens |
|------|--------------|
| 1. **Welcome** | Introduction to TorlyAI and what it can do |
| 2. **Provider** | Choose your AI provider (Anthropic Claude, ChatGPT, Copilot, Google, local models) |
| 3. **Credentials** | Enter your API key or sign in with one-click OAuth |
| 4. **Workspace** | Name your project and pick a folder to store your work |
| 5. **Profile** | Your name, country, and business context |
| 6. **Journey** | Animated walkthrough of the 6-phase endorsement workflow |
| 7. **AI Team** | Meet your 6 AI agents and learn what each one does |
| 8. **Quick Start** | Choose your first action — discover an idea, seed tasks, or jump into chat |

You can re-run the wizard anytime from **Settings** → **Re-run Setup Wizard**.

---

## Getting an API Key

TorlyAI is a **BYOK (Bring Your Own Key)** application — you use your own AI provider account. The Setup Wizard helps you configure this, but here's a quick reference:

### Anthropic Claude (recommended)

1. Go to [console.anthropic.com](https://console.anthropic.com/)
2. Create an account or sign in
3. Click **API Keys** in the sidebar → **Create Key**
4. Copy the key (it starts with `sk-ant-`)
5. Paste it into TorlyAI when the Setup Wizard asks for your credentials

### Other providers

| Provider | How to get credentials |
|----------|----------------------|
| **ChatGPT Plus/Pro** | One-click OAuth sign-in (no API key needed) |
| **GitHub Copilot** | One-click OAuth sign-in (no API key needed) |
| **Google AI Studio** | Get API key from [aistudio.google.com](https://aistudio.google.com/) |
| **OpenRouter** | Get API key from [openrouter.ai](https://openrouter.ai/) |
| **Ollama** | No key needed — [download Ollama](https://ollama.ai/), runs AI models locally on your machine |

---

## Your AI Team

TorlyAI provides 6 specialized AI agents that collaborate on your visa application:

| Agent | Role | What They Do |
|-------|------|--------------|
| **McGonagall** | Orchestrator | Coordinates the team, ensures quality across all phases |
| **Dumbledore** | Strategic Advisor | High-level strategy, vision, idea discovery |
| **Harry** | Writer | Business plan drafting, innovation narrative |
| **Hermione** | Analyst | Market research, financial modeling, sensitivity analysis |
| **Kingsley** | Compliance Expert | Visa requirements, 4F assessment, evidence packs |
| **Dobby** | Assistant | Document formatting, application assembly, QA |

### The 6-Phase Journey

TorlyAI guides you through a structured workflow from initial idea to submission:

| Phase | Name | Lead Agent | Goal |
|:-----:|------|------------|------|
| 0 | **Plan** | McGonagall | Project kick-off, Kanban backlog, roadmap |
| 1 | **Ideate** | Dumbledore | Concept shortlist, market scan, endorsement-fit |
| 2 | **Draft** | Harry | Business plan V1, innovation narrative |
| 3 | **Model** | Hermione | Financial model, sensitivity analysis, plan V2 |
| 4 | **Prove** | Kingsley | Evidence pack, 4F assessment, plan V3 |
| 5 | **Submit** | Dobby | Final QA, forms, submission bundle |

---

## Features

### Core
- **Business Plan Generation** — 7 comprehensive sections using specialized AI agents
- **Financial Modeling** — 3-5 year projections with sensitivity analysis and scenario planning
- **Interview Preparation** — Mock interviews with endorsement body questions (Tech Nation, UKRI, etc.)
- **Innovatorly Matrix** — 4F Formula evaluation for visa endorsement readiness
- **Idea Discovery** — Guided brainstorming with risk assessment and multi-idea comparison

### Workspace
- **Autopilot** — Autonomous multi-agent workflow orchestration
- **Kanban Board** — Visual task management with 4 columns (To Do, Working, Review, Done)
- **AI-Native Task Creation** — Describe a task in plain English, AI structures it automatically
- **Content Pipeline** — Living business plan assembly from agent outputs
- **Session Linking** — Connect chat sessions to tasks for context

### AI & Connectivity
- **Multi-LLM Support** — Anthropic Claude, OpenAI, GitHub Copilot, Google Gemini, OpenRouter, Ollama
- **MCP Sources** — Connect to external tools and APIs via Model Context Protocol
- **Permission Modes** — Three-level safety system (Explore, Ask to Edit, Auto)

### Output & Display
- **Mermaid Diagrams** — Flowcharts, sequence, ER, and class diagrams rendered in chat
- **File Previews** — PDF, images, JSON, HTML, and data tables viewed in-app
- **Export** — PDF, DOCX, and Markdown export for your business plan

### Localisation
- **English** — Full UI and agent prompts
- **Simplified Chinese (简体中文)** — Full UI localisation

---

## Auto-Updates

TorlyAI Desktop includes automatic updates:

1. When a new version is available, you'll see an update notification in the app
2. Click **Update** to download and install
3. The app restarts with the new version

You can also check manually: **Settings** → **About** → **Check for updates**

---

## System Requirements

### macOS

| | Minimum | Recommended |
|---|---------|-------------|
| **macOS version** | macOS 12 Monterey | macOS 14 Sonoma or later |
| **Architecture** | Intel (x64) or Apple Silicon (arm64) | Apple Silicon (M1/M2/M3/M4) |
| **RAM** | 4 GB | 8 GB |
| **Disk space** | 500 MB | 1 GB |

### Windows

| | Minimum | Recommended |
|---|---------|-------------|
| **Windows version** | Windows 10 (64-bit, build 1809+) | Windows 11 |
| **Architecture** | x64 | x64 |
| **RAM** | 4 GB | 8 GB |
| **Disk space** | 500 MB | 1 GB |

### All platforms

- **Internet connection** required for AI providers (except Ollama local models)
- **AI provider account** required — see [Getting an API Key](#getting-an-api-key)

---

## Uninstalling

### macOS
1. Open **Finder** → **Applications**
2. Drag **TorlyAI** to the Trash (or right-click → Move to Trash)
3. To also remove all your data, open **Terminal** (`Cmd + Space`, type `Terminal`, press Enter) and run:
   ```
   rm -rf ~/.torlyai
   ```

### Windows
1. Open **Settings** → **Apps** → **Installed apps**
2. Find **TorlyAI** and click **Uninstall**
3. Follow the uninstaller prompts
4. All app data is removed automatically

---

## Troubleshooting

### macOS: "TorlyAI is damaged and can't be opened"

This can happen with unsigned builds. Open **Terminal** (`Cmd + Space`, type `Terminal`) and run:

```bash
xattr -cr /Applications/TorlyAI.app
```

Then try opening the app again.

### Windows: Installer blocked by antivirus

Some antivirus software flags new or unsigned executables. Options:
1. Temporarily pause your antivirus during installation
2. Add TorlyAI's install folder to your antivirus exclusion list: `%LOCALAPPDATA%\Programs\TorlyAI`
3. Download the code-signed release from the [Releases page](https://github.com/torlyai/desktop/releases)

### App shows blank/white screen on launch

1. Close TorlyAI completely (check the system tray on Windows or force-quit on macOS)
2. Reopen the app
3. If the issue persists, clear the cache:
   - **macOS:** Open Terminal and run `rm -rf ~/Library/Application\ Support/TorlyAI/Cache`
   - **Windows:** Delete the folder `%APPDATA%\TorlyAI\Cache`

### Still need help?

- **Documentation:** [torly.ai/docs](https://torly.ai/docs)
- **Issues:** [GitHub Issues](https://github.com/torlyai/desktop/issues)
- **Website:** [torly.ai](https://torly.ai)

---

## Security & Privacy

- **Local-first:** All your data stays on your machine — nothing is uploaded to TorlyAI servers
- **Encryption:** API keys are encrypted with AES-256-GCM
- **Code signing:** macOS builds are signed and notarized with Apple. Windows builds are code-signed.
- **GDPR:** Full UK GDPR compliance with data subject rights, consent management, and data retention
- **Privacy Policy:** [torly.ai/privacy](https://torly.ai/privacy)

Verify checksums on each [release page](https://github.com/torlyai/desktop/releases).

---

## License

Proprietary. Copyright © 2026 TorlyAI Ltd. All rights reserved.
