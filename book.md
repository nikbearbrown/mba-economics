# Principles of Economics — with LLMs

**Audience.** First-year college students taking a one-year principles-of-economics course. Mixed background — some have had a prior microeconomics course in high school; many have not. Comfortable with arithmetic, occasionally apprehensive about graphs, mostly new to economic thinking. Native to LLMs the way the prior generation was native to web search.

**Scope.** A full year of principles of economics — micro and macro — covering the standard OpenStax bundle: scarcity and choice through demand-and-supply through firm structure and market failures (micro), then macroeconomic measurement, growth, business cycles, money and banking, fiscal and monetary policy, exchange rates, trade, and globalization (macro). Source material is OpenStax *Principles of Economics 2e* (and adjacent modules), rewritten in the voice below.

**Voice.** Set by the canonical Chapter 1 (`style/canonical-chapter-1.md`) — Bear's own rewrite. Key features:

- **Opens in scene, mid-action.** Cold open with one specific person, place, or moment. No abstraction in the first paragraph.
- **Tagline subtitle**, italicized, immediately under the chapter title.
- **Short declarative sentences at pivots.** Sentence fragments at moments of weight. Long sentences for connection.
- **First person sparingly.** "I want to be honest with you about something." "The reading I want to leave you with."
- **Direct second person.** "You" the reader is in the room.
- **Named-section headers** that read as prose, not labels. ("The fact that starts everything," not "Section 2: Scarcity.")
- **Three concept sections per chapter** with sub-headers like "Mechanism one — comparative advantage." Not enumerated as 2/3/4.
- **Worked examples woven into prose**, not boxed.
- **Common misconceptions woven into prose**, not subsectioned.
- **No tables, no figures embedded** in the chapter file itself; figures live in `images/`.
- **Trade-offs named explicitly**, often as their own brief subsection at the end of a concept.
- **Synthesis section** that brings the three concepts back through one anchoring scene or analogy.
- **Five LLM Exercises** at the end, each using an LLM as a thinking partner — not a calculator. Replaces traditional textbook exercises entirely.
- **"What comes next"** — single paragraph forward-look, named chapters.
- **"What would change my mind"** — one short paragraph naming the evidence that would revise the chapter's central claim.
- **"Still puzzling"** — one short paragraph naming what the author does not yet fully understand.
- **Byline:** *"Byline: Nik Bear Brown."* italicized at the end.

**Length target.** ~3,000–4,500 words per chapter. Tighter is better. The chapter is a working tool for a one-week reading; not a survey of everything that could be said.

**Hard rules.** Per workshop CLAUDE.md §7 — no fabricated sources or quotes; primary sources where the chapter makes a contestable empirical claim; calibrated uncertainty; show the work; method applies to method (named tools earn their place by doing work).

**Source.** OpenStax *Principles of Economics 2e* modules, retained in `chapters/[NN-slug]/` subfolders during the State-B rewrite. Bookmaps under `bookmaps/` track which source module fed which section.

**Companions.**
- `pantry/[chapter-slug].md` — reusable ingredients (scenes, examples, vocabulary, named tools, trade-offs, sources).
- `images/[chapter-slug].md` — figure briefs (hero image + in-chapter figures, with style sheet).
- `bookmaps/[chapter-slug].md` — source map (which OpenStax module fed which section, what was promoted/demoted/cut, what's deferred to other chapters).

**LLMs in the curriculum.** This book is part of the "with LLMs" series. The end-of-chapter LLM Exercises use Claude (claude.ai) as the default tool, with prompts that work on other LLMs with minimal adjustment. Exercises are framed as ways to *test understanding by stress-testing the LLM*, not as "ask the bot to do it for you."
