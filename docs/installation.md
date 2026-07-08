---
layout: default
title: Installation
nav_order: 2
permalink: /docs/installation
---

# 📥 Installation & Setup

Brody AI is a professional Unity Editor extension. Follow these instructions to get your "Developing Homie" set up inside your project.

---

## 🛒 Step 1: Secure Your Copy
Brody AI can be purchased via the [Unity Asset Store](https://assetstore.unity.com/packages/tools/generative-ai/brody-ai-your-agentic-developing-homie-356158).
1.  Complete your purchase on the Asset Store.
2.  Ensure you are logged into the same Unity Hub account you used for the purchase.

---

## 📦 Step 2: Import into Unity
1.  Open your target Unity Project (Unity 2021.3 LTS or newer recommended).
2.  Go to **Window > Package Manager**.
3.  Change the registry filter to **My Assets**.
4.  Find **Brody AI** and click **Download**, then **Import**.
5.  Ensure all files in the package (under `Assets/Brody AI`) are checked and click **Import**.

---

## 🛠️ Step 3: Initialization
Once imported, Brody AI will initialize.
1.  If the welcome panel doesn't open automatically, launch it from the menu bar:
    **Tools > Brody AI > Welcome 👋**
2.  Click on **Setup API Keys** to configure a provider brain (cloud API keys or local Ollama).
3.  Brody AI will automatically perform a lightweight scan of your project files in the background to build its local index.

---

## ⚙️ Requirements & Compatibility
*   **Operating System**: Windows / macOS / Linux
*   **Unity Editor**: 2021.3+ LTS, 2022.3+ LTS, 6000+ (Unity 6)
*   **Dependencies**: Requires internet access to connect to cloud models, or a running local Ollama instance (`localhost:11434`) for offline mode.

[Next: Getting Started](./getting-started.html){: .btn .btn-primary }
