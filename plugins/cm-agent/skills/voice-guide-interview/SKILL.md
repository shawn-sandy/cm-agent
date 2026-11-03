---
name: voice-guide-interview
description: Walks a user from writers they admire to a finished voice guide, with a sample piece and varied structures. Use when someone wants to define or document their writing voice or a brand voice.
license: MIT
metadata:
  author: shawn-sandy
  version: "0.1.0"
allowed-tools: Read Write Edit Glob Grep WebFetch
---

# Voice guide interview

Guide the user through building a voice guide the way a good editor would:
start from what they like to read, not from what they think they should write.
Many users say they are bad at writing, so never ask for a writing sample
first.

## Step 1 — Scope

Ask these together: who is this voice for (the user, a creator, or a company),
which content types matter most (articles, posts, scripts, videos), who the
reader is, and what the reader should be able to do after reading. Confirm the
reader and goal before drafting; they fill the guide's required audience
fields, so never guess them. Keep a personal voice and client or brand voices in separate guides.
If a brand has existing guidelines, read them first and treat them as
overrides.

## Step 2 — Gather examples

Ask for 4 to 7 links to writers, blogs, or posts they enjoy, plus one line on
what they like about each (clear, funny, well structured, personal). Tell them
to say when the list is complete, and wait. Acknowledge each link with a
running count. Invite one non-technical favorite.

## Step 3 — Read and analyze

Fetch each link. For each, note point of view, sentence length, humor, how it
opens, how it explains hard ideas, heading and layout style, how it closes, and
two short quotes. If a page cannot be fetched, say so and ask for the title or
pasted text. Do not guess at its content.

## Step 4 — Find the shared voice

Summarize the traits most examples share and call out where the user's stated
likes differ. Name the voice in three words, each with a "we are / we are not"
pair. Confirm with the user before going further.

## Step 5 — Draft the guide

`Read` `assets/voice-guide.template.md` and fill it in without changing its
section order, headings, or limits. The guide's own format is locked, but the
content it governs must not feel formulaic: section 6 is a menu of 3 to 6
structures, and the rule is never the same format twice in a row.

## Step 6 — Prove it

Write a short sample piece on a topic the user picks, in the new voice. Ask
what feels off (too playful, too long, wrong analogy) and revise once or twice.
Fold what they say back into the guide.

## Step 7 — Wrap up

Save the guide as one file. Offer next steps: turn it into a reusable skill,
create a blank copy of the template for other clients, or run a draft through
`humanize-text` to catch AI-sounding phrases.

## Rules

- Ask one or two questions at a time, and do as much as possible before the
  user answers.
- Quote and paraphrase sources briefly; never reproduce articles.
- Do not invent facts about the user. Mark guesses as guesses.
- Keep the user's voice separate from any client or brand voice.
