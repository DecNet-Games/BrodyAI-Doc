---
layout: default
title: Getting Started
nav_order: 3
permalink: /docs/getting-started
---

# 🚀 Getting Started

Let's configure Brody AI's brain and run your first agent tasks.

---

## 🧠 Step 1: Set Up Your AI Brain
Brody AI supports a variety of local and cloud engines. To set your primary provider:

1.  Open the settings panel via **Tools > Brody AI > Tool Settings**.
2.  In the **General** tab under the **Global Core Settings**, select your preferred default provider.
3.  **Choose your setup style:**
    *   **Commercial APIs**: Enter your OpenAI, Gemini, Claude, or DeepSeek API key in the *Global Credential Vault*.
    *   **Aggregators (Recommended for low cost)**: Get an API key from [OpenRouter.ai](https://openrouter.ai/). You can access top-tier models and multiple **completely free models** (like nvidia/nemotron or tencent/hy3) with a single key.
    *   **Local & Private**: Choose **Ollama**. Start the Ollama server on your machine, and download your chosen model (e.g. `ollama run llama3`).

---

## 🔌 Step 2: Connection Test
Before talking to Brody, make sure the connection is fully synced:
1.  In the **General** tab of the settings, scroll down and click **Test Global Connection**.
2.  A popup dialog will verify if the agent successfully established contact.
3.  If the test fails, verify your API keys or check your local Ollama address (`http://localhost:11434`).

---

## 💬 Step 3: Your First Prompt
Open the chat window at **Tools > Brody AI**. Let's ask Brody to create a simple gameplay script:

1.  Set the mode dropdown (at the bottom left) to **Execute**.
2.  In the text area, type:
    > "Create a new script named PlayerMovement.cs that handles basic keyboard movement and jumping for a Rigidbody."
3.  Click **SEND** or hit `Enter`.
4.  Brody will stream the reasoning and write the script. Once done, a **Proposal Card** will appear showing `PlayerMovement.cs` with an **Apply** button. Click **Apply** to write the file directly into your Unity Assets folder!

---

## 📽️ Next Steps
Explore specific configurations:
*   [Quick Cheat Sheet](./quick-start.html)
*   [Setting up Free Models](../advance/zero-cost-setup.html)
*   [Generating Game Assets](../features/texture-lab.html)
