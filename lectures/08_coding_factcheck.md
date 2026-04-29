# Fact-Check Report — Session 08: Coding and Data Analysis

## Summary
- **Errors flagged**: 1 (model version names from a referenced paper)
- **Imprecisions flagged**: 2 (EU ETS phrasing; "Codex GPT 4.5" model name)
- **Unverified references flagged**: 1 ("David" / "AP project" producing 10,000 papers)
- **Confirmed claims**: PNAS, PDSI, Anscombe's quartet, UC Berkeley Simpson example, Anthropic Economic Index, double machine learning cross-fitting, Polity 2 codes, QoG data portal, Julius.ai

---

### Issue 1: Model names in the agentic-AI vs human economists paper
- **Slide**: Agentic AI vs Human Economists (slide 21)
- **Claim**: "**Codex GPT-4.5** beats **Codex GPT-5.3**, beats **Claude Code**, beats human researchers — humans last."
- **Problem**: The paper being referenced is *A Comparison of Agentic AI Systems and Human Economists* (Grundl et al., 2025/2026, the "claude-code-economist" project replicating a DACA study). The systems compared are:
  - **Claude Code with Opus 4.6**
  - **Codex with GPT-5.4**
  - **Codex with GPT-5.3-Codex**
  There is no "Codex GPT-4.5" model. The lecturer likely meant **GPT-5.4** (mis-spoken or mis-transcribed as "GPD 4.5"). Also, the paper's headline finding is *not* that AI beats humans — it's that AI medians match human medians but with **tighter dispersion** (less variance, fewer extremes).
- **Suggested fix**: Replace "Codex GPT-4.5 beats Codex GPT-5.3, beats Claude Code, beats human researchers" with a description that matches the paper, e.g.: "the systems compared were **Claude Code (Opus 4.6)**, **Codex (GPT-5.4)**, and **Codex (GPT-5.3-Codex)**. The paper's headline: AI systems and humans land near the same median estimate, but the AI runs cluster much more tightly than the human runs do."
- **Source**: [Marginal Revolution post](https://marginalrevolution.com/marginalrevolution/2026/04/a-comparison-of-agentic-ai-systems-and-human-economists.html), [project site](https://claude-code-economist.com/), [paper PDF](https://claude-code-economist.com/data/paper.pdf)

### Issue 2: EU ETS in 2007
- **Slide**: The Five Steps Recipe (slide 12)
- **Claim**: "the collapse of the European **emissions trading scheme**" / "many countries or city countries collapsed completely and they stopped using it"
- **Problem**: What collapsed in 2007 was the **price** of EU ETS Phase 1 allowances (to ~€0.10 by September 2007), because Phase 1 permits could not be banked for Phase 2 and supply far exceeded emissions. **Countries did not stop using the ETS** — Phase 2 launched in 2008 and the system has continued through Phase 4 (2021–2030). The polished prose says "the collapse of the European emissions trading scheme," which is technically a price collapse, not a system collapse — readers may misinterpret.
- **Suggested fix**: Clarify to "the **price collapse** of the European emissions trading scheme in 2007 (Phase 1 allowances became unusable in Phase 2, driving prices to near zero)."
- **Source**: [Wikipedia: EU ETS](https://en.wikipedia.org/wiki/European_Union_Emissions_Trading_System), [European Commission — Development of EU ETS](https://climate.ec.europa.eu/eu-action/carbon-markets/eu-emissions-trading-system-eu-ets/development-eu-ets-2005-2020_en)

### Issue 3 (resolved): "David" / "AP project" / 10,000 papers
- **Slide**: The 1,000 Papers Problem (slide 20)
- **Resolved**: Instructor confirmed the reference: **David Yanagizawa-Drott** (University of Zurich), the **APE** project (*Autonomous Policy Evaluation*), producing on the order of **1,000 papers** (not 10,000). The transcript's "David from finally" is a transcription artifact; "AP project" → APE. Final qmd updated with correct name, affiliation, project name, and paper count.
- **Editorial note**: The lecturer's anecdote about a reviewer finding fabricated policy dates in "ape papers" was explicitly flagged by the lecturer as "I'll cut on the video." Since that anecdote, once attached to a named project, becomes a serious public allegation, the polished qmd generalizes it to a risk pattern ("if the model is incentivized to 'make it run,' it can invent data") without naming any project. This is intentional and matches the lecturer's stated intent to cut.

### Issue 4 (minor): Polity 2 sentinel codes
- **Slide**: The Five Steps Recipe (slide 12)
- **Claim**: "uses **–66** to code transition periods" (after faithfulness correction)
- **Problem**: Accurate as far as it goes — the lecturer only mentioned –66. For completeness: Polity 2 actually uses **three** sentinel codes that all fall well outside the [–10, +10] range — **–66** (interruption / foreign occupation), **–77** (interregnum / anarchy), and **–88** (transition). The course audience may benefit from the full list; the current text is faithful to the lecture but pedagogically thin.
- **Suggested fix**: Optional — a footnote could add: "(Polity 2 also uses –77 for interregnum and –88 for transition. All three sentinels need to be recoded before any linear analysis.)"
- **Source**: [Polity Project codebook (Center for Systemic Peace)](https://www.systemicpeace.org/inscrdata.html)

---

## Confirmed claims (no action needed)
- **PNAS** is correctly characterized as a top general-science journal.
- **PDSI (Palmer Drought Severity Index)**: developed by Wayne Palmer (1965); high values = wet, low values = dry. Correctly described in the lecture.
- **Tree-ring climate reconstruction**: dendrochronology is a well-established method for centuries-scale climate reconstruction.
- **Industrial Revolution ~1750 in the UK**: standard dating (some scholars use 1760).
- **UC Berkeley admissions Simpson's-paradox case (1973)**: the canonical real-world Simpson's paradox example.
- **Anscombe's quartet (Francis Anscombe, 1973)**: four datasets with identical means, variances, correlations, and regression coefficients but very different shapes.
- **Anthropic Economic Index**: real, regularly updated; country-level and US-state-level data with multiple waves.
- **Julius.ai**: real data-science assistant with a free tier.
- **Double machine learning requires cross-fitting** (Chernozhukov et al., *Econometrics Journal*, 2018) — cannot be re-derived in real time from a slider input, supporting the lecturer's "fake coefficients" anecdote.
- **QoG (Quality of Government) data**: real, hosted at the University of Gothenburg.
- **Stack Overflow traffic decline**: well documented — annual reports show steep usage drops since ChatGPT's release.
