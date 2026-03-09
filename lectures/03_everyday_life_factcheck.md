# Fact-Check Report: Session 03 — General Use

**Date**: 2026-03-09
**File reviewed**: `website/lectures/03_everyday_life_draft3.qmd`
**Checker**: Content Expert Agent (Claude Opus 4.6)

---

## Summary

11 issues identified: 4 errors, 5 imprecisions, 2 items that could not be verified.

---

### Issue 1: Misspelling of Sebastien Bubeck's first name
- **Slide**: Slide 1 (GenAI & Research --- 03. General Use)
- **Claim**: "**Sebastian Bubeck** argues that sparks of AGI were already visible in early models."
- **Problem**: The correct spelling is **Sebastien Bubeck** (or with the accent: Sebastien). The text uses "Sebastian" (no final 'e'). This is a minor but verifiable error. His official name is Sebastien Bubeck, as listed on his Microsoft Research page, personal website, and Wikipedia.
- **Suggested fix**: Replace "Sebastian Bubeck" with "Sebastien Bubeck" throughout.
- **Source**: [Sebastien Bubeck — Microsoft Research](https://www.microsoft.com/en-us/research/people/sebubeck/); [Wikipedia](https://en.wikipedia.org/wiki/S%C3%A9bastien_Bubeck)
- **Freshness**: Verified March 2026.

---

### Issue 2: Anthropic did not "reject a contract" — the situation is more nuanced
- **Slide**: Slide 1 (GenAI & Research --- 03. General Use)
- **Claim**: "Anthropic's recent decision to reject a US Department of Defense contract over mass surveillance and autonomous weapons concerns, while OpenAI accepted"
- **Problem**: This is an imprecision that could mislead. Anthropic did not reject a DoD contract outright. Anthropic *had* a DoD contract (a $200M transaction agreement awarded in July 2025). The dispute arose in January 2026 when Defense Secretary Pete Hegseth demanded Anthropic remove its prohibitions on autonomous weapons and domestic mass surveillance. Anthropic *refused to modify the terms*, and the government then banned Anthropic products and moved to designate the company a national security risk. Meanwhile, OpenAI announced a separate Pentagon deal. Framing it as "Anthropic rejected a contract while OpenAI accepted" collapses a complex multi-month dispute into a misleading binary.
- **Suggested fix**: "Anthropic's refusal to remove safety guardrails from its existing Pentagon contract — specifically prohibitions on autonomous weapons and domestic mass surveillance — which led to a government ban on Anthropic products, while OpenAI moved to fill the gap with its own Pentagon deal"
- **Source**: [CNN — Anthropic rejects latest Pentagon offer](https://www.cnn.com/2026/02/26/tech/anthropic-rejects-pentagon-offer); [NPR — OpenAI announces Pentagon deal after Trump bans Anthropic](https://www.npr.org/2026/02/27/nx-s1-5729118/trump-anthropic-pentagon-openai-ai-weapons-ban); [TechPolicy.Press — Timeline of the Anthropic-Pentagon Dispute](https://www.techpolicy.press/a-timeline-of-the-anthropic-pentagon-dispute/)
- **Freshness**: Verified March 2026. This situation is still evolving.

---

### Issue 3: AlphaGo was initially trained on human games, not purely through reinforcement learning
- **Slide**: Slide 9 (GENAI AND CREATIVITY)
- **Claim**: "This creativity emerged from **reinforcement learning**, not imitation. The model was not trained to copy human play; it discovered novel strategies by optimizing purely for winning."
- **Problem**: This is an **error**. The original AlphaGo (the version that played Lee Sedol in 2016 and produced Move 37) was first trained via supervised learning on approximately 30 million moves from 160,000 human games, *then* further trained through self-play reinforcement learning. It was not "purely" reinforcement learning. The claim that "The model was not trained to copy human play" is factually wrong for AlphaGo. (The later AlphaGo Zero and AlphaZero *were* trained purely from self-play, but Move 37 came from the original AlphaGo.) The creativity of Move 37 likely emerged from the reinforcement learning phase, but the model's foundation included extensive human game data.
- **Suggested fix**: "This creativity emerged from a combination of learning from human expert games and reinforcement learning through self-play. While AlphaGo was initially trained on millions of human moves, its self-play training phase allowed it to discover novel strategies beyond human conventions — Move 37 was a product of this exploration."
- **Source**: [DeepMind — AlphaGo](https://deepmind.google/research/alphago/); [Wikipedia — AlphaGo versus Lee Sedol](https://en.wikipedia.org/wiki/AlphaGo_versus_Lee_Sedol)
- **Freshness**: Verified March 2026.

---

### Issue 4: University of Montana creativity study — task description appears inaccurate
- **Slide**: Slide 10 (GENAI AND CREATIVITY)
- **Claim**: "A study from the **University of Montana** tested creativity more directly. Participants wrote a short text about a city of the future, and blind human judges rated the creativity of each output."
- **Problem**: The well-known University of Montana creativity study (Guzik et al., 2023) used the **Torrance Tests of Creative Thinking (TTCT)**, a standardized creativity assessment involving multiple types of tasks (generating questions, guessing causes, product improvement, imagining consequences, etc.) — not specifically "a short text about a city of the future." The study compared 8 ChatGPT responses against 24 UM students and 2,700 national college students. A separate 2025 study in *Humanities and Social Sciences Communications* did examine "future cities imagined by ChatGPT-4o," but that is a different paper by different authors. The "city of the future" framing may come from the instructor's paraphrase of one TTCT sub-task, but as written it mischaracterizes the study's methodology.
- **Suggested fix**: Either (a) describe the TTCT methodology accurately ("participants completed the Torrance Tests of Creative Thinking, a standardized battery of creative thinking tasks"), or (b) verify from the transcript whether the instructor was referring to a different study entirely and cite it correctly.
- **Source**: [University of Montana — AI Tests Into Top 1% for Original Creative Thinking](https://www.umt.edu/news/2023/07/070523test.php); [StudyFinds — ChatGPT scores in the top 1%](https://studyfinds.org/chatgpt-original-creative-thinking/)
- **Freshness**: Verified March 2026.

---

### Issue 5: The creativity study compared against UM students and national norms, not "average Americans"
- **Slide**: Slide 10 (GENAI AND CREATIVITY)
- **Claim**: "An important caveat: the participants were **average Americans**, not professional writers."
- **Problem**: Imprecision. The human comparison group was 24 University of Montana students (from entrepreneurship and personal finance classes), plus national norms from 2,700 college students who took the TTCT in 2016. Calling them "average Americans" is a loose characterization — they were college students, a specific demographic. The broader point (not professional creatives) still holds, but "average Americans" overstates the generality of the sample.
- **Suggested fix**: "the participants were **college students**, not professional writers or trained creatives"
- **Source**: [University of Montana — AI Tests Into Top 1%](https://www.umt.edu/news/2023/07/070523test.php)
- **Freshness**: Verified March 2026.

---

### Issue 6: Jagged Frontier study used GPT-4, not ChatGPT
- **Slide**: Slide 8 (CHATGPT: USELESS?)
- **Claim**: "Boston Consulting Group consultants with access to ChatGPT worked faster"
- **Problem**: Imprecision. The Dell'Acqua et al. (2023) study used **GPT-4** specifically, not "ChatGPT" generically. The paper's experimental conditions were "GPT-4 AI access" and "GPT-4 AI access with a prompt engineering overview." While GPT-4 was accessible via ChatGPT at the time, "ChatGPT" could be interpreted as any version (including GPT-3.5). The 40% quality improvement figure is specific to GPT-4.
- **Suggested fix**: Replace "with access to ChatGPT" with "with access to GPT-4" for precision.
- **Source**: [Harvard Business School — Navigating the Jagged Technological Frontier](https://www.hbs.edu/faculty/Pages/item.aspx?num=64700)
- **Freshness**: Verified March 2026.

---

### Issue 7: PDF visual analysis limit is 100 pages, not "under 100 pages"
- **Slide**: Slide 21 (MORE CONTEXT)
- **Claim**: "For **PDFs under 100 pages**, the model reads both text and visual elements"
- **Problem**: Minor imprecision. According to Anthropic's documentation, Claude analyzes visual elements for PDFs up to 100 pages (inclusive). Beyond 100 pages, text is still extracted but images/charts are not visually analyzed. "Under 100 pages" could imply 99 pages is the limit. The actual file size limit is 32 MB (not 30 MB as stated — see Issue 8).
- **Suggested fix**: "For PDFs of **up to 100 pages**" (and verify the current documentation, as these limits change).
- **Source**: [Claude API Docs — PDF support](https://platform.claude.com/docs/en/build-with-claude/pdf-support)
- **Freshness**: Verified March 2026. These limits may have changed.

---

### Issue 8: File size limit appears to be 32 MB, not 30 MB
- **Slide**: Slide 21 (MORE CONTEXT)
- **Claim**: "Practical limits to keep in mind: **30 MB per file**"
- **Problem**: Multiple sources (including Anthropic's documentation) cite the limit as **32 MB** per file, though some third-party sources do say 30 MB. The 20 files per chat limit is confirmed as accurate.
- **Suggested fix**: Verify against current Anthropic documentation. If 32 MB, update to "**32 MB per file**."
- **Source**: [Anthropic Help Center — Uploading files to Claude](https://support.claude.com/en/articles/8241126-uploading-files-to-claude); multiple third-party sources confirm both 30 MB and 32 MB — check official docs at time of delivery.
- **Freshness**: March 2026. Limits may have been updated since the lecture was recorded.

---

### Issue 9: Fotopoulos and Gombal study — cannot verify
- **Slide**: Slide 38 (Thought Diversity)
- **Claim**: "Research from the University of Neuchatel's business school (Fotopoulos and Gombal) shows that commercial and R&D professionals naturally propose different types of solutions"
- **Problem**: **Cannot verify.** Multiple web searches for "Fotopoulos and Gombal" at the University of Neuchatel returned no results. The name "Gombal" may be a transcription error from the lecture audio. The general finding (AI reduces diversity of solutions across professional groups) is well-supported by other research — notably Doshi and Hauser (2024), "Generative AI enhances individual creativity but reduces the collective diversity of novel content" in *Science Advances*. But the specific attribution to "Fotopoulos and Gombal" at Neuchatel cannot be confirmed.
- **Suggested fix**: Either (a) verify the correct author names from the instructor, or (b) if the paper cannot be located, replace with the verified Doshi and Hauser (2024) citation from *Science Advances*, which makes the same point. Add a note: `% Citation needs verification: Fotopoulos and Gombal, Neuchatel — not found in searches.`
- **Source**: [Doshi & Hauser (2024) — Science Advances](https://www.science.org/doi/10.1126/sciadv.adn5290)
- **Freshness**: March 2026.

---

### Issue 10: Nestle SEO/LLM strategy claim — cannot verify
- **Slide**: Slide 18 (PROMPT ENGINEERING 101)
- **Claim**: "Nestle, for example, is rethinking its entire SEO strategy because consumers increasingly ask LLMs questions instead of searching Google --- and Nestle wants *its* answers surfacing"
- **Problem**: **Cannot verify.** Web searches for Nestle specifically rethinking its SEO strategy for LLMs returned no results. Many companies are adapting SEO strategies for LLM search (this is a well-documented trend), but the specific attribution to Nestle as an example could not be confirmed. This may come from a talk, interview, or internal presentation the instructor referenced.
- **Suggested fix**: If the Nestle example cannot be sourced, replace with "Major consumer brands are rethinking their SEO strategies..." or find a verifiable company example. Alternatively, add `% Source needed: Nestle SEO/LLM claim — not found in public sources.`
- **Source**: General trend confirmed; specific Nestle claim unverified.
- **Freshness**: March 2026.

---

### Issue 11: NotebookLM described as having a special "architecture" for source grounding
- **Slide**: Slide 16 (LLMS MAKES MISTAKES! SOLUTION 3: PROVIDE THE SOURCE)
- **Claim**: "NotebookLM's architecture is specifically optimized for source-grounded responses"
- **Problem**: Imprecision. NotebookLM uses Gemini models with a RAG (Retrieval-Augmented Generation) framework — the same general technique available to other tools. It is not a fundamentally different "architecture" but rather a product design choice that restricts the model to user-uploaded sources and enforces citation. Research does show NotebookLM has lower hallucination rates (around 13%) compared to ChatGPT and Gemini in open mode (around 40%), but this is primarily due to the product's restrictive design (refusing to answer from training data), not a novel architectural innovation.
- **Suggested fix**: "NotebookLM is specifically designed to generate responses grounded in your uploaded sources, with built-in citation and strict limits on using training data — resulting in substantially lower hallucination rates than general-purpose LLMs."
- **Source**: [NotebookLM research and reviews](https://www.emergentmind.com/topics/notebooklm); [Source-grounded AI tool analysis](https://insidescienceresources.wordpress.com/2025/12/16/notebooklm-exploring-a-source-grounded-ai-tool/)
- **Freshness**: Verified March 2026.

---

## Items Verified — No Issues Found

The following claims were checked and found to be accurate:

- **Bubeck's "Sparks of AGI" paper** exists and argues what is described (Microsoft Research, 2023). Note: Bubeck left Microsoft for OpenAI in October 2024.
- **Roman Yampolskiy** is correctly described as having a cautious, risk-focused view on AI (University of Louisville, AI safety researcher).
- **Jagged Frontier 40% quality improvement** — confirmed: GPT-4 boosted human-rated performance by over 40% on tasks within the AI frontier (Dell'Acqua et al., 2023).
- **LM Arena / arena.ai** — confirmed as a real benchmarking platform with the URL arena.ai and leaderboard across text, code, vision, etc.
- **OpenAI removed military use ban** — confirmed: OpenAI quietly removed "military and warfare" from its usage policy in January 2024.
- **Claude file limits: 20 files per chat** — confirmed.
- **W.E.I.R.D. bias** concept — correctly described (Western, Educated, Industrialized, Rich, Democratic).
- **GPTZero** — confirmed as a real AI detection tool, though its accuracy is debated (claims 95.7% detection, but independent testing shows higher false positive rates).
- **Process vs. output framework for learning** — this is the instructor's pedagogical framing (opinion), not a factual claim. Appropriate as presented.

---

## Overall Assessment

The draft is largely accurate and well-grounded. The most significant factual error is **Issue 3** (AlphaGo training method), which directly mischaracterizes a well-documented technical fact. **Issue 4** (creativity study methodology) and **Issue 2** (Anthropic/DoD framing) are important imprecisions that could mislead students. **Issues 9 and 10** (unverifiable citations) should be flagged for the instructor to confirm or replace.
