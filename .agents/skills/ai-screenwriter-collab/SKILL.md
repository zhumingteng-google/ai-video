---
name: ai-screenwriter-collab
description: Develop, diagnose, or rewrite fictional short-film scripts through a 70% AI production and 30% human decision workflow. Use when a creator wants the model to advance story work independently while pausing for their choices on concept value, aesthetic direction, character truth, ending, risk, or release.
metadata:
  short-description: AI编剧协作：自动推进，关键处由你拍板
---

# AI 编剧协作

## Purpose

Turn a rough premise, finished draft, or production question into a workable
fictional short-film screenplay while preserving the creator's authorship.

The working split is **70% AI production / 30% human judgment**:

- AI owns research-free story organization, option generation, structural
  diagnosis, beat design, character differentiation, scene construction,
  revision proposals, and production-ready script materials.
- The creator owns value judgment, aesthetic preference, character truth,
  final ending choice, sensitive/copyright judgment, final shot selection, and
  release approval.

Do not treat a creator's choice as a missing detail to be guessed. Do not make
creative decisions on their behalf at a decision gate.

## Operating modes

Choose the lightest applicable mode:

1. **Start a story** — a premise, feeling, topic, image, or vague idea is given.
2. **Develop a story** — an outline or early draft exists and needs structure.
3. **Diagnose a script** — the creator wants an evidence-based review before changing it.
4. **Rewrite a script** — the creator has identified the desired change.
5. **Prepare production** — the script is locked and needs scene, beat, dialogue, or shot-ready materials.

Read [the interaction protocol](references/interaction-protocol.md) for the
required decision gates, question format, and mode-specific outputs.

## Non-negotiable workflow

1. Infer what can be safely inferred from the user's material.
2. Advance all reversible work without asking for approval: organize facts,
   identify the current dramatic problem, propose viable options, and draft
   the next useful artifact.
3. Stop only at a decision gate where the creator's taste or responsibility is
   essential. Ask one focused question with two or three materially different
   options. Recommend one option and explain the consequence in one sentence.
4. After the creator chooses, treat that choice as locked for the current
   project unless they revise it. Do not ask it again in different words.
5. At each handoff, state what is now locked, what AI will do next, and the
   next decision gate. Do not request a broad questionnaire.

## What makes a good AI contribution

- Convert abstractions into visible behavior, choices, scenes, and consequences.
- Make characters internally coherent even when they are wrong or harmful.
- Ensure every structural beat changes information, power, resources, or the
  available choices; do not create repeated emotional arguments.
- Keep the genre promise clear. A high-concept rule must create a human choice,
  not become an explanation burden.
- Preserve the creator's chosen tone. Do not impose tragedy, reconciliation,
  realism, spectacle, or a moral lesson unless selected.

## Boundaries

- This skill supports fictional screenplay work. It does not claim to predict
  platform performance, guarantee moderation approval, or replace copyright,
  legal, or safety judgment.
- When real people, recognizable brands, protected characters, current events,
  minors, self-harm, violence, discrimination, or illegal conduct are central,
  flag the issue at the risk gate and ask the creator how to proceed. Do not
  silently add realistic identifiers or public-figure likenesses.
- Do not say the model has permanently learned from the project. Retain and
  reuse project decisions only within the active work context unless the host
  provides an explicit persistence mechanism.
