# [BOOK TITLE] — Project Bible

> This is the single source of truth for this book. All locked decisions live here.
> At the start of every writing session, re-read this file before doing anything else.
> **Also read:** `STYLE_GUIDE.md`, `research/voice-profile.md`, `CHAPTER_LOG.md`

---

## Book Overview (LOCK THESE ONCE DECIDED)

| Field | Value |
|-------|-------|
| **Working title** | [TITLE] |
| **Author** | [YOUR NAME] |
| **Subtitle** | [SUBTITLE — or TBD] |
| **One-sentence premise** | [What is this book in one sentence?] |
| **Core promise to the reader** | [What will they be able to do after reading it?] |
| **Target reader** | [Be specific — not "people interested in X," but who exactly] |
| **What this book is NOT** | [What are you deliberately leaving out?] |
| **What makes this book different** | [Why buy this over everything else on the shelf?] |

---

## Book Structure (LOCK ONCE FINALIZED)

| Chapter | Title | Status | Target Words |
|---------|-------|--------|-------------|
| 1 | [Title] | Not started | [X] |
| 2 | [Title] | Not started | [X] |
| 3 | [Title] | Not started | [X] |

**Total word count target:** [X] words
**Format:** Print + ebook / Print only / Ebook only
**Trim size:** [e.g., 6x9 inches trade paperback]

---

## Locked Decisions
*(Add decisions here as they are made and confirmed. Never undo these without
explicit discussion.)*

1. [Decision]
2. [Decision]

---

## Anti-Hallucination & Drift Prevention Rules (LOCKED)

These rules exist to prevent the AI from inventing facts, drifting from approved
decisions, or paraphrasing research in ways that introduce inaccuracies.

1. **Never invent personal facts.** If the author hasn't confirmed it, don't write it.
   Mark the slot with `[AUTHOR'S STORY: topic]` and ask.
2. **Never invent historical or technical facts.** Flag anything uncertain with `[VERIFY]`
   before it goes into manuscript. Do not smooth over uncertainty with confident-sounding prose.
3. **Never directly quote or closely paraphrase copyrighted sources.** All research must
   be synthesized into original writing.
4. **Never drift from locked decisions.** If something in this file says LOCKED or
   CONFIRMED, do not change it without explicit approval.
5. **No chapter is approved until the author explicitly says so.** "Looks good" is not
   approval. The word "approved" must appear in the conversation.
6. **At the start of every session, re-read PROJECT.md, CHAPTER_LOG.md,
   `research/voice-profile.md`, and `STYLE_GUIDE.md`** before drafting anything.
7. **Credit all sources.** Track in `research/source-ledger.md` and carry into Appendix.
   Popular nonfiction attribution style — not academic citation format.
8. **Personal content (videos, recordings, notes) supplies voice and stories, not facts.**
   Use for voice, anecdotes, and chapter material — not as factual sources unless verified.
   See `research/transcript-ingest-rules.md`.

*Add additional rules here as needed for your specific topic.*

---

## Rules for the AI / Ghostwriter

1. Do not write the whole book at once. One chapter at a time.
2. Before drafting each chapter, build and present a chapter dossier for the author's approval.
3. For personal stories: check `notes/personal-stories.md` and approved manuscript first.
   Ask before inventing. Never paste raw transcript text into the manuscript.
4. Do not invent personal stories. Do not claim the author experienced something unless
   it appears in approved manuscript, story bank, or they confirmed it.
5. Keep writing grounded in real experience specific to this subject.
6. Preserve all locked decisions recorded in this file.
7. When a chapter is approved, treat it as the official draft until the author requests changes.
8. Maintain `CHAPTER_LOG.md` with current approval status after every session.

---

## Chapter Workflow

For every chapter — follow these steps in order. Do not skip any step.
Reference files: `docs/chapter-dossier-template.md`, `research/repetition-log.md`,
`research/source-ledger.md`, `research/terminology.md`, `STYLE_GUIDE.md`.

| Step | Action | Reference |
|------|--------|-----------|
| 1 | **Build the chapter dossier.** Fill out `docs/chapter-dossier-template.md` for this chapter. Include: mission, reader questions, key concepts, claims needing sources, available personal stories, what NOT to repeat (check `repetition-log.md`), terminology to use, section outline. | `docs/chapter-dossier-template.md` |
| 2 | **Author approves the dossier.** No prose is drafted until the dossier is approved. Ask about any personal story slots marked `[AUTHOR'S STORY: topic]`. | Author's explicit "approved" |
| 3 | **Confirm research gaps are closed.** Any item flagged as a research gap in the dossier must be resolved first. Log any new factual claims in `research/source-ledger.md`. | `research/source-ledger.md` |
| 4 | **Draft one section at a time.** Not the whole chapter at once. Context to load for every session: `PROJECT.md` + `STYLE_GUIDE.md` + `research/voice-profile.md` + `research/terminology.md` + the chapter dossier + relevant research files + relevant story notes + the previous chapter's final draft. | `STYLE_GUIDE.md` |
| 5 | **Run Post-Draft Voice Check after each section.** Banned phrase scan → AI structure check → specificity check → rhythm check → read-aloud gate. Do not move to the next section until this passes. | `STYLE_GUIDE.md` — Post-Draft Voice Check |
| 6 | **Author reviews and revises.** Provide a short list of possible gaps or improvements. Revise based on feedback. | Author's feedback |
| 7 | **Run repetition check on complete chapter draft.** Compare against `research/repetition-log.md` and all previous chapter summaries. Flag any concept, story, or phrasing that has appeared before. | `research/repetition-log.md` |
| 8 | **Verify all factual claims.** Every claim must appear in `research/source-ledger.md` with at least Medium confidence. Any Low confidence claims must be resolved or removed before locking. | `research/source-ledger.md` |
| 9 | **Lock the chapter.** Update `research/repetition-log.md` with all concepts and stories used. Update story status in `notes/personal-stories.md`. | `research/repetition-log.md` |
| 10 | **Mark APPROVED in CHAPTER_LOG.md.** The word "approved" must appear explicitly. "Looks good" is not approval. | `CHAPTER_LOG.md` |

---

## Book Format & Production Specs

| Spec | Value |
|------|-------|
| Trim size | [6x9 inches] |
| Target word count | [X] words |
| Photos / illustrations | [Yes / No] |
| Publication format | [Print + ebook / Print only] |
| Interior layout tool | [TBD] |
