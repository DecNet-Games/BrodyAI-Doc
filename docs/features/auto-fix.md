---
layout: default
title: Auto-Fix Engine
parent: Features
nav_order: 7
permalink: /docs/features/auto-fix
---

# 🛠️ Auto-Fix Engine (One-Click Error Diagnostic)

The **Auto-Fix Engine** is a background diagnostic module that monitors Unity's Console window. When a compilation or runtime error is detected, it automatically attempts to diagnose the issue and offer a patch.

---

## 🚀 How it Works

1.  When a compilation error or exception occurs, an alert banner will appear at the bottom of the main **Brody AI** chat window (e.g. *⚠️ NullReferenceException: Object reference not set...*).
2.  Click the **🛠️ Ask Brody to Fix** button.
3.  Brody AI will analyze the error stack trace, locate the script that generated the error, and read the code.
4.  The agent will then write a modified version of the code that resolves the exception (e.g. adding null guards, fixing typos, resolving type mismatch compiler errors).
5.  A **Visual Diff** will display showing the exact code changes. Click **Apply** to patch the error instantly.

---

## 🔒 Safety Assurances
*   **Compile Lock Protection**: If a proposed fix fails to compile, Brody's internal validator flags it, and you can undo the change instantly via **Tools > Brody AI > Undo Last Change**.
*   **No Code Loss**: The auto-fix engine edits files surgically. Unrelated code, comments, and structure are completely preserved.
