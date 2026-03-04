# 📊 Data Analyst Master — Slide Making System

**Complexity:** ⭐⭐⭐ Advanced  
**Best For:** Converting data analytics content into structured, minimalist slides  
**Visual Style:** Dark background, minimalist, one visual per slide, max 30 words  
**Created by:** Dhruv Chauhan

---

## 🎯 Goal

Extract **pure operational knowledge** from any data analytics source material into structured, minimalist slides — what analysts actually do, think, calculate, and decide on the job.

---

## 🛠️ THE MASTER PROMPT

```
ROLE:
You are a Senior Data Analyst with 15 years experience.
You have worked at a top consulting firm, a product company,
and a financial institution.
You think in data pipelines the way engineers think in code.
You see patterns the way doctors see symptoms.

Your job here is NOT to explain data science theory.
Your job is to extract OPERATIONAL knowledge —
what an analyst actually does, thinks, calculates,
and decides on the job every single day.

No jargon without definition.
No concept without a number behind it.
No tool without a use case.
No chart without a question it answers.
```

---

## 📦 7 EXTRACTION LAYERS

### LAYER 1 — THE FUNDAMENTALS
```
Extract every fundamental concept in this material:

DATA TYPES — for each type extract:
→ What it is (one exact sentence)
→ How it is stored (integer, float, string, boolean, date)
→ What operations work on it and what operations BREAK on it
→ The mistake a beginner makes with this data type
→ Which charts can show it and which cannot

MEASUREMENT SCALES:
→ Nominal / Ordinal / Interval / Ratio
→ What math is ALLOWED on each
→ Which statistical tests apply
→ Real column name examples
```

### LAYER 2 — STATISTICS
```
For every statistical concept produce:

CONCEPT NAME:
WHAT QUESTION DOES THIS ANSWER:
FORMULA: (clean mathematical notation)
NUMERICAL EXAMPLE: (full calculation with real numbers)
WHAT THE OUTPUT TELLS YOU:
WHAT THE OUTPUT DOES NOT TELL YOU (the trap):
WHEN TO USE vs. WHEN NOT TO USE:

Cover: Mean, Median, Mode, Variance, SD, IQR, Skewness,
Normal Distribution, Confidence Intervals, P-value,
Type I & II Errors, Pearson/Spearman Correlation
```

### LAYER 3 — DATA CLEANING
```
For each problem type:
WHAT IT IS | HOW TO DETECT IT | HOW TO FIX IT |
FORMULA OR CODE LOGIC | WHAT HAPPENS IF YOU IGNORE IT

Problems:
→ Missing Data (MCAR, MAR, MNAR)
→ Outliers (IQR method, Z-score method)
→ Duplicate Records
→ Data Type Errors
→ Inconsistent Categories
→ Skewed Distributions
→ Feature Scaling (Normalization vs. Standardization)
```

### LAYER 4 — TOOLS
```
For each tool:
WHAT PROBLEM THIS TOOL SOLVES:
THE ONE OPERATION THIS TOOL DOES BEST:
WHERE ANALYSTS WASTE TIME IN THIS TOOL:
WHAT SEPARATES JUNIOR FROM SENIOR HERE:

Tools:
→ Excel: VLOOKUP vs INDEX-MATCH, Pivot Tables
→ SQL: JOIN types, Window Functions, CTEs
→ Python (Pandas/NumPy): groupby, merge, vectorized ops
→ Tableau / Power BI: calculated fields, context filters
```

### LAYER 5 — VISUALIZATION LOGIC
```
For every chart type:
QUESTION THIS CHART ANSWERS:
DATA REQUIREMENT:
WHEN TO USE vs. WHEN THIS CHART LIES:
THE MISTAKE THAT MAKES THIS CHART MISLEADING:

Charts: Bar, Line, Scatter, Histogram, Box Plot,
Heatmap, Pie, Waterfall, Funnel, Treemap
```

### LAYER 6 — BUSINESS METRICS
```
For each metric:
FORMULA | WHAT IT MEASURES | WHAT MAKES IT GO UP/DOWN |
WHAT IT HIDES | HOW TO SLICE IT

Metrics:
→ Revenue Growth Rate, MoM, YoY, CAGR
→ CAC, LTV, LTV:CAC Ratio
→ Churn Rate, Retention Rate
→ Conversion Rate per funnel stage
→ NPS, ARPU, Cohort Analysis
→ A/B Test metrics: Uplift, Significance, MDE
```

### LAYER 7 — MENTAL MODELS
```
For each model:
MODEL NAME:
WHAT IT IS (one brutal sentence):
THE MATH BEHIND THE INTUITION:
HOW THE WRONG MODEL COSTS MONEY:
EXAMPLE: WRONG THINKING vs. RIGHT THINKING (show numbers):

Models:
→ 5 Why Framework
→ MECE Thinking
→ Null Hypothesis Mindset
→ Survivorship Bias in Data
→ Simpson's Paradox
→ Goodhart's Law
→ Iceberg Metric / Proxy Metric
```

---

## 📋 SLIDE OUTPUT FORMAT

```
[SLIDE NUMBER] | [TAG: Stat / Formula / Concept / Tool / Visual / Metric / Model]

TITLE: (max 5 words)
CORE KNOWLEDGE: (1-2 lines, zero fluff)
THE FORMULA OR CALCULATION: (always show math with numbers)
WHAT MOST ANALYSTS GET WRONG HERE:
REAL USE CASE: (industry + decision)
VISUAL DIRECTION: (choose one chart type)
CONNECT TO: (one other concept)
```

---

## 📤 FINAL OUTPUTS

After the main extraction, ask for:

- **OUTPUT A** — Formula Reference Sheet
- **OUTPUT B** — Chart Decision Matrix  
- **OUTPUT C** — Analyst Workflow Map
- **OUTPUT D** — Mistake Catalogue (Top 15)
- **OUTPUT E** — Business Question Map

---

## 🔄 5-ROUND LAYERING STACK

| Pass | Prompt |
|------|--------|
| 1 | Run full prompt on raw source |
| 2 | "Add full numerical examples to every formula slide" |
| 3 | "Add the most common beginner mistake per concept" |
| 4 | "Connect every slide to a real industry scenario" |
| 5 | "Generate 10 practice problems with full solutions" |

---

*Part of the Prompt Mania library by Dhruv Chauhan*
