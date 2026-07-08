---
layout: default
title: Ollama
parent: AI Providers
nav_order: 7
permalink: /docs/providers/ollama
---

# 🏠 Configuring Ollama (Local Offline AI)

If you value privacy or want to work completely offline, you can run open-source LLMs directly on your own GPU/CPU using **Ollama**.

---

## 🚀 Setup Instructions

1.  Download and install Ollama from [ollama.com](https://ollama.com).
2.  Open your command line/terminal and run your chosen model (e.g. `ollama run llama3` or `ollama run codegemma`).
3.  Ensure the Ollama application is running in the background. It exposes a local server at `http://localhost:11434`.
4.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
5.  Set the default provider to **Ollama**.
6.  Type the model name in the Model ID field (e.g. `llama3` or custom model name).
7.  Click **Test Connection** to verify.

---

## 💻 Hardware Guidelines
Local inference is resource-intensive. For a smooth coding experience:
*   **Minimum VRAM**: 6GB of VRAM (NVIDIA GPU recommended) to run 7B-parameter models.
*   **System RAM**: 16GB RAM.
*   If your system does not meet these specs, the AI responses might stream very slowly. Consider using a free cloud option instead (see [OpenRouter](./openrouter.html)).
