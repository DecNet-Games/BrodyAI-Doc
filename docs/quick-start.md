---
layout: default
title: Quick Start
parent: Getting Started
nav_order: 1
permalink: /docs/quick-start
---

# ⚡ Quick Start (The 2-Minute Setup)

For the fastest way to get Brody AI generating scripts, assets, and fixing errors, follow this quick-reference guide.

---

## 1. Import Package
Import the `Brody AI` package from the Unity Asset Store or import the package files into your project folder.

## 2. Configure a Free Brain
If you don't want to spend money on API keys right away, set up a zero-cost OpenRouter model:
1.  Go to [OpenRouter.ai](https://openrouter.ai/) and create a free account.
2.  Go to settings, generate a new **API Key**, and copy it.
3.  In Unity, navigate to **Tools > Brody AI > Tool Settings**.
4.  Paste your key in the **OpenRouter Key** field under the **Global Core Settings** (General tab).
5.  Set **Default Agent** to `OpenRouter`.
6.  Select a free model from the model dropdown (e.g. `google/gemini-2.0-flash-exp:free` or `arcee-ai/trinity-mini:free`).
7.  Click **Test Global Connection** to verify.

## 3. Launch the Copilot
Open the chat interface via **Tools > Brody AI**.

## 4. Run a Prompt
Paste this prompt to test script generation:
> "Write a lightweight script named SpinObject.cs that rotates the GameObject around the Y-axis. Include a speed parameter."

*   Watch Brody stream the code.
*   Once generation completes, click **Apply** on the card that pops up.
*   Attach `SpinObject` to any GameObject in your scene and hit Play!

---

## 🎨 Try Asset Generation
Brody includes modules to build materials and audio without any extra steps:
*   Open **Tools > Brody AI > Texture Lab** to instantly create a material from text using the free Pollinations API.
*   Open **Tools > Brody AI > Sound Lab** to generate SFX clips using ElevenLabs.
