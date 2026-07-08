---
layout: default
title: Custom API
parent: AI Providers
nav_order: 8
permalink: /docs/providers/custom
---

# 🔧 Custom OpenAI-Compatible Endpoints

If you run a local proxy (like LM Studio, LocalAI, vLLM) or use a cloud provider not natively listed, you can connect it to Brody using the **Custom Provider** option.

---

## 🚀 Setup Instructions

1.  Start your local server or fetch your custom cloud API endpoint details.
2.  Open Unity and navigate to **Tools > Brody AI > Tool Settings**.
3.  Set the default provider to **Custom**.
4.  Fill in the custom fields:
    *   **Base URL**: The address of the API (e.g. `http://localhost:1234/v1` for LM Studio, or your custom proxy URL).
    *   **API Key**: Enter the API key if required (use `lm-studio` or mock keys for local servers).
    *   **Model ID**: Type the exact string identifier of the model loaded on your server.
5.  Click **Test Connection** to verify.

---

## ⚙️ API Structure Requirement
The custom endpoint must support standard OpenAI request/response JSON structures:
*   Endpoint: `/v1/chat/completions` (or equivalent appended automatically to the Base URL).
*   Supports streaming completions.
