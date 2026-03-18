# Stop Slop — Academic Physics Edition

A skill for removing AI tells from condensed matter physics prose.

<img width="3840" height="2160" alt="G-Yg4RVbIAAhVxW" src="https://github.com/user-attachments/assets/902afc15-1f40-4a9d-af24-8cd67afb8ebf" />

## What this is

AI writing has patterns. In general prose, these are predictable phrases, structures, and rhythms. In academic physics writing, the problem is different: AI inflates significance, omits quantification, and breaks the problem-solution narrative structure that physics papers require. This skill teaches Claude to catch the right patterns — without destroying the legitimate conventions of scientific writing.

## What makes physics different

The original stop-slop rules target blog and essay writing. Applied to physics papers, they break things. "We observe," "as shown in Fig. X," and passive voice in methods are not AI slop — they are the standard vocabulary of the field. This version of the skill knows the difference.

**Protected:** observation verbs, figure references, evidence-linking phrases, passive voice in experimental procedures, calibrated hedging tied to real uncertainty.

**Targeted:** significance inflation, missing quantification, vague gesturing, announcement sentences, over-hedging, rhetorical scaffolding.

## Skill Structure

```
stop-slop/
├── SKILL.md              # Core instructions
├── references/
│   ├── phrases.md        # Phrases to remove (with protected phrases listed first)
│   ├── structures.md     # Structural patterns to avoid
│   └── examples.md       # Before/after transformations in physics contexts
├── README.md
└── LICENSE
```

## Quick start

**Claude Code:** Add this folder as a skill. Invoke with `/stop-slop`.

**Claude Projects:** Upload `SKILL.md` and reference files to project knowledge.

**Custom instructions:** Copy core rules from `SKILL.md`.

**API calls:** Include `SKILL.md` in your system prompt. Reference files load on demand.

## What it catches

**Significance inflation** — "revolutionary," "unprecedented," "paves the way," "opens new avenues," "landmark study." Replace with the specific result that earns its own weight. See `references/phrases.md`.

**Missing quantification** — Claims without values, units, or experimental conditions. Every magnitude claim needs a number. See `references/structures.md`.

**Abstract structure violations** — Announcement openers, missing knowledge gap, no quantitative result, vague closing statements. The abstract must follow: problem → gap → approach → result. See `references/structures.md`.

**Throat-clearing** — "It is worth noting that," "It is important to note that," "In this work, we present." State the thing directly. See `references/phrases.md`.

**Hidden actors in results** — Passive voice where "we" should be the subject: "a gap was observed" → "we observe a gap." See `references/structures.md`.

**Over-hedging** — "it might possibly be the case that," "it is conceivable that." Calibrate hedging to actual uncertainty. See `references/phrases.md`.

## What it does NOT flag

- "We observe / demonstrate / find / show / report / measure" — these are the core verbs of empirical physics
- "As shown in Fig. X" — figure references are required for every key result
- "This is consistent with / in good agreement with" — standard evidence-linking language
- "Our results suggest / indicate" — appropriate hedging for observational claims
- Passive voice in methods sections — "samples were cleaved," "spectra were recorded" are correct and conventional
- Technical adverbs: "linearly," "exponentially," "monotonically" — required physics vocabulary

## Scoring

Rate 1–10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Specificity | Every claim backed by numbers and units? |
| Structure | Problem → gap → approach → result throughout? |
| Precision | Hedging calibrated to actual uncertainty? |
| Economy | Any sentence that could be cut without losing information? |
| Authenticity | Reads like physics, not a press release? |

Below 35/50: revise.

## Author

Original: [Hardik Pandya](https://hvpandya.com)

Academic physics adaptation: [P. Nemes-Incze](https://github.com/zrbyte)

## License

MIT. Use freely, share widely.
