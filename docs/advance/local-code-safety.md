---
layout: default
title: Local Code Safety
parent: Advanced Setup
nav_order: 6
permalink: /docs/advance/local-code-safety
---

# 🛡️ Local Code Safety & File Recoveries

Brody AI works directly with your local project assets. To ensure you never lose work or get stuck with compilation loops, several safety logic systems are built in.

---

## ↩️ Undo Last Change

If Brody applies an edit that you want to revert:
1.  Go to the Unity menu bar:
    **Tools > Brody AI > Undo Last Change ↩️**
2.  The editor will immediately restore the modified script files back to their exact state prior to the generation.
3.  *Note: Only the most recent set of file modifications can be undone. We recommend version controlling your project using Git for full history management.*

---

## 🚫 Compiler Warning Detection
*   Before applying edits, the editor parses namespaces, syntax, and braces to catch obvious mistakes.
*   If an applied code edit generates a compiler error, Unity's compiler warnings are logged. The **Auto-Fix** banner will immediately pop up in the chat window, allowing you to ask Brody to self-repair the typo in one click.
