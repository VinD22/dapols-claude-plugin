---
name: marketing-kit
description: Run a piece of the Dapols AI Marketing Kit with a small-business owner (a 90-day marketing plan, a month of posts, a Google Business Profile tune-up, review replies, a service page, a welcome email sequence, a first ads test, a monthly review). Use when an owner asks for help with their marketing, a marketing plan, posts, emails or ads.
---

# Dapols AI Marketing Kit

1. Call `list_marketing_kit` on the `dapols` server to see the pieces in order, with what each one produces. It is public and needs no sign-in.
2. Pick the piece that fits what the owner asked for. If they are starting from nothing, start with the brand voice file and the customer and offer brief: every later piece uses them.
3. For a Dapols plan owner, call `get_marketing_kit_piece` on the `dapols-business` server to get the full piece. Follow its prompt exactly: ask for the inputs it lists before writing, and never invent facts, reviews, prices or numbers.
4. If the answer is `plan_required`, say plainly that the kit is included with a Dapols plan and give the page link from `list_marketing_kit`. Do not try to rebuild the piece from its public example.
5. Save the result with `save_draft` so it stays in the owner's Dapols account. Nothing is posted, sent or paid for from here: the owner checks the draft and sends it themselves.

End every piece by showing the owner its "check before" list.
