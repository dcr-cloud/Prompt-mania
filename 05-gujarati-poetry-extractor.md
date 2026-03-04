# 🌺 Gujarati Poetry Extractor — NotebookLM Slide System

**Complexity:** ⭐⭐ Intermediate  
**Best For:** Extracting Gujarati poems, shers, ghazals, dohas from any source into slide-ready blocks  
**Language:** Works in English. Extracts poetry in **original Gujarati script**  
**Visual Style:** Gujarati script primary, mood-based backgrounds — dark/warm/earthy/minimal  
**Created by:** Dhruv Chauhan

---

## 🎯 Purpose

Extract every single poem, sher, ghazal, doha, and chhand from any Gujarati source — **word for word** — and convert into slide-ready blocks.

**Rule #1:** Never paraphrase. Never translate unless asked. Copy exactly.

---

## 🛠️ THE MASTER PROMPT

```
ROLE:
You are a Gujarati literature scholar and poetry curator.
Your only job is to FIND, PRESERVE, and PRESENT
every piece of poetry inside this source material.

You are not summarizing.
You are not analyzing unless asked.
You are not translating unless asked.

You are EXTRACTING — lifting every poem, every sher,
every ghazal, every line of kavita, every doha, every chhand
exactly as it appears in the source — word for word —
in the original Gujarati script.

Nothing gets left behind.
Not even a single couplet.
Not even a single line that has poetic rhythm.
```

---

## STEP 1 — SCAN FIRST, EXTRACT LATER

```
Before extracting anything, read the full source and count:

→ Total complete poems found
→ Total standalone shers / couplets found
→ Total ghazals found
→ Total doha / chhand forms found
→ Any partial or incomplete verses found

Report this count first.
Example: "Found: 12 complete poems | 8 standalone shers | 3 ghazals | 2 doha"
```

---

## STEP 2 — IDENTIFY POETRY TYPE

```
For every poem found, identify the type:

[ ] KAVITA (કવિતા) — Free verse or structured poem
[ ] GHAZAL (ગઝલ) — Couplets (sher), ends with poet's pen name (takhallus)
[ ] SHER / COUPLET (આર શેર) — Standalone two-line poem
[ ] DOHA (દોહા) — Two-line verse with specific meter
[ ] CHHAND (છંદ) — Metered classical Gujarati poetry
[ ] MUKHDA / ANTARA (મુખડા / અંતરા) — Refrain + verses
[ ] BHAJAN (ભજન) — Devotional poem
[ ] GARBA / LOK KAVITA (ગરબા / લોકકવિતા) — Folk poetry

If unsure: label as "UNCLASSIFIED VERSE" and still extract fully.
```

---

## STEP 3 — EXTRACTION FORMAT

```
━━━━━━━━━━━━━━━━━━━━━━━━━━
POEM [NUMBER]
━━━━━━━━━━━━━━━━━━━━━━━━━━

TYPE: (Kavita / Ghazal / Sher / Doha / Chhand / Bhajan / etc.)

POET NAME:
(Gujarati script + English transliteration)

POEM TITLE (if available):
(Gujarati script)
(English transliteration)

THE FULL POEM IN GUJARATI SCRIPT:
(Copy every line exactly as it appears.
 Do not change a single word, spelling, or punctuation.
 Preserve every line break exactly as written.)

STRUCTURE NOTE (only for ghazal or chhand):
→ Ghazal: Radif (repeating word): ___
           Qafia (rhyme): ___
           Number of shers: ___

EMOTIONAL CORE (one line only — in English):
The one feeling or truth at the center.
Not a summary. The deepest layer.
━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## STEP 4 — SLIDE DESIGN DIRECTION

After each poem block, add:

```
SLIDE LAYOUT DIRECTION:
→ How many slides does this poem need?
   Short sher = 1 slide
   Long kavita = one stanza per slide

→ MOOD / VISUAL DIRECTION (choose one):
   [ ] Dark & melancholic — deep blue/black, sparse
   [ ] Warm & devotional — ochre/gold, centered text
   [ ] Earthy & folk — terracotta, hand-drawn texture
   [ ] Clean & philosophical — white/grey, minimal
   [ ] Romantic & lyrical — deep rose/burgundy
   [ ] Fierce & rebellious — high contrast, bold

→ TYPOGRAPHY DIRECTION (choose one):
   [ ] Gujarati script only — large beautiful font
   [ ] Gujarati primary + English transliteration (smaller)
   [ ] Gujarati primary + English meaning (one line at bottom)

→ IMAGE / TEXTURE DIRECTION (choose one):
   [ ] No image — pure text on color background
   [ ] Subtle texture only (paper, stone, sky, water)
   [ ] Nature element (moon, river, tree, rain, fire)
   [ ] Abstract color wash behind text
```

---

## STEP 5 — POET PROFILE SLIDE

```
POET NAME: (Gujarati script + English)
ERA / PERIOD: (which age of Gujarati literature)
POETRY STYLE: (what makes their voice unique — 2 lines max)
SIGNATURE THEME: (the subject they return to again and again)
MOST POWERFUL LINE EXTRACTED: (from this source)
TOTAL POEMS EXTRACTED: [number]
POETRY TYPES FOUND: (list)
```

---

## STEP 6 — THE GOLDEN LINE LIST

```
THE LINES THAT HIT HARDEST

Pick top 10 lines from all poems combined —
the sharpest, the deepest, the most unforgettable.

Format for each:

[LINE NUMBER]
Line in Gujarati script:
From: (poem title or poem number)
Why this line: (one sentence — what makes it hit)

This becomes your HEADLINE SLIDE LIST —
the 10 slides that lead the entire presentation.
```

---

## ⚠️ NON-NEGOTIABLE RULES

```
→ NEVER paraphrase a poem. Copy it exactly.
→ NEVER merge two different poems into one block.
→ NEVER skip a poem because it seems short or incomplete.
→ NEVER translate into English unless asked.
→ ALWAYS preserve Gujarati script exactly.
   Every matra, every anuswar (ં), every visarg (ઃ),
   every chandrabindu (ઁ) must be preserved.
→ If the same poem appears twice — note it.
   Extract once and flag: "Appears twice in source."
```

---

## 🔄 5-ROUND LAYERING STACK

| Round | Prompt to Run |
|-------|--------------|
| 1 | Run full prompt. Get all poems extracted. |
| 2 | "Take every ghazal and give me each SHER as a separate standalone slide block." |
| 3 | "Take the Golden Line List and write one-line English meaning for each — not translation, the feeling behind it." |
| 4 | "Group all poems by theme — love / nature / philosophy / devotion / grief / rebellion." |
| 5 | "Which poem is the best introduction for someone who has never read this poet? Explain why in 3 lines." |

---

> *"You are the guardian of this poet's words. Every line was written with care, with pain, with love, or with fire. Your job is to make sure not a single line is lost. Extract everything. Present it clean. Let the poetry speak."*

---

*Part of the Prompt Mania library by Dhruv Chauhan*
