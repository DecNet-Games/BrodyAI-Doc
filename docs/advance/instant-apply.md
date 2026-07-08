---
layout: default
title: Instant Apply Mode
parent: Advanced Setup
nav_order: 5
permalink: /docs/advance/instant-apply
---

# ⚡ Instant Apply Mode (Speed Prototyping)

For power users who want to construct levels and layouts rapidly, Brody includes an **Instant Apply Mode** that executes scene operations automatically without waiting for manual confirmation.

---

## ⚙️ Enabling Instant Apply

1.  Navigate to **Tools > Brody AI > Tool Settings**.
2.  In the **General** tab under the **Automation Control** section, locate the toggle:
    **Super Fast Mode (Auto-Apply Scene/Commands)**.
3.  Toggle it **ON**.

---

## ⚡ Behaviors & Safety Caps
*   **Scene Modifications**: Basic scene layout edits (Spawning shapes, placing prefabs, moving objects, parenting, and deleting) will execute **instantly** as the AI streams its response.
*   **Scripts Safety**: Script creation and editing (**CREATE** and **MODIFY** actions) **still require your approval** even in fast mode, ensuring no files on disk are overwritten without your review.
*   **Action Cap**: A safety limit of max 20 instant operations per turn is enforced to prevent erratic AI loops from overpopulating your hierarchy.
