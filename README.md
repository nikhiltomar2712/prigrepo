# 🛡️ Prigrepo

[![GitHub repository](https://img.shields.io/badge/Repository-prigrepo-blue?style=for-the-badge&logo=github)](https://github.com/nikhiltomar2712/prigrepo)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](./LICENSE)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub stars](https://img.shields.io/github/stars/nikhiltomar2712/prigrepo?style=for-the-badge&logo=github&color=yellow)](https://github.com/nikhiltomar2712/prigrepo/stargazers)

> **Prigrepo** is a dedicated knowledge base and structured repository containing logs, notes, and code samples exploring the intersections of **AI Coding**, **Prompt Hacking**, and **Cybersecurity**.

---

## 🎯 What is inside?

This repository contains structured directories (`logs/dir_0` through `logs/dir_30`) hosting a rich set of learning logs and code snippets. Each entry covers an essential concept or observation under three main pillars:

### 🤖 AI Coding
- **Assisted Development:** Best practices for programming with LLMs (e.g., Cursor, Gemini, Copilot).
- **Architecture Patterns:** Discussions on Retrieval-Augmented Generation (RAG) and tool-use agents.
- **Security Guardrails:** Why and how to review AI-generated code for security vulnerabilities (XSS, SQL Injection).

### 💬 Prompt Hacking
- **Adversarial Prompts:** Explanations of prompt injection techniques, token smuggling, and base64-obfuscated bypasses.
- **Defense Strategies:** How to design robust system instructions to prevent leakage and unauthorized execution.
- **Alignment:** How LLMs learn to distinguish benign and malicious instructions.

### 🔒 Cybersecurity
- **Secure Code Design:** Principles of least privilege, input sanitization, and secure configurations.
- **Vulnerability Reference:** Brief code samples demonstrating flaws and their respective secure patches.

---

## 📁 Repository Structure

```text
prigrepo/
├── logs/
│   ├── dir_0/
│   │   ├── note_1.md      <-- Topic-specific markdown log
│   │   ├── note_2.js      <-- Code sample illustrating AI patterns or vulnerabilities
│   │   └── note_5.py      <-- Python implementations/concepts
│   └── ... (up to dir_30)
└── README.md
```

Each log directory contains standard-formatted files:
*   **`.md`** and **`.txt`** files for conceptual explanation and topic deep-dives.
*   **`.js`** and **`.py`** files for executable code samples and vulnerability proofs.

---

## 🔍 How to Explore the Logs

Since the repository houses multiple structured directories, you can easily search for topics using standard terminal tools:

### Find all logs on Prompt Hacking:
```bash
grep -rn "Topic: Prompt Hacking" logs/
```

### Find all logs on AI Coding:
```bash
grep -rn "Topic: AI Coding" logs/
```

### Search for specific keywords (e.g., "RAG" or "Smuggling"):
```bash
grep -rn "RAG" logs/
```

---

## 🤝 Contributing

Contributions are highly welcome! Whether you are documenting a new prompt jailbreak mechanism, security concept, or AI assistant pattern, feel free to contribute:

1. **Fork** the repository.
2. **Create your feature branch** (`git checkout -b feature/amazing-log`).
3. **Commit your changes** (`git commit -m 'Add log entry on prompt defensive layers'`).
4. **Push to the branch** (`git push origin feature/amazing-log`).
5. **Open a Pull Request**.

If you find these notes helpful, please consider giving this project a ⭐ **Star** to show your support!

---

## 📄 License

This repository is licensed under the MIT License. Feel free to use, share, and build upon these notes.
