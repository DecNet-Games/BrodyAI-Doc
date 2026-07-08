---
layout: default
title: Anthropic Claude
parent: AI Providers
nav_order: 3
permalink: /docs/providers/claude
---

# 🐦 Configuring Anthropic Claude

Anthropic's Claude models, particularly `claude-3-5-sonnet`, are highly regarded for their logic, code formatting, and architectural planning skills.

---

## 🔑 Setup Instructions

1.  Log in to the Anthropic Console at [console.anthropic.com](https://console.anthropic.com).
2.  Generate a new API key from the dashboard.
3.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
4.  In the **General** tab under the **Global Credential Vault**, paste your key into the **Claude Key** field.
5.  Select **Claude** as your default agent, and pick `claude-3-5-sonnet-20240620` from the dropdown list.

---

## 💡 Best Practice
Because Claude 3.5 Sonnet excels at coding, we recommend using it for specialized tasks:
*   Set your global provider to a cheaper fallback (like Gemini Flash or GPT-4o-mini).
*   Go to **Tool Settings > Script Editor** tab and set an **Override** to use Claude 3.5 Sonnet. This ensures Claude is only called when doing surgical inspector script edits, saving you API costs.
