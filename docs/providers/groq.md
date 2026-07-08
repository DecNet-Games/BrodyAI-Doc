---
layout: default
title: Groq
parent: AI Providers
nav_order: 6
permalink: /docs/providers/groq
---

# ⚡ Configuring Groq

**Groq** provides ultra-fast LPU (Language Processing Unit) inference, making it the fastest provider for generating short scripts or running simple refactoring edits.

---

## 🔑 Setup Instructions

1.  Log in to the Groq console at [console.groq.com](https://console.groq.com).
2.  Navigate to API Keys and create a new key.
3.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
4.  In the **General** tab under the **Global Credential Vault**, paste your key into the **Groq Key** field.
5.  Set your default agent to **Groq** and choose your model (e.g. `llama3-8b-8192` or `llama3-70b-8192`).
