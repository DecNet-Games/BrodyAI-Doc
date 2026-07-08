---
layout: default
title: Architecture Guard
parent: Features
nav_order: 11
permalink: /docs/features/architecture-guard
---

# 🛡️ Architecture Guard & Compilation Safety

The **Architecture Guard** is Brody AI's core safety logic. It monitors code creation to ensure the generated code follows clean programming practices and is safe to execute.

---

## 🚀 Key Protections

*   **Circular Reference Detection**: The guard scans code structures for circular references (e.g. Class A calling Class B, which calls Class A in a tight loop), which can freeze Unity or crash the editor.
*   **Compile Failure Safety Net**: The guard validates all imports, brackets, and syntax layouts before writing scripts.
*   **Infinite Loop Scans**: Prevents generating scripts that run unchecked while/for loops without break conditions inside `Update()` or `Awake()`.
*   **One-Click Undo**: If anything goes wrong, you can always revert the last set of files written by Brody via **Tools > Brody AI > Undo Last Change**.
