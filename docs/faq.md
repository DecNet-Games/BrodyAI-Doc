---
layout: default
title: FAQ
nav_order: 10
permalink: /docs/faq
---

# Frequently Asked Questions

---

## 💰 Cost & Licensing

### Is there a monthly subscription for Brody AI?
**No.** Brody AI is a one-time purchase on the Unity Asset Store. We do not charge recurring subscriptions for using the editor tool. You buy once, you keep it forever.

### Do I have to pay for API keys to use the AI?
**No, you can run Brody AI completely free.**
*   **100% Free Setup**: By using **OpenRouter** free models (like `google/gemini-2.0-flash-exp:free` or `arcee-ai/trinity-mini:free`), **Pollinations AI** (for free unlimited textures), and **Ollama** (for running open source models locally on your GPU), you can configure a $0 operating cost setup. See the [Zero-Cost Setup Guide](../advance/zero-cost-setup.html).
*   **Paid Setup**: If you choose to use commercial engines like OpenAI (GPT-4o) or Anthropic (Claude 3.5 Sonnet), you will pay your respective provider directly for API tokens used.

---

## 🔒 Privacy & Security

### Is my game code safe? Is it uploaded online?
Your project safety depends entirely on your chosen provider:
*   **Commercial Cloud Providers (OpenAI, Claude, Gemini)**: Selected context files and your prompts are sent to their endpoints to compile answers. Consult their developer policies regarding data training.
*   **Local Models (Ollama)**: Your code **never leaves your computer**. Ollama runs completely offline on your own machine.
*   **Metadata Storage**: API keys, custom models, and settings are stored locally in your computer's `EditorPrefs`. They are never sent to Decnet Games servers.

---

## 🛠️ Diagnostics & Troubleshooting

### The Brody AI window is blank or Unity threw a GUILayout layout exception?
Unity's IMGUI windows can occasionally experience layout mismatches if resized aggressively during an active generation.
1.  Close the Brody AI window.
2.  Go to **Tools > Brody AI > Tool Settings**.
3.  Click **Reset Settings** in the General or active tab.
4.  Reopen Brody AI.

### Why am I getting HTTP 404 errors?
An HTTP 404 error means the AI provider cannot locate the specified model name.
*   Check if you selected "Custom" model and mistyped the name.
*   Check if your provider recently deprecated or renamed the model you selected (e.g. OpenAI updating model names).
*   Verify spelling under **Tool Settings > Overrides**.
