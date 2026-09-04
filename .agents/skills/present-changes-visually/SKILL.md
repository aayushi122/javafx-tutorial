---
name: present-changes-visually
description: Present completed code, UI, document, or configuration changes with concise visual evidence such as screenshots, rendered previews, before-and-after comparisons, diagrams, or tables. Use when the user asks to see, demonstrate, review, or summarize changes visually; do not activate when a plain textual answer is sufficient.
---

# Present Changes Visually

Show the effect of completed changes using the smallest visual that makes the result easier to verify.

## Choose the evidence

- For visible UI changes, run or render the current application and capture the relevant screen or state.
- For documents, slides, PDFs, or images, render the changed artifact and show the affected page or region.
- For behavioral or data changes, use a compact before-and-after table, chart, or example when it communicates the difference more clearly than prose.
- For structural changes involving several components or steps, use a small diagram that shows the important relationships or flow.
- Skip decorative visuals and avoid repeating information already clear from a short diff or explanation.

Use an existing baseline for before-and-after comparisons. Do not reconstruct or claim a “before” state unless it can be obtained reliably from version control or an artifact supplied by the user.

## Verify the result

Ensure the visual represents the current working tree and the exact state relevant to the request. Exercise the changed interaction or render the final artifact before presenting it. Do not modify unrelated product code solely to make a demonstration easier.

Keep temporary captures out of the repository unless the user requests persistent evidence or the project already has a designated artifacts directory.

## Present the outcome

Lead with what changed, then show or link the visual with a short caption explaining what it proves. Mention the verification performed and disclose any important state that could not be rendered or exercised.
