---
layout: default
title: OpenRouter
parent: AI Providers
nav_order: 5
permalink: /docs/providers/openrouter
---

# 🌐 Configuring OpenRouter (For $0 Cost Setup)

**OpenRouter** is an API aggregator that allows you to access hundreds of commercial and open-source models (including OpenAI, Claude, Llama 3, Gemini, etc.) using a single unified API Key.

Importantly, OpenRouter provides access to **completely free AI endpoints**, making it the easiest way to run Brody AI at zero operating cost.

---

## 🔑 Setup Instructions

1.  Create an account at [OpenRouter.ai](https://openrouter.ai/).
2.  Navigate to **API Keys** and generate a new key.
3.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
4.  In the **General** tab under the **Global Credential Vault**, paste your key into the **OpenRouter Key** field.
5.  Set your default agent provider to **OpenRouter**.
6.  Select your model from the dropdown.

---

## 🆓 Accessing Free Models
OpenRouter offers multiple free models that are highly capable:
*   `arcee-ai/trinity-mini:free` (Fast & lightweight)
*   `nvidia/nemotron-3-ultra-550b-a55b:free` (Excellent for detailed reasoning and code generation)
*   `tencent/hy3:free` (Strong logic and layout generation)

To use these, choose **OpenRouter** as the provider, select **Custom** from the Model dropdown, and type the model string (e.g. `nvidia/nemotron-3-ultra-550b-a55b:free`) into the Custom Model ID text field.
