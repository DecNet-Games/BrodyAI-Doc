---
layout: default
title: Edit with AI
parent: Features
nav_order: 4
permalink: /docs/features/edit-with-ai
---

# ✍️ Edit with AI (Surgical Inspector Editing)

The **Edit with AI** feature lets you make quick, surgical modifications to existing components and scripts directly from their inspector views.

---

## 🚀 How to Use

1.  Select a GameObject containing the script you want to modify.
2.  In the Inspector, locate the component.
3.  Right-click the component header and select **Edit with AI**.
4.  A popup window will appear showing the component context.
5.  Type your instructions (e.g. *"Add a double-jump boolean and expose it as a public variable"*).
6.  Click **Apply Changes**.

---

## 🔍 Visual Diff System
Before any code changes are written to disk, Brody AI presents a **Visual Diff Window**:
*   **Deletions** are highlighted in red (with a `-` prefix).
*   **Additions** are highlighted in green (with a `+` prefix).
*   You can review the exact lines of code that will change.
*   Click **Apply** to save the modified code, or **Reject** to abort the edit.
