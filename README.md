# NFL Draft Value Analysis (2005–2024)

An exploratory data analysis project investigating whether NFL draft position
truly predicts player success, which franchises draft best, and which positions
carry the highest bust risk when selected in the early rounds.

Built as an extra credit project for a data science course, this notebook
analyzes 5,109 draft picks across 20 NFL Drafts using Python and Jupyter.

---

## 🏈 Background

As the 2026 NFL Draft kicks off in Green Bay, one of the most debated
questions in football remains: are high draft picks actually worth it?
With teams trading entire draft classes for a single first-round pick,
the stakes of drafting well have never been higher.

This project uses 20 years of NFL draft data (2005–2024) to find out.

---

## 📊 Analysis Overview

The notebook is broken into three parts:

**Part 1: Does Draft Position Predict Career Performance?**
- Average career AV by round and by pick number
- Identification of value drop-off zones across the draft
- Rolling average trend analysis across all 260+ picks

**Part 2: Which NFL Teams Draft Best?**
- Expected AV calculated for every pick position
- Draft surplus metric (actual AV − expected AV) for each pick
- Team rankings by average surplus across all 32 franchises

**Part 3: Which Position is Most Likely to Bust?**
- Bust rate by position for rounds 1 and 2 picks
- Average and median career AV by position
- Identification of safest and riskiest positions to draft early

---

## 🔑 Key Findings

- The biggest drop in draft value is between round 1 and round 2 — rounds
  4 through 7 are nearly interchangeable in terms of expected output
- **Green Bay** leads all franchises with the highest average draft surplus
  (+3.4 AV per pick), while the **Raiders** rank last (-4.0 AV per pick)
- **Cornerback** is the riskiest early round investment with a 49.1% bust
  rate, while **Offensive Line** is the safest at just 14.0%
- QB has the highest average career AV when they hit, but nearly 1 in 3
  early QB picks still fail to produce meaningful NFL careers
