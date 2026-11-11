<div align="center">

  <img src="https://raw.githubusercontent.com/modeldock/ModelDock/main/static/logo.svg" width="100" height="100" alt="ModelDock Logo" />

  # ModelDock
  
  **Universal Local AI Docking Station & Cross-Platform Inference Platform**
  
  Run open-source AI models locally with native performance, zero background daemons, and ultra-low memory usage across Windows, macOS, and Linux.

  <p align="center">
    <a href="https://modeldock.github.io/"><strong>🌐 Visit Official Documentation Website »</strong></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-0078D6?logo=linux&logoColor=white" alt="Cross Platform" />
    <img src="https://img.shields.io/badge/Engine-llama.cpp_Standalone-10b981?logo=cplusplus&logoColor=white" alt="Engine" />
    <img src="https://img.shields.io/badge/Hardware-NVIDIA_CUDA%20%7C%20Apple_Metal%20%7C%20CPU-8b5cf6" alt="Hardware Acceleration" />
    <img src="https://img.shields.io/badge/RAM_Footprint-~35_MB-f59e0b" alt="RAM" />
    <img src="https://img.shields.io/badge/API-OpenAI_Compatible-6366f1" alt="API" />
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="License" />
  </p>

</div>

---

### 🌟 What is ModelDock?

Most local AI software bundles heavy Chromium or Electron runtimes, consuming **600 MB to 1.5 GB of RAM** before even loading model weights. Other tools trap developers in isolated silos (strictly Ollama or manual GGUF files).

**ModelDock bridges everything together into a unified, high-performance docking station:**
- 🖥️ **Cross-Platform Native Experience:** Runs smoothly on **Windows 10/11**, **macOS (Apple Silicon M-series & Intel)**, and **Linux (Ubuntu, Debian, Fedora, Arch)**.
- ⚡ **Ultra-Low Memory Footprint (~35 MB):** Leaves almost 100% of your system RAM and GPU VRAM free for model weights and inference.
- 🛡️ **Zero Daemon Dependency:** Bundles standalone high-performance `llama.cpp` inference binaries—no background services or Docker daemons needed.
- ⏸️ **True Pause & Resume:** Multi-gigabyte GGUF weight streaming via HTTP `Range` headers.
- 🤗 **Hugging Face Hub & Ollama:** Search, download, and manage models from both ecosystems under one roof.
- 🔌 **OpenAI-Compatible Local API (`/v1`):** Drop-in backend for Cursor, VS Code Continue, OpenWebUI, Cline, and LangChain.

---

### 💻 Supported Operating Systems & Acceleration

| Operating System | Acceleration Backend | Runtime Mode |
| :--- | :--- | :--- |
| **Windows 10 / 11** | NVIDIA CUDA / DirectML / CPU AVX2 | Native Desktop (WebView2) & Web UI |
| **macOS (M1/M2/M3/M4 & Intel)** | Apple Metal (MPS) / CPU Accelerate | Native Webkit / Browser Web UI |
| **Linux (Ubuntu, Arch, Fedora)** | NVIDIA CUDA / ROCm / CPU AVX-512 | Headless Server & Browser Web UI |

---

### 🗂️ Ecosystem Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| [**ModelDock**](https://github.com/modeldock/ModelDock) | Core platform, cross-platform engine, and local OpenAI `/v1` server | 🟢 Active |
| [**ModelDock.github.io**](https://github.com/modeldock/ModelDock.github.io) | Official documentation website and developer guides | 🟢 Live |

---

### 🚀 Quick Links

- 📖 **[Documentation & Guides](https://modeldock.github.io/)**
- ⚡ **[Quick Start & Installation](https://modeldock.github.io/getting-started.html)**
- 🔌 **[OpenAI `/v1` API Reference](https://modeldock.github.io/api-reference.html)**
- 🧠 **[Hardware Acceleration Guide](https://modeldock.github.io/hardware-acceleration.html)**

---

<div align="center">
  <sub>Maintained by the ModelDock Open Source Community • Licensed under Apache 2.0</sub>
</div>
