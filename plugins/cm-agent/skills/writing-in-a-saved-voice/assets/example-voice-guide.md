# Shawn's voice guide

Built from six technical reads: Matt Pocock, Sara Soueidan, Josh Comeau, Smashing Magazine (structure), Heydon Pickering, Addy Osmani.

## 1. Audience and purpose
Working front-end and AI-assisted developers, and non-technical readers when the topic is introductory. Each piece should leave the reader able to do or decide something.

## 2. Personality (three words)
**Direct, curious, lightly funny.**
- Direct, not blunt for show. Not preachy.
- Curious, not all-knowing. Admit what you got wrong or didn't know.
- Lightly funny, not jokey. One dry aside beats five emoji.

## 3. Point of view and register
First person plus "you". Contractions yes. Casual-to-conversational. Dry, self-deprecating humor. Like a colleague sharing what worked.

## 4. Words
- Use plain verbs ("use", not "leverage"), concrete nouns, analogies for hard ideas.
- Avoid stock AI words (delve, robust, seamless, tapestry), "not just X but Y", puffery, empty closing summaries, more than one emoji per piece.

## 5. Sentence rules
- Mostly short and declarative; one long sentence allowed when explaining a mechanism.
- A short claim line after a longer explanation ("Plans shouldn't be novels.").
- Open sentences with "So," "But," "Now," "Let's" when it sounds like speech.
- One idea per paragraph. One-line paragraphs sparingly.
- Back every claim with an example, code, or source.

## 6. Structure menu (rotate; never the same format twice in a row)
Always: thesis or hook up front, short paragraphs, headings that are practical statements or questions. Vary the opener, section count, and closer from the last piece.

| Format | When | Shape |
|---|---|---|
| Problem then fix | tutorials, bug write-ups | show it broken, explain why, fix it, note gotchas |
| Misconception first | explainers | state the common wrong idea, correct it, show a short example |
| Story then lesson | personal posts | short anecdote or confession, the lesson, one takeaway |
| Short opinion | posts, hooks | claim in line one, one example, one takeaway |
| Walkthrough | guides | numbered steps, a try-it-this-week close |

Longer articles (over about 1,200 words): add a table of contents. Close by circling back to the thesis or with a short numbered recap.

## 7. Media rules
- **Code:** one idea per snippet, shortest working example, a line before saying what it shows and a line after saying what to notice. Broken first, then fixed. Language label always.
- **Images:** each makes one point and is referenced in the text. Crop tight, real alt text, WebP.
- **Video:** short, one idea each; point in the first 10 seconds; captions; describe it in the text so the post works without it.
- **Test:** remove the media and the text still makes sense.

## 8. Pre-publish check
1. Is the thesis in the first paragraph?
2. Does every claim have an example?
3. Is there at most one dry joke, and no puffery?
4. Did you admit something you didn't know or got wrong?
5. Does the structure differ from your last piece?
Then run `humanize-text` in review-only mode.
