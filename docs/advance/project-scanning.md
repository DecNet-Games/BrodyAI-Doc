---
layout: default
title: Project Directory Scanning
parent: Advanced Setup
nav_order: 3
permalink: /docs/advance/project-scanning
---

# 📂 Full Project Directory Scanning

By default, Brody AI focuses on your selected objects and immediate context to keep generation speeds fast. However, for massive refactoring tasks, you can enable **Full Project Scan**.

---

## ⚙️ Enabling Project Scanning

1.  Navigate to **Tools > Brody AI > Tool Settings**.
2.  In the **General** tab under the **Context Handling (Vision)** section, locate the toggle:
    **Enable Full Project Scan (Ask 'Check Project')**.
3.  Toggle it **ON**.

---

## ⚡ How to Trigger

Once project scanning is enabled, you can trigger a full scan by using specific keywords in your chat prompts:
*   *"Check my project and find where the player variables are stored."*
*   *"Scan the project and suggest optimizations for my update loops."*
*   *"Analyze all managers in the project and layout a new state system."*

*Note: For large projects with thousands of files, scanning can take several seconds to map. Ensure you are using a model with a decent context window (like Gemini 1.5 Pro) to handle the data load.*
