# 🧩 Floating Code Editor with Local Hosted LLM Autocomplete  
![Static Badge](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)  
![Static Badge](https://img.shields.io/badge/LLM-DeepSeek--Coder--v2:16B-green?style=for-the-badge&logo=openaigym)  
![Static Badge](https://img.shields.io/badge/Engine-C%2B%2B%20%2F%20DirectX-critical?style=for-the-badge&logo=cplusplus)  
![Static Badge](https://img.shields.io/badge/License-Private-lightgrey?style=for-the-badge)  

---

### ✨ Overview
I wanted a code editor that could pop up anywhere, even while playing games, so I built my own **floating in-game code editor** that supports multiple languages, real-time AI code completions, and inline scripting.

The editor runs **entirely locally**, powered by a **self-hosted LLM backend** connected through a lightweight proxy.  
The model I fine-tuned for completions is **DeepSeek-Coder-v2:16B**, hosted on my own machine for **ultra-low latency inference**.

---

## 🚀 Core Features

| Feature | Description |
|----------|-------------|
| 💻 **High Performance** | Multithreaded rendering and logic execution, stress-tested with scripts exceeding **100,000 lines** for responsiveness. |
| 🪶 **Floating Overlay IDE** | Instantly summon the editor over any window or game using a custom hotkey. |
| 🧠 **Local Hosted LLM** | Real-time code completions powered by a self-hosted model (Copilot-style autocompletion). |
| 🧮 **Multi-Language Support** | Supports **Lua**, **C++**, **Python**, and **AngelScript** (for Unreal Engine). |
| 💡 **IntelliSense Integration** | Semantic analysis, signature hints, contextual completions, and real-time symbol resolution. |
| 🎨 **Syntax Highlighting** | Fully customizable **VS Code-style regex themes** with real-time highlighting. |
| ⚡ **Low-Latency Backend** | Average round-trip completion latency: **~1.55s** on local inference. |
| 🔄 **Inline Scripting** | Edit, execute, and reload scripts directly inside the editor. |

---

## 🧬 Machine Learning Work

This project doubles as an **AI research sandbox** for evaluating locally hosted language models in real-world coding environments.

**Current goals:**
- 🧩 Fine-tuning lightweight models for **context-aware completions**
- 🔗 Implementing **structured tool-calling** and chain reasoning
- ⏱ Measuring **latency & context window efficiency** in live usage

By running locally, I can directly benchmark inference speed, prompt handling, and completion accuracy across different architectures.

---

## 🧰 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend / UI** | C++ custom rendering engine (DirectX backend), floating overlay UI |
| **AI Backend** | Local inference server (DeepSeek-Coder-v2:16B) via custom proxy |
| **Scripting** | Lua / AngelScript / Python runtime integration |
| **Editor Engine** | Multithreaded text engine, regex-driven syntax highlighting, semantic indexing |
| **Integration** | Real-time socket-based completion requests with fallback caching |

---

## 📸 Example Preview

A Lua script being edited inside the floating IDE — showing inline AI completions and VS Code-style syntax coloration.

![Floating Code Editor Screenshot](assets/editor_preview.png)

*(Add your actual screenshot in `/assets/editor_preview.png`)*

---

## 🔒 Note

> ⚠️ The **source code is private**.  
> This repository exists to showcase the **project concept**, **architecture**, and **design**.  
> Private builds or documentation may be shared upon request for research or collaboration purposes.

---

## 🧠 Future Directions

- 🧩 Plugin API for custom tools and visualizers  
- 🪄 On-device fine-tuning utilities  
- 🧱 Additional language runtimes (C#, Rust, HLSL)  
- 🧭 AI-driven refactoring and auto-comment generation  

---

## 📫 Contact

Interested in:
- The **engine architecture**  
- The **AI integration layer**  
- Or **local LLM deployment and tooling**

Reach out directly, happy to discuss system design, optimization, and self-hosted AI workflows.

---

> 🧠 *“Built for experimentation — optimized for creativity.”*
