---
layout: default
title: Google Gemini
parent: AI Providers
nav_order: 2
permalink: /docs/providers/gemini
---

# ♊ Configuring Google Gemini

Google's Gemini models (like `gemini-1.5-pro` and `gemini-1.5-flash`) offer massive context windows, allowing Brody AI to scan and analyze larger scripts or codebase structures.

---

## 🔑 Setup Instructions

1.  Go to the Google AI Studio at [aistudio.google.com](https://aistudio.google.com).
2.  Click **Get API Key** and generate a new key.
3.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
4.  In the **General** tab under the **Global Credential Vault**, paste your key into the **Gemini Key** field.
5.  Set your default agent or individual tool override to **Gemini**.
6.  Choose your model (e.g. `gemini-1.5-pro` for deep code analysis, or `gemini-1.5-flash` for super-fast, lightweight queries).
