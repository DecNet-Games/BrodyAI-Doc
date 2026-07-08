---
layout: default
title: Context Depth
parent: Advanced Setup
nav_order: 2
permalink: /docs/advance/context-depth
---

# 🧠 Managing Context Depth

To balance speed, token consumption, and generation quality, Brody AI features a **Context Depth** controller. You can adjust this setting under **Tool Settings > General > Context & Credit Manager**.

---

## 🎛️ Context Depth Levels

### ⚖️ Medium (Recommended / Default)
*   **Behavior**: Scans and loads the top 15 most relevant scripts from your Assets folder, and loads the closest 15 GameObjects in your scene hierarchy.
*   **Best For**: Everyday coding, spawning common items, and standard debugging.

### 💸 High (Rich Context)
*   **Behavior**: Performs a full scan of all files in your project directory and maps the deep scene structure.
*   **Best For**: Major system refactoring or complex, multi-file code modifications.
*   *Warning*: Uses significantly more API tokens and may hit rate limits on smaller/cheaper cloud accounts.

### ✅ Low (Minimal Token Usage)
*   **Behavior**: Skips scanning the project files. Brody only sees the active scene roots.
*   **Best For**: General Unity documentation questions, quick C# tips, or when running on tight API rate limits.
