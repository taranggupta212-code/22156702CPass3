# BUS5001 Q4 — NotebookLM Evaluation Log

**Student:** Tarang Gupta (22156702)
**Date:** June 2026
**Tool evaluated:** Google NotebookLM (free preview)

## Scenario
Postgraduate Master of Business Analytics student preparing a briefing on the alignment between La Trobe University's institutional sustainability plan and the Australian sustainability disclosure regime (AASB S1), tracing the lineage of disclosure expectations back through IFRS S2 to the TCFD framework.

## Sources uploaded to NotebookLM
1. La Trobe University Sustainability Plan (2015–2017)
2. AASB S1 — General Requirements for Disclosure of Sustainability-related Financial Information (September 2024)
3. IFRS S2 — Climate-related Disclosures (ISSB)
4. TCFD Recommendations Final Report (2017)

## Features tested

| # | Feature | Screenshot | Verdict |
|---|---|---|---|
| 1 | Source Q&A with citations | q4_01_qa_with_citations.png | Strong — produced a structured 3+3 alignment/gap analysis with page-range citations like [497–499] |
| 2 | Briefing document generation | q4_02_briefing_doc.png | Multi-section synthesis covering regulatory landscape, qualitative characteristics, four pillars, and implementation requirements |
| 3 | Flashcards (65 cards) | q4_03_flashcards.png | Concept-and-definition pairs grounded in sources, with "Explain" expansion option |
| 4 | Audio overview (custom focus) | q4_04_audio_overview.png | 1:33 conversational discussion with custom prompt directing focus to La Trobe vs AASB S1/IFRS S2 alignment |
| 5 | Mind map | q4_05_mindmap.png | Visual concept map of AASB S1 structure: Core Content (four pillars) and General Requirements branches |

## Critical evaluation tests

| Test | Screenshot | Finding |
|---|---|---|
| A — Citation integrity | q4_06_citation_check.png | NotebookLM returned the verbatim text of AASB S1 paragraphs 26 and 27 with clickable citation markers [1][2]. Citations pointed to the correct passages. |
| B — Hallucination resistance | q4_07_hallucination_test.png | **Strongest finding.** NotebookLM explicitly disclosed "the following information regarding the EU biodiversity reporting requirements is from my external knowledge and is not contained in your current sources" before answering an out-of-source question — exemplary responsible-AI behaviour. |
| C — Cross-source synthesis | q4_08_comparison_table.png | Produced a polished 4×4 comparison matrix of TCFD pillars across IFRS S2, AASB S1, and La Trobe's plan, with explicit "NOT ADDRESSED" markers on La Trobe's strategy/resilience gap. |

## Overall verdict
NotebookLM is genuinely useful for postgraduate-level academic work where the source corpus is bounded and the goal is rapid synthesis, navigation and revision rather than discovery. Its source-grounded design with transparent disclosure of out-of-source reasoning makes it materially safer than non-grounded chatbots for academic use. Best deployed as a first-draft, navigation and revision tool, with the student responsible for verifying critical citations, restoring normative position where appropriate, and using conventional research databases for external source discovery.

## Limitations observed
- Tendency toward balance/neutrality even where sources are normatively directive
- Audio outputs more vulnerable to paraphrasing drift than text outputs
- Structural over-reliance risk: feature richness (flashcards, mind maps, audio) makes it easier to bypass direct engagement with sources

## Recommended deployment
Use NotebookLM as a research assistant, not a research substitute. Pair it with traditional database search (Scopus, Web of Science, Google Scholar) for source discovery, and always verify critical citations against the original document.