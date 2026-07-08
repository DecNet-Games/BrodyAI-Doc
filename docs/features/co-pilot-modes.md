---
layout: default
title: Co-Pilot Modes
parent: Features
nav_order: 2
permalink: /docs/features/co-pilot-modes
---

# 🕹️ Co-Pilot Modes (Ask, Plan, Execute)

To give you complete control over token usage and safety, Brody AI operates in three distinct **Co-Pilot Modes**. You can toggle these anytime using the dropdown menu in the bottom-left corner of the chat window.

---

## 💻 1. Execute Mode (Default)
In this mode, Brody acts as an autonomous agent that can propose direct actions.
*   **Capabilities**: Writes scripts, suggests modifications, runs scene edits, and generates texture/audio files.
*   **How it behaves**: Proposes **Proposal Cards** with "Apply", "Reject", and "View Diff" buttons.
*   **Smart Automation**: If you type commands like `plan ...` or `/plan ...`, Brody automatically triggers the **Architect Mode** to layout and compile systems dynamically in one run.

---

## ❓ 2. Ask Mode
Use this mode when you want to learn, brainstorm, or clarify concepts without modifying your project.
*   **Capabilities**: Answers questions, explains API usage, explains algorithms, and debugs code logic in text.
*   **How it behaves**: Appends system instructions preventing the AI from outputting `<ACTION>` cards or generating raw file creations. Safe to use for brainstorming sessions.

---

## 📋 3. Plan Mode
When designing complex mechanics, use Plan Mode to draft the architectural details first.
*   **Capabilities**: Analyzes scripts and generates step-by-step documentation, database schemas, or system mockups.
*   **How it behaves**: Tells the AI to think step-by-step and write structured documentation instead of executing C# files. It outputs a numbered steps breakdown without spawning action components.
