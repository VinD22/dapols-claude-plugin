---
name: find-skills
description: Find free agent skills and plugins that fit a small business, from Dapols' checked directory (Anthropic, Google, Vercel and independent makers). Use when someone asks which skills or plugins to add to Claude for their business, or for a skill that does a specific job such as invoices, SEO, video, documents, sales or support.
---

# Find skills for a business

1. Call `search_skills` on the `dapols` server. Pass `businessType` when you know the kind of business (for example `law-firms` or `restaurants-cafes`), `job` for one kind of work, and `noTerminal: true` when the person is not technical.
2. Offer three to five results, the recommended ones first. For each, give what it does, who makes it, its licence, how to add it and whether it needs a terminal.
3. Say that these are other people's projects that Dapols links to and has not run in every case, and that the person should read the project's own instructions before installing.
4. Give the date each entry was checked. Do not describe a skill beyond what the result says.
