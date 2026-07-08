---
layout: default
title: AI Chat & Workspace
parent: Features
nav_order: 1
permalink: /docs/features/ai-chat
---

# 💬 AI Chat & Workspace

The main entry point for Brody AI is the **AI Chat Window**, accessible via **Tools > Brody AI**. It provides a workspace interface for interacting with your codebase, scene selection, and chat history.

---

## 🎛️ Interface Layout

1.  **Sidebar (Left-hand Navigation)**
    *   **Chat Icon**: Active conversation panel.
    *   **History Icon**: Reload previous chat sessions or delete old logs.
    *   **Settings Icon**: Direct shortcut to the `Tool Settings` window.
    *   **Green Plus Icon**: Creates a new, blank chat session (auto-cleaning empty historical conversations).
2.  **Active Chat Log**
    *   **User Bubbles (Blue)**: Your inputs. Includes option to copy prompt or retry generation.
    *   **AI Response Bubbles (Dark Grey)**: Explanations and streamed text. Contains real-time text formatting (bolding, italics, syntax code coloring).
    *   **Proposal Cards**: Generated C# scripts or scene edits that can be applied, rejected, or analyzed via a visual Diff preview.
3.  **Input Panel (Bottom)**
    *   **Mode Selector Dropdown**: Ask, Plan, or Execute.
    *   **Magic Prompt Enhancer (✨)**: Automatically appends quality, edge-case, and commenting guidelines to your input prompt.
    *   **Drag & Drop Context Slot**: Drop files or GameObjects directly here.
    *   **Text Area**: Type instructions (Shift+Enter for newlines, Enter to Send).
    *   **Action Button**: Send prompts or Stop (🛑) streaming when you want to interrupt.
