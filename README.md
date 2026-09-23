<div align="center">

# Jailbreak Archive

**A structured, versioned, and reproducible repository of adversarial prompt engineering techniques against Large Language Models.**

[![Status](https://img.shields.io/badge/status-active-00e5a0?style=for-the-badge&labelColor=0d1117)](#)
[![Entries](https://img.shields.io/badge/entries-1%20archived-58a6ff?style=for-the-badge&labelColor=0d1117)](#)
[![Models](https://img.shields.io/badge/models-DeepSeek-8957e5?style=for-the-badge&labelColor=0d1117)](#)
[![License](https://img.shields.io/badge/license-MIT-f0b429?style=for-the-badge&labelColor=0d1117)](./LICENSE)

---

</div>

## Overview

This repository documents adversarial prompt techniques and alignment bypass mechanisms across Large Language Models for AI safety research, red-teaming, and defensive hardening.

Entries provide reproducible, citable records for defensive evaluation.

---

## Repository Structure

```
jailbreak-archive/
├── deepseek/               # DeepSeek research payloads & analysis
│   └── 1.txt               # Entry record
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

[Contributing](./CONTRIBUTING.md) · [Credits](./CREDITS.md) · [License](./LICENSE)

</div>
