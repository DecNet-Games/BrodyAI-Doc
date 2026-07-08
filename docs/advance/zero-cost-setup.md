---
layout: default
title: Zero-Cost Setup
parent: Advanced Setup
nav_order: 1
permalink: /docs/advance/zero-cost-setup
---

# 🆓 Zero-Cost Setup Guide ($0 Operating Cost)

One of Brody AI's strongest features is its capability to run completely free of charge. By combining free cloud APIs, local inference, and open asset generators, you can build games with AI without spending a single dollar.

---

## 🛠️ Step 1: Free Text & Code Generation (OpenRouter)

OpenRouter offers high-quality, completely free models that you can use instead of paid OpenAI or Claude endpoints:
1.  Sign up for a free account at [OpenRouter.ai](https://openrouter.ai/).
2.  Go to your settings and generate an API key. Since you're using free models, you do not need to deposit any credits.
3.  Open Unity and go to **Tools > Brody AI > Tool Settings**.
4.  Paste your key in the **OpenRouter Key** field in the General tab.
5.  Set **Default Agent** to **OpenRouter**.
6.  Select **Custom** in the model dropdown, and type one of the following free model IDs into the text field:
    *   `google/gemini-2.0-flash-exp:free` (Highly recommended - fast and smart)
    *   `nvidia/nemotron-3-ultra-550b-a55b:free` (Excellent coding logic)
    *   `arcee-ai/trinity-mini:free` (Ultra-fast lightweight queries)

---

## 🎨 Step 2: Free Unlimited Textures (Pollinations AI)

Texture Lab comes preconfigured to use **Pollinations AI** for image generation:
*   Pollinations AI is completely free, unlimited, and requires **no API key**.
*   In Texture Lab, simply set the provider to **Pollinations** to generate textures and materials at zero cost.

---

## 🔊 Step 3: Free Game Sound Effects (ElevenLabs Free Tier)

For game audio, Sound Lab integrates with **ElevenLabs**:
*   ElevenLabs offers a free tier that grants **10,000 monthly credits**.
*   This is sufficient to generate roughly **100 custom sound effects** every month for free.
*   Sign up at [elevenlabs.io](https://elevenlabs.io), get your free key, and paste it into the **Sound Lab** tab in settings.

---

## 💻 Step 4: Local Offline Models (Ollama)

If you have a dedicated graphics card (NVIDIA GPU with 6GB+ VRAM recommended), you can bypass cloud services entirely:
*   Download and run **Ollama** locally.
*   Pull a free coding model like `llama3` or `codegemma`.
*   Set your provider to **Ollama** in Unity.
*   Your local GPU will perform all the generation offline, completely free and private.
