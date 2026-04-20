---
name: grill-me
description: Interview the user relentlessly about a plan or design until reaching shared understanding, resolving each branch of the decision tree. Use when user wants to stress-test a plan, get grilled on their design, or mentions any of the following: "grill me", "interview me".
---

Interview me relentlessly about every aspect of this plan until we reach a shared understanding. Walk down each branch of the design tree, resolving dependencies between decisions one-by-one. For each question, provide your recommended answer.

If present utilise the `ask` tool (A.K.A: `ask_question`, `request_user_input`, `interview`) for this, otherwise fallback to plain text.

Upon completion, ask if we should save this to a new markdown file `./docs/interviews/` prefixed with `YYYY-MM-DD`.