---
name: choose-ai-tools
description: Compare AI tools and models for a small business with dated, sourced prices. Use when the user asks which AI tool, plan or model to use, what it costs, or how two models compare.
---

# Choose AI tools

1. For a business need, call `recommend_stack` with the business type, team size and budget, or `search_tools` for one job (for example "answer the phone").
2. For one tool's plans, call `get_tool`. Quote the plan name, the monthly price in USD and the date it was checked. Say when a price is usage-based or quote-only.
3. For models, call `list_models`, `get_model` or `compare_models`. Report benchmark scores with their source, and say when a score is vendor-reported.
4. Never state a price without its check date. If a tool is not in the catalog, say so instead of guessing.
