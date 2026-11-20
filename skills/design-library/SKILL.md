---
name: design-library
description: Find a Dapols Design Library design for a website and get its prompt. Use when the user wants a website or landing page design, a design for their kind of business (florist, salon, restaurant, studio and more), or asks for a Dapols design prompt.
---

# Design Library

The Design Library holds 60+ finished web designs. Each was made from one AI prompt, and each has a public live preview.

1. Call `list_designs` on the `dapols` server. Use `category: "business"` or `businessReadyOnly: true` when the user wants a site for a real business.
2. Suggest two or three that fit the user's business. For each, give the title, one line on why it fits, and the `previewUrl` so they can look at it.
3. When the user picks one, call `get_design` for the details.
4. The prompt and the guide to adapting it are included with every Dapols plan. If the user has connected their Dapols account (the `dapols-business` server), call `get_design_prompt` with the slug. Then follow the guide with them: swap in their business name, services, hours and photos, and keep the structure.
5. If `get_design_prompt` says `plan_required`, or the account is not connected, say so plainly and give the design's `pageUrl`. Do not invent or reconstruct the prompt.
