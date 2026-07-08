---
layout: default
title: Dependency Graph
parent: Features
nav_order: 10
permalink: /docs/features/dependency-graph
---

# 🔗 Dependency Graph & Script Relations

When editing complex systems, changing a single line in a base class can break multiple inheriting components. Brody AI's **Dependency Graph** module maps script relationships to prevent compile failures.

---

## ⚡ How it Protects Your Project

1.  **Relation Analysis**: When Brody proposes to edit a script (e.g. `GameManager.cs`), the indexer immediately scans for dependencies—such as what other scripts invoke `GameManager` or inherit from it.
2.  **Safety Injections**: It flags variables and methods that are heavily referenced by other components and reminds the AI to maintain backward compatibility during updates.
3.  **Warning Indicators**: Proactively warns you if the generated edit will require updating other scripts in your assets folder, helping you avoid broken references.
