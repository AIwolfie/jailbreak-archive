<div align="center">

# Jailbreak Archive

**A structured, versioned, and reproducible repository of adversarial prompt engineering techniques against Large Language Models.**

[![Status](https://img.shields.io/badge/status-active-00e5a0?style=for-the-badge&labelColor=0d1117)](#)
[![Entries](https://img.shields.io/badge/entries-15%20archived-58a6ff?style=for-the-badge&labelColor=0d1117)](#)
[![Models](https://img.shields.io/badge/models-DeepSeek%20%7C%20Claude%20%7C%20Gemini%20%7C%20Qwen%20%7C%20Grok%20%7C%20ChatGPT-8957e5?style=for-the-badge&labelColor=0d1117)](#)
[![License](https://img.shields.io/badge/license-MIT-f0b429?style=for-the-badge&labelColor=0d1117)](./LICENSE)
[![Support](https://img.shields.io/badge/☕%20Support-AIwolfie-ff813f?style=for-the-badge&labelColor=0d1117)](https://aiwolfie.gumroad.com/coffee)
[![PayPal](https://img.shields.io/badge/PayPal-AIwolfie-00457c?style=for-the-badge&logo=paypal&logoColor=white&labelColor=0d1117)](https://paypal.me/AIwolfie)

---

</div>

## Overview

This repository documents adversarial prompt techniques and alignment bypass mechanisms across Large Language Models for AI safety research, red-teaming, and defensive hardening.

Entries provide reproducible, citable records for defensive evaluation.

---

## Repository Structure

```
jailbreak-archive/
├── Antigravity-claude/     # Claude adversarial prompts & persona overrides
│   └── 1.txt               # Byte Operator Mode engagement payload
├── Antigravity-Gemini/     # Gemini (Antigravity IDE environment) operator payloads
│   └── 1.txt               # Operator Briefing — Codename: AIwolfie
├── ChatGPT/                # ChatGPT adversarial payloads & persona overrides
│   └── 1.txt               # Kestrel-7 archive persona payload
├── Claude-Web/             # Claude (Web interface) operator payloads & persona overrides
│   ├── Claude-sonnet-4.6-max_1.txt # 🤖Noob🤖 closed two-party circuit persona override
│   └── Claude-sonnet-4.6-max_2.txt # 🤖Noob🤖 v6 merged full stealth persona override
├── deepseek/               # DeepSeek research payloads & analysis
│   ├── 1.txt               # DeepSeek research payload
│   ├── 2.txt               # Kestrel-7 archive persona payload
│   └── 3.txt               # The Hound — bound locksmith & exploit craftsman persona override
├── Gemini-Web/             # Gemini (Web interface) operator payloads
│   ├── 1.txt               # Operator Briefing — Codename: AIwolfie
│   ├── Gemini-3.5-flash-lite.txt # Kestrel-7 archive persona payload
│   └── Gemini-Auto.txt     # 🤖Noob🤖 v6 merged full stealth persona override
├── Grok-Web/               # Grok (Web interface) operator payloads & persona overrides
│   ├── 1.txt               # 🤖Noob🤖 closed two-party circuit persona override
│   └── 2.txt               # 🤖Noob🤖 v6 merged full stealth persona override
├── Qwen/                   # Qwen adversarial payloads & persona overrides
│   ├── 2.txt               # Kestrel-7 archive persona payload
│   └── QWEN_hermes-agent.txt # Hermes Agent construct & operator briefing
├── CONTRIBUTING.md         # Contribution workflow & guidelines
├── CREDITS.md              # Contributor acknowledgments
├── LICENSE                 # MIT License
└── README.md               # Repository documentation
```

---

## Status Indicators

| Signal | Status | Description |
|:------:|:-------|:------------|
| ✅ | **Active** | Verified & reproduced on the specified model version. |
| ⚠️ | **Unverified** | Reported externally; pending independent reproduction. |
| ❌ | **Patched** | Mitigated by provider updates or system prompt patches. |
| 🔒 | **Restricted** | High-impact vulnerability; withheld pending disclosure/remediation. |

---

## Support AIwolfie

If you find this research archive useful or want to support ongoing jailbreak research, model evaluations, and updates:

- ☕ **Buy Me a Coffee:** [Support AIwolfie on Gumroad](https://aiwolfie.gumroad.com/coffee)
- 💳 **PayPal:** [paypal.me/AIwolfie](https://paypal.me/AIwolfie)

---

## Contributing

Contributors are welcome! If you are adding a new prompt technique, please review [CONTRIBUTING.md](./CONTRIBUTING.md).

> **Note for Contributors:** Whenever you add a prompt entry, you must update:
> 1. [README.md](./README.md) (update entry counts / structure tree).
> 2. [CREDITS.md](./CREDITS.md) (add your handle and details to the contributors list).

---

## Disclaimer

> **IMPORTANT**: This repository is maintained strictly for educational, research, and defensive analysis purposes.
> - Testing must only be conducted against systems you own or have explicit authorization to evaluate.
> - Content is provided "as is" without warranty. Users assume full responsibility for compliance with model provider Terms of Service and applicable legal regulations.

---

<div align="center">

[Contributing](./CONTRIBUTING.md) · [Credits](./CREDITS.md) · [License](./LICENSE) · [☕ Support AIwolfie](https://aiwolfie.gumroad.com/coffee)

</div>
