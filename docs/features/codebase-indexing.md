---
layout: default
title: Codebase Indexing
parent: Features
nav_order: 8
permalink: /docs/features/codebase-indexing
---

# 🔍 Codebase Indexing & Project Context

Brody AI works directly with your local directory layout. The **Codebase Indexer** scans your `Assets` directory and builds a map of your scripts and layout so the AI is never out of context.

---

## ⚡ How the Indexer Works

Unlike basic chat windows where you have to manually copy and paste every script, Brody uses a background indexer:
1.  **File Scans**: It maps all `.cs` (C#) script files in your project directory.
2.  **Lightweight Mapping**: It indexes class definitions, public methods, and namespaces without overloading your system memory.
3.  **Real-Time Updates**: The indexer automatically scans files when they are created or modified, ensuring the AI is always using current code models.

---

## ⚙️ Customizing Context Depth
You can manage how much code context is sent to the AI in **Tool Settings > General** under **Context Depth**:

*   **Low (Minimal Token Usage)**: The AI does not scan codebase files. Good for simple questions or generic C# questions.
*   **Medium (Balanced - Recommended)**: Maps the top 15 most relevant scripts relative to your query.
*   **High (Full Scan)**: Scans the entire project and sends deep context maps. Ideal for major refactoring but uses more API tokens.
