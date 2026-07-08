---
layout: default
title: Generate Component
parent: Features
nav_order: 3
permalink: /docs/features/generate-component
---

# 📦 Generate Component

The **Generate Component** tool is a specialized module designed to create brand new, context-aware MonoBehaviours and attach them directly to selected GameObjects.

---

## 🚀 How to Use

1.  Select a GameObject in your scene hierarchy.
2.  Open the welcome dashboard (**Tools > Brody AI > Welcome 👋**) and click **Generate Component** under Power Tools, or right-click the GameObject in the Hierarchy and select **Brody AI > Generate Component**.
3.  Type a description of what the new script should do (e.g. *"A script that makes this object float up and down smoothly"*).
4.  Click **Generate**.

---

## ⚡ Context Awareness

Unlike generic AI code assistants, Brody AI reads the target GameObject's current structure:
*   It detects **existing components** on the GameObject (e.g. Rigidbody, Colliders, Renderer).
*   It ensures the generated script references and utilizes those components correctly instead of duplicating them.
*   If **Advanced Project Context** is enabled in Settings, it will scan other classes in your project to ensure compatibility with your existing managers and namespaces.
