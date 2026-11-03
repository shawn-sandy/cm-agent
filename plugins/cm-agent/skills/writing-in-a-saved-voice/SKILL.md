---
name: writing-in-a-saved-voice
description: Drafts or rewrites content in a saved voice guide's voice, rotating structures. Use when asked to write, draft, or edit a post, article, or script in someone's voice, or as a brand or client.
license: MIT
metadata:
  author: shawn-sandy
  version: "0.1.0"
allowed-tools: Read Write Edit Glob Grep
---

# Writing in a saved voice

Draft or rewrite content so it sounds like the owner of a saved voice guide.
Use one guide per piece. Never blend a personal voice with a client or brand
voice.

## Step 1 — Find the guide

Voice guides live in the user's project at `voice/<owner-slug>.md`, written by
`voice-guide-interview`. `Glob` for `voice/*.md`.

- One guide: confirm it is the right voice.
- Several: list them and ask which one to use.
- None: say so and offer to run `voice-guide-interview` first. Do not invent a
  voice. `assets/example-voice-guide.md` shows what a finished guide looks
  like; do not draft from it unless the user asks for that voice.

`Read` the chosen guide in full.

## Step 2 — Confirm the brief

Settle three things, asking only for what is missing: topic, content type
(article, post, script, video), and reader. Do not invent facts, numbers, or
quotes; ask for them or mark a gap.

## Step 3 — Pick a structure

Choose one format from the guide's structure menu. If the user names their last
piece, pick a different format and vary the opener and closer. Never reuse the
same shape twice in a row.

## Step 4 — Draft

Write to the guide: its point of view, word rules, sentence rules, and media
rules for any code, image, or video. Support every claim with an example.

## Step 5 — Check

Run the guide's pre-publish check against the draft and fix what fails. Then
offer `humanize-text` in review-only mode for AI-sounding phrases.

## Step 6 — Hand back

Return the draft with a two-line note: which structure you used and which guide
rules you leaned on. If feedback reveals a lasting preference, suggest adding it
to the guide file.
