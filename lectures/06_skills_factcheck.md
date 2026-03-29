# Fact-Check Report: Session 06 -- Skills: Building Reusable AI Tools

**File reviewed**: `website/lectures/06_skills_draft2.qmd`
**Date**: 2026-03-27
**Checker**: Content Expert Agent (Claude Opus 4.6)

---

## Summary

8 issues found: 3 errors, 4 imprecisions, 1 unverifiable claim.

---

### Issue 1: LeapSpace naming and attribution

- **Slide**: Repetitive Specialized Tasks (slide 2)
- **Claim**: "One student discovered **Leap Space**, a tool from ScienceDirect that pulls actual peer-reviewed papers using Scopus."
- **Problem**: Two issues. (a) The product name is **LeapSpace** (one word, camelCase), not "Leap Space" (two words). (b) LeapSpace is a product of **Elsevier**, not "from ScienceDirect." LeapSpace is the successor/rebrand of ScienceDirect AI -- it integrates content from both ScienceDirect and Scopus, but attributing it to ScienceDirect specifically is inaccurate. LeapSpace went live commercially on January 21, 2026, replacing ScienceDirect AI. Since this is a student's comment rather than the instructor's claim, the bar is lower, but the published text should still be accurate.
- **Suggested fix**: Change to: "One student discovered **LeapSpace**, an Elsevier tool that pulls actual peer-reviewed papers using Scopus and ScienceDirect content."
- **Source**: [Elsevier LeapSpace product page](https://www.elsevier.com/products/leapspace); [Elsevier press release: LeapSpace goes live](https://www.elsevier.com/about/press-releases/leapspace-goes-live-the-research-grade-ai-assisted-workspace)
- **Severity**: Error (product name and attribution)

---

### Issue 2: Paper title in super-referee discussion

- **Slide**: Super-Referee: The 4-Round Pipeline (slide 25)
- **Claim**: "grounded in an established paper on how to write good referee reports (*'Preparing a Referee Report'*)"
- **Problem**: The paper referenced appears to be Berk, Harvey & Hirshleifer (2017), but the title given is imprecise. There are actually **two** related works by these authors: (1) **"Preparing a Referee Report: Guidelines and Perspectives"** -- an SSRN working paper from 2016 (not a journal publication); (2) **"How to Write an Effective Referee Report and Improve the Scientific Review Process"** -- the published version in the *Journal of Economic Perspectives*, Vol. 31(1), pp. 231-244, Winter 2017. The draft uses the working paper title but does not cite authors or year. If the instructor is referencing the published JEP paper (which is the standard citation), the title in the text is wrong.
- **Suggested fix**: Change to: "grounded in Berk, Harvey & Hirshleifer's (2017) paper *'How to Write an Effective Referee Report and Improve the Scientific Review Process'* (Journal of Economic Perspectives)" -- or if the instructor genuinely means the SSRN working paper, clarify that it is unpublished.
- **Source**: [AEA: Berk, Harvey & Hirshleifer (2017)](https://www.aeaweb.org/articles?id=10.1257/jep.31.1.231); [SSRN working paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2547191)
- **Severity**: Imprecision (the title given matches the SSRN draft, not the published version; no authors or year cited)

---

### Issue 3: skills.mp URL and name

- **Slide**: Skills Are Just Folders: Share Them Like Files (slide 18)
- **Claim**: "**skills.mp** is a marketplace with thousands of community-built skills."
- **Problem**: The actual URL is **skillsmp.com** (no dot between "skills" and "mp"). The text renders "skills.mp" which looks like a domain with a .mp TLD (Marshall Islands), but the actual site is skillsmp.com. Also, the scale claim of "thousands" is a significant understatement. As of early 2026, SkillsMP indexes over 66,000+ agent skills (some sources cite 96,000+). The site is also explicitly described as "NOT affiliated with Anthropic" -- it is an independent community project.
- **Suggested fix**: Change "skills.mp" to "**skillsmp.com**" (or "**SkillsMP**" as the brand name). Update "thousands" to "tens of thousands" if precision matters, or keep as-is if the instructor's spoken phrasing was approximate.
- **Source**: [SkillsMP homepage](https://skillsmp.com/); [SmartScope review: 66,500+ skills](https://smartscope.blog/en/blog/skillsmp-marketplace-guide/)
- **Severity**: Error (URL/name is misleading as written)

---

### Issue 4: "over 20,000 skills in the research category alone"

- **Slide**: Mid-term Presentation Structure (slide 37)
- **Claim**: "the marketplace has over 20,000 skills in the research category alone"
- **Problem**: I could not verify this specific number. SkillsMP indexes 66,000-96,000+ skills total across all categories, but no source confirms 20,000+ specifically in a "Research" category. The number may have been approximate or from a live browse during the lecture. It is plausible but unverifiable as of this check.
- **Suggested fix**: Consider softening to "thousands of skills in the research category" unless the instructor can confirm the number from a recent browse. Alternatively, check the current count on skillsmp.com and update.
- **Source**: No specific source found for this category count.
- **Severity**: Unverifiable claim (not necessarily wrong, but cannot be confirmed)

---

### Issue 5: ".skill file format is actually just a zip archive"

- **Slide**: Installing a Skill on Claude.ai (slide 19)
- **Claim**: "the `.skill` file format is actually just a **zip archive**. If you want to inspect its contents, rename the extension from `.skill` to `.zip` and extract it."
- **Problem**: This is mostly correct but slightly imprecise in how it is presented. Anthropic's official documentation describes uploading skills as ZIP files. Some sources mention ".skill" files as an alternate extension accepted by the upload UI, but the canonical format described in official docs is simply a ZIP containing the skill folder. The draft presents .skill as the primary format that "is actually" a zip, when the reality is closer to: the upload format is a ZIP that may sometimes carry a .skill extension. This is a minor point of framing rather than factual error.
- **Suggested fix**: No change strictly necessary. If desired, clarify: "Skills can be downloaded as `.skill` files (which are ZIP archives) or as regular `.zip` files."
- **Source**: [Claude Help Center: Use Skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
- **Severity**: Imprecision (framing, not factual error)

---

### Issue 6: Microsoft "Copilot" as equivalent to Custom GPTs / Gems

- **Slide**: Every Platform Now Offers Reusable AI Tools (slide 4)
- **Claim**: "Microsoft **Copilot** offers the same concept."
- **Problem**: The direct equivalent to Custom GPTs and Gems in the Microsoft ecosystem is **Microsoft Copilot Studio** (formerly Power Virtual Agents), which allows building custom agents. Simply saying "Microsoft Copilot" is imprecise -- Copilot itself is the AI assistant; Copilot Studio is the builder for custom reusable agents. The slide text (from the slide image) may say "Copilot Agents" which would be more accurate, but the prose text just says "Microsoft Copilot."
- **Suggested fix**: Change to: "Microsoft offers **Copilot Agents** (built via Copilot Studio), which provide similar capabilities."
- **Source**: [Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-365-copilot/microsoft-copilot-studio)
- **Severity**: Imprecision (the distinction between Copilot and Copilot Studio matters for accuracy)

---

### Issue 7: Token-to-word ratio

- **Slide**: A/B Testing in Practice: Full vs. Light (slide 33)
- **Claim**: "a token is approximately 0.75 words"
- **Problem**: This is correct for English text. The standard approximation from OpenAI and widely used in the field is that 1 token is roughly 3/4 of a word (or equivalently, 100 tokens is roughly 75 words). However, the phrasing in the draft could be read as "one token equals 0.75 words," which is the correct direction. No issue here. **This claim checks out.**
- **Suggested fix**: None needed.
- **Source**: [OpenAI tokenizer documentation](https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them)
- **Severity**: No issue (verified correct)

---

### Issue 8: 1,024 character limit for description, and 200-line guideline for SKILL.md body

- **Slide**: The Golden Rule: Keep Your SKILL.md Lean (slide 13)
- **Claim**: "the front matter description should be under **1,024 characters**, with no XML. The main `SKILL.md` body should ideally stay **under 200 lines**."
- **Problem**: The 1,024 character limit for the description field is **correct** per Anthropic's official documentation. The "under 200 lines" guideline for the body is a reasonable practical recommendation but does not appear as an explicit hard limit in Anthropic's docs. Anthropic's guidance says the body should be "under 5,000 words" and some sources suggest "under 500 lines" as a soft guideline. The 200-line recommendation in the draft is more aggressive than official guidance -- this may be the instructor's personal best practice (which is fine pedagogically) but it is presented as if it were an official rule.
- **Suggested fix**: Consider clarifying: "Anthropic recommends keeping the body under 5,000 words. In practice, under 200 lines tends to work well -- put anything beyond that into reference files." This distinguishes the official limit from the instructor's recommendation.
- **Source**: [Anthropic skill authoring best practices](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices); [SKILL.md format spec](https://deepwiki.com/anthropics/skills/2.2-skill.md-format-specification)
- **Severity**: Imprecision (200 lines is instructor's recommendation, not an official Anthropic limit; the official limit is ~5,000 words)

---

## Claims Verified as Correct (No Issues)

- **Custom GPTs** (OpenAI) and **Gems** (Google) as reusable AI tool equivalents -- confirmed.
- **Claude skills work across Claude.ai, Claude Code, and the API** -- confirmed per Anthropic's official documentation. Skills use the open SKILL.md standard and function across all three surfaces.
- **Skills are plain text (Markdown) files** -- confirmed.
- **Kebab-case naming requirement** for skill folders -- confirmed.
- **"claude" and "anthropic" are reserved words** in skill names -- confirmed.
- **Consensus** as a research tool with journal quality (SJR quartile) filtering -- confirmed.
- **Progressive disclosure** concept for context window management in skills -- confirmed by Anthropic docs.
- **Ashraf and Galor "Out of Africa"** paper -- confirmed as a real paper (AER 2013). The RECAST replication example is the instructor's own demonstration and cannot be independently fact-checked, but the source paper is real.
- **Token ratio of ~0.75 words per token** -- confirmed (see Issue 7).

---

## Notes

1. The draft does **not** mention "GPT-0" anywhere. The task instructions asked about this, but the term does not appear in the text. No issue.

2. The claim that skills are "most tightly integrated with Claude Code" (slide 4) is a reasonable characterization. Claude Code reads `.claude/skills/` directories natively and manages skill loading automatically, which is a tighter integration than the Claude.ai web interface where skills must be uploaded manually. This is accurate.

3. The "Out of Africa" replication with causal forests (slide 28) is described as the instructor's own demonstration project (RECAST). Since this is a first-person account of his own work, it cannot be fact-checked against external sources. The underlying paper (Ashraf & Galor, AER 2013) is real and well-known.
