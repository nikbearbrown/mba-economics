# Revision Notes

Track what you've added, removed, or rewritten here.

---

## 2026-05-10 — Chapter 1 pilot

**Book state:** B (numbered subfolders with OpenStax `.md` source, 34 chapters total).

**Pilot scope:** Chapter 1 only. Voice calibration before scaling to ch 2–34.

**Files generated:**
- `chapters/01-welcome-to-economics.md` (6,213 words)
- `pantry/01-welcome-to-economics.md` (1,406 words)
- `images/01-welcome-to-economics.md` (1,109 words — five figure briefs incl. hero)
- `bookmaps/01-welcome-to-economics.md` (1,427 words — full source map, what-was-promoted/cut log, deferral list)

**Voice flag:** `voice-unanchored` — book has no `book.md`, no `outline.md`, no `style/` folder. Chapter 1 was written in the Attenborough × Feynman v1.1 register specified in the workflow brief. This chapter is the calibration point. If voice is adjusted after Bear's review, ch 1 will be the revision target before ch 2 begins.

**Cleanup:** Source subfolder `chapters/01-welcome-to-economics/` retained per B6 (cleanup gated on Bear's pilot review).

**Awaiting:** Bear's review of voice, structure, and pedagogical choices. Decisions still owed: confirm voice → write `book.md` and `style/` → batch ch 2–34 in subsequent sessions (3–5 per run) → then Chapter 00 / Project options / Enrichment per the "with LLMs" brief.

---

## 2026-05-10 — Full 34-chapter run

**Voice anchor.** Bear's rewrite of Chapter 1 (preserved in `style/canonical-chapter-1.md`) was used as the voice anchor for all 33 subsequent chapters. Voice features: tagline subtitle, scene-first cold open, learning objectives + prerequisites paragraph, three concept sections with named subheaders, woven worked examples, synthesis section, five LLM Exercises, What comes next / What would change my mind / Still puzzling, italicized byline.

**Total prose written.** ~91,000 words across 34 chapter files (averaging ~2,700 words/chapter — within the targeted 2,000-4,500 range).

**Files generated.**
- `chapters/[NN-slug].md` × 34 — flat chapter files.
- `pantry/[NN-slug].md` × 34 — reusable ingredients.
- `images/[NN-slug].md` × 34 — figure briefs.
- `bookmaps/[NN-slug].md` × 34 — source maps.
- `book.md` — book metadata and voice spec.
- `style/canonical-chapter-1.md` — voice anchor.
- `_toc.md` — rewritten table of contents pointing to flat files.

Total artifact files generated this session: **138**.

**Book state.** Originally State B (numbered subfolders with OpenStax source). Now: flat chapter files + retained source subfolders (cleanup gated on Bear's review per CLAUDE.md §B6).

**LLM enrichment approach.** Bear's rewrite of Chapter 1 merged the workflow brief's Step 4 enrichment (LLM Exercises) directly into the chapter as the end-of-chapter exercises section, replacing traditional graduated exercises. This approach was followed for all 34 chapters. Each chapter has 5 LLM Exercises designed to use Claude/ChatGPT/Gemini as a thinking partner — not a calculator. No inline Dig Deeper prompts (departing from the "with LLMs" workflow brief, but consistent with Bear's voice anchor).

**Cleanup status.** Source subfolders retained. After Bear's review of the full set, the cleanup decision can be made for the bundle.

**Awaiting.** Bear's review. Likely revision targets: voice consistency across the run; ensuring the late chapters maintain the freshness of the early ones (the macro chapters are tighter on word count than the micro chapters, intentionally — but Bear may want them expanded); LLM exercise quality; figure briefs.

**Note on truthfulness.** Per workshop CLAUDE.md §7, no fabricated quotes or precise statistics were invented. Numerical examples are either from OpenStax source modules, well-documented public-domain knowledge (Volcker disinflation rates, COVID-era unemployment, U.S. budget composition), or labeled as hypothetical/illustrative. Where a specific number was needed and uncertain, the chapter uses approximate phrasing ("about 100 percent of GDP," "roughly $7 trillion," etc.) rather than a precise fabricated figure. The chapters are rough drafts and Bear should fact-check specific numerical claims before publication.

## 2026-05-12 — Running Project added (additive): "Policy Brief"

Generated 34 end-of-chapter LLM Exercise blocks via the Running Project Exercise Generator. Project selected: **Policy Brief** — student picks one contestable policy in Chapter 1 (carbon tax / minimum wage / antitrust / UBI / rent control / single-payer / tariffs / student loan forgiveness / sugar tax) and applies each chapter's tools to that policy across the semester. Final deliverable: 6,000–10,000 word policy brief with sharpened verdict, "what would change my mind" section, and "still puzzling" close.

**Critical:** This was applied ADDITIVELY. The existing per-chapter `## LLM Exercises` (plural) sets — five thinking-partner exercises per chapter that train students to use LLMs critically — are PRESERVED. The new Policy Brief block uses the singular form `## LLM Exercise — Chapter N` to disambiguate. Each chapter now has both: the standalone thinking-partner exercises (existing) AND the running-project block (new).

The architecture: Ch 1 sets the policy and the brief foundation. Chs 2–18 work through the micro lens (PPF, demand-supply, elasticity, consumer/producer behavior, competition, externalities, info, financial, political economy). Chs 19–34 work through the macro lens (GDP, growth, unemployment, inflation, trade/capital, AD/AS, Keynes, neoclassical, money/banking, monetary policy, exchange rates, fiscal policy, debt, comparative policy, trade, globalization). Ch 34 compiles the brief.

Methodological commitments baked in across all 34: name what's known and unknown explicitly; honor the "still puzzling" discipline; don't paper over disagreement between Keynesian (Ch 25) and neoclassical (Ch 26) framings — run both as a check on the brief's conclusions; require honest naming of uncertainty in elasticity estimates and cross-country comparisons; require the student to update their draft verdict (Ch 1) against the analysis (Ch 34).

The project deliberately runs each policy through multiple lenses that often disagree. The brief earns its keep when the student names where the lenses converge (robust conclusion) and where they diverge (which assumption is doing the work).

Tool recommendations: Claude Project as the home for the brief; Claude Code for several quantitative chapters (Ch 3 D&S diagram, Ch 8 deadweight loss, Ch 15 Lorenz curve, Ch 22 inflation pass-through, Ch 24 AD/AS, Ch 31 debt trajectory); Cowork for Ch 34 final compilation across 34 sections.

Each block appended to the bottom of its chapter file, preserving the existing 5-exercise sets above. Total addition: ~22,000 words of new content across 34 chapters.

**Known follow-up for review:** by Ch 18 the student's brief is already 5,000+ words; by Ch 34 it's 8,000–12,000+. Some students will need a mid-semester editorial pass. If the workshop wants, an inserted "Chapter 19 transition: brief consolidation" exercise could go before the macro chapters begin — currently absent.
