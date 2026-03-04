# 🔬 NotebookLM Knowledge Extractor

**Complexity:** ⭐⭐⭐ Advanced  
**Best For:** Converting long-form video/podcast transcripts into deep presentation outlines  
**Source:** NotebookLM  
**Visual Style:** Structured & Insight-Rich  
**Created by:** Dhruv Chauhan

---

## 🎯 Goal

Transform long-form video or podcast transcripts into **deep-dive presentation outlines** — extracting mental models, frameworks, and actionable insights (not just summaries).

---

## 🛠️ THE PROMPT

```
ROLE: Expert knowledge extraction and synthesis assistant.
GOAL: Convert transcript into a concise, insight-rich slide deck outline.

EXTRACT:
1. Core ideas and key insights
2. Mental models and thinking frameworks
3. Mindset, values, and decision-making patterns
4. Daily habits and rituals

FORMAT FOR EACH SLIDE:
─────────────────────────────────
SLIDE [NUMBER]

THEME: [Topic area]
HEADLINE: [6-9 words — insight-driven]
CORE INSIGHT: [The non-obvious takeaway — 1-2 sentences]
MENTAL MODEL / FRAMEWORK: [If applicable]
EVIDENCE: [Quote, data, or example from the source]
VISUAL DIRECTION: [How to show this visually]
─────────────────────────────────

CONSTRAINTS:
- Signal over noise: Cut filler, keep principles
- Framework-first: Turn abstract ideas into transferable models
- Reality check: Note limitations and common misunderstandings
- Never add content not in the source
```

---

## 🎨 Visual Philosophy

- **Signal over Noise:** Strip away filler, focus on core principles
- **Framework-First:** Translate abstract thinking into transferable models
- **Reality Check:** Include limitations and common misunderstandings

---

## 📋 EXTRACTION PRIORITIES

When processing a transcript, prioritize in this order:

1. **Repeated ideas** — mentioned 3+ times = core message
2. **Numbered frameworks** — "3 things you need to..." = slide-ready
3. **Surprising claims** — counterintuitive = most memorable
4. **Specific numbers** — data with exact figures = credible
5. **Personal stories** — used to illustrate a point = humanizing

---

## 🔄 5-ROUND LAYERING STACK

Run these prompts in sequence for best results:

| Round | Prompt |
|-------|--------|
| 1 | Run the full extraction prompt |
| 2 | "Now add one practical exercise per slide" |
| 3 | "Now add the most common misconception per concept" |
| 4 | "Now connect each concept to a real-world scenario" |
| 5 | "Which 3 slides are the most important? Why?" |

---

## 💡 Best Used With

- Huberman Lab podcasts
- Lex Fridman interviews
- TED Talks
- Business strategy videos
- Personal development content

---

*Part of the Prompt Mania library by Dhruv Chauhan*
