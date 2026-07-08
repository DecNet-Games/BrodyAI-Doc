---
layout: default
title: OpenAI
parent: AI Providers
nav_order: 1
permalink: /docs/providers/openai
---

# 🤖 Configuring OpenAI

OpenAI provides reliable, high-quality models for coding and general tasks. You can use their chat models to power Brody's general agent or DALL-E for Texture Lab generation.

---

## 🔑 Setup Instructions

1.  Log in to your developer dashboard at [platform.openai.com](https://platform.openai.com).
2.  Navigate to **API Keys** and generate a new key.
3.  Ensure your account has sufficient credits/balance.
4.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
5.  In the **General** tab under the **Global Credential Vault**, paste your key into the **OpenAI Key** field.
6.  You can now select models like `gpt-4o` or `gpt-4o-mini` from the dropdown lists.

---

## 🎨 Texture Lab Integration (DALL-E 3)
*   If you wish to use OpenAI for generating textures, switch the **Image Provider** in the **Texture Lab** settings (or under Tool Settings > Texture Lab tab) to **OpenAI (DALL-E 3)**.
*   Paste your key in the **Image Key** field.
*   Note: Generating DALL-E 3 images has a set cost per generation charged directly to your OpenAI API account.
