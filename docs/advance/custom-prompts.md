---
layout: default
title: Custom Prompts
parent: Advanced Setup
nav_order: 7
permalink: /docs/advance/custom-prompts
---

# ✍️ Customizing Brody's Naming & Coding Style

You can directly modify Brody's underlying system prompt to force it to adhere to your studio's internal coding styles, naming conventions, or design structures.

---

## 🚀 How to Edit Prompt Rules

1.  Open your project script editor and locate the file:
    `Assets/Brody AI/Editor/Core/PromptBuilder.cs`.
2.  Open the file and find the method `BuildSystemPrompt`.
3.  Inside the system message builder, append your specific constraints to the text string.

---

## 💡 Example Style Rules to Append

### C# Naming Conventions
If you want to enforce specific naming rules, you can add this line to the system prompt:
> *"Always use camelCase starting with an underscore for private variables (e.g. `_speed`) and PascalCase for public fields (e.g. `Speed`)."*

### Disabling Legacy APIs
If you want to prevent the AI from generating deprecated Unity methods:
> *"Never use `OnLevelWasLoaded`. Instead, always import `UnityEngine.SceneManagement` and register callbacks to `SceneManager.sceneLoaded`."*
