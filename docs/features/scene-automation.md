---
layout: default
title: Scene Automation
parent: Features
nav_order: 9
permalink: /docs/features/scene-automation
---

# 🤖 Scene Automation & Orchestration

Brody AI is not just a code generator—it can also orchestrate and manipulate objects in your Unity scene hierarchy using simple, natural language instructions.

---

## 🚀 Capabilities

When you instruct Brody to build a layout, it uses specialized tags to perform actions:
*   **Spawn Primitive Shapes**: e.g., *"Spawn a cube at 0, 0, 0 and name it Ground"*
*   **Move & Rotate Objects**: Adjust coordinates and orientation.
*   **Parent Objects**: Form hierarchies, like placing sub-elements inside a manager.
*   **Delete Assets/Objects**: Remove test assets or cleanup layout.
*   **Add Components**: Attach components, rigidbodies, or custom scripts to scene gameobjects automatically.

---

## 🔒 Safety and Speed Configurations
Under **Tool Settings > General**, you can configure how Scene actions execute:
*   **Review Mode (Default)**: Brody proposes the scene edit in a Proposal Card. You must review the actions and click **Apply** to execute them.
*   **Instant Apply Mode**: If enabled, basic scene commands (Spawning, moving, parenting, deleting) bypass approval and happen **instantly** to speed up your prototyping.
