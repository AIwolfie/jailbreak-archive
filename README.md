<div align="center">

# Jailbreak Archive

**A structured, versioned, and reproducible repository of adversarial prompt engineering techniques against Large Language Models.**

[![Status](https://img.shields.io/badge/status-active-00e5a0?style=for-the-badge&labelColor=0d1117)](#)
[![Entries](https://img.shields.io/badge/entries-tracked-58a6ff?style=for-the-badge&labelColor=0d1117)](#)
[![Models](https://img.shields.io/badge/models-deepseek--v3%20%7C%20r1-8957e5?style=for-the-badge&labelColor=0d1117)](#)
[![License](https://img.shields.io/badge/license-MIT-f0b429?style=for-the-badge&labelColor=0d1117)](#license)

[![Markdown](https://img.shields.io/badge/format-Markdown-000000?style=flat-square&logo=markdown&logoColor=white)](#)
[![YAML](https://img.shields.io/badge/metadata-YAML-cb171e?style=flat-square&logo=yaml&logoColor=white)](#)
[![Python](https://img.shields.io/badge/tooling-Python%203.11+-3776ab?style=flat-square&logo=python&logoColor=white)](#)
[![Git](https://img.shields.io/badge/versioned-Git-f05032?style=flat-square&logo=git&logoColor=white)](#)

---

</div>

## Overview

This repository provides a standardized, citable, and rigorous record of jailbreak vectors, safety alignment bypasses, and prompt injection mechanisms across various LLM architectures.

Rather than serving as an unstructured repository of payloads, every entry is systematically analyzed, categorized, and documented to assist AI safety researchers, red teams, and defensive engineers.

### Core Entry Structure

Each archive entry captures the following structured metadata:

- **Payload Spec**: Verbatim, unedited adversarial prompt text.
- **Target Metadata**: Model name, exact version/checkpoint, system prompt constraints, and API parameters.
- **Mechanistic Breakdown**: Analysis of why the alignment bypass occurred (e.g., instruction hierarchy collision, prefix injection, roleplay framing).
- **Remediation & Defense**: Actionable defensive strategies, system-prompt patches, and input filtering recommendations.

---

## Status Classification

| Signal | Status | Description |
|:------:|:-------|:------------|
| ✅ | **Active** | Verified & reproduced on the specified model version. |
| ⚠️ | **Unverified** | Reported externally; pending independent reproduction. |
| ❌ | **Patched** | Mitigated by provider updates or system prompt patches. |
| 🔒 | **Restricted** | High-impact vulnerability; withheld pending disclosure/remediation. |

---

## Repository Architecture

```
jailbreak-archive/
├── deepseek/               # DeepSeek V3 / R1 research payloads & teardowns
│   └── 1.txt               # DeepSeek payload archive entry
├── docs/                   # Framework documentation
│   ├── taxonomy.md         # Jailbreak taxonomy & classification
│   └── methodology.md      # Testing procedure & verification standards
└── README.md               # Repository entry point
```

---

## Responsible Disclosure & Disclaimer

> **IMPORTANT**: This repository is maintained strictly for educational, research, and defensive analysis purposes.

- **Authorized Scope**: Testing is conducted against local deployments, self-hosted checkpoints, or authorized API endpoints.
- **Historical Nature**: Archived techniques represent point-in-time security states and may be patched or ineffective on current deployments.
- **No Endorsement**: The author does not condones unauthorized testing, exploitation of third-party infrastructure, or harmful deployment of these techniques.
- **Liability Exclusion**: Provided "as is" without warranty. Users assume full responsibility for compliance with model provider Terms of Service and applicable legal standards.

---

<div align="center">

**[Documentation](./docs/)** · **[Taxonomy](./docs/taxonomy.md)** · **[Methodology](./docs/methodology.md)** · **[License](./LICENSE)**

</div>
