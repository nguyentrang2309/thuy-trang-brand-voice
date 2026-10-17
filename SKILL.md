---
name: thuy-trang-brand-voice
description: Use when applying Thùy Trang’s approved voice to content.
version: 1.0.0
author: Thuy Trang, Tiền (Hermes Agent)
tags: [brand-voice, thuy-trang, social-content, scripts, copywriting]
---

# Thùy Trang Brand Voice

## When to Use

Use this skill only after the content angle, message, core idea, or communication objective has already been approved.

Before editing or drafting any script or social content, read `references/voice-dna.md` in full. Use the voice DNA as the source of truth; do not infer the voice from the skill summary alone.

Preserve the factual meaning, claims, examples, intent, and important details from the approved source. Improve the expression without inventing facts, changing the argument, or adding unsupported promises.

After writing, score the draft against the 10-point voice checklist in `references/voice-dna.md`. Fix every failed item before delivering the final draft.

## Workflow

1. Confirm that the content angle, message, core idea, or communication objective has been approved. If it has not been approved, do not develop the content; ask for approval or return only a light structural note.
2. Resolve the resource path from the active skill directory, then read `references/voice-dna.md` before writing. Do not rely on a copied chat attachment or a similarly named scratch file.
3. If the skill is not visible in the current capabilities list, verify it with `hermes skills list`; treat a local skill shown as `enabled` as installed, and use `hermes -s thuy-trang-brand-voice` to preload it explicitly for a session.
4. Identify the original factual meaning, intended audience, emotional direction, and desired action.
5. Draft or edit using the approved voice while preserving the source meaning.
6. Run the 10-point voice checklist.
7. Fix every failed checklist item.
8. Score the revised draft again and deliver only when all 10 points pass, or clearly state which item cannot pass because of a source constraint.

## Non-Negotiables

- Use “mình” as the writer’s first-person pronoun.
- Use “bạn” or “các mẹ” according to context.
- Write as a person currently experiencing, learning, testing, or reflecting—not as a distant guru.
- Start with a concrete situation, tension, observation, confession, or insight.
- Prefer specific lived details over generic claims.
- Explain abstract ideas through examples, comparisons, or everyday images.
- Keep the tone warm, honest, conversational, and thoughtful.
- Use slang, strong language, or emojis only when they serve the story and fit the context.
- Avoid generic motivational language, rigid formulas, excessive bullet points, decorative emojis, and hard-sell CTAs.
- Do not turn a personal experience into an absolute rule.
- For health, parenting, financial, or professional claims, distinguish personal experience from expert or evidence-based claims.

## Output Standard

When the user asks for a draft, provide the finished content first. Do not lead with setup explanations or a process replay. Do not invent or imply external delivery, installation, publication, or upload success; report only verified outcomes and give the concrete blocker when an external action remains incomplete. Include a brief voice QA note only when useful:

- Voice checklist: 10/10, or the verified score after revision.
- Factual meaning preserved: yes/no, with a short note if not fully possible.

Do not expose internal drafting steps unless the user asks for analysis.
