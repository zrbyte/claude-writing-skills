---
name: stop-slop
description: Remove AI writing patterns from academic condensed matter physics prose. Use when drafting, editing, or reviewing papers, abstracts, and reports to eliminate AI tells while preserving legitimate academic conventions.
metadata:
  trigger: Writing or editing physics papers, abstracts, reports, grant text, referee letters
  author: Hardik Pandya (https://hvpandya.com), adapted for condensed matter physics by P. Nemes-Incze
---

# Stop Slop — Academic Physics Edition

Eliminate AI writing patterns from condensed matter physics prose without destroying legitimate academic conventions.

## Context

Physics writing follows conventions that look like "slop" to a general editor but are standard and necessary: passive voice in methods, observation verbs ("we observe," "we demonstrate"), hedged claims tied to evidence, dense figure references. Do not remove these. Target actual AI slop: vague significance inflation, missing quantification, broken narrative structure, rhetorical padding.

## Protected Phrases

Never flag or remove these from physics writing:

**Observation and demonstration verbs** (the core of empirical physics):
- "We observe..." / "We find..." / "We measure..."
- "We demonstrate..." / "We show that..." / "We reveal..."
- "We report..." / "We investigate..."
- "Our results indicate..." / "Our measurements show..."
- "Our results suggest..." (appropriate hedging for observational claims)

**Evidence-linking phrases:**
- "This is consistent with..."
- "In good agreement with..."
- "We can attribute this to..."
- "This observation agrees with..."
- "This resolves..."

**Figure and data references:**
- "As shown in Fig. X..."
- "As illustrated in Fig. X..."
- "In Fig. X, we present..."
- "The inset shows..."

**Legitimate hedging** (use only when genuine uncertainty exists):
- "This indicates..." / "This suggests..."
- "We cannot rule out..."
- "It is likely that..."

**Passive voice in methods** (required for experimental procedures):
- "Samples were cleaved in UHV..."
- "Spectra were recorded at T = 4 K..."
- "Calculations were performed using..."

## Core Rules

1. **Quantitative specificity is mandatory.** Every claim needs numbers: values, units, error estimates, temperature, field, sample parameters. "The gap is large" is slop. "The gap is 30 meV, measured at T = 4.2 K" is physics. See [references/phrases.md](references/phrases.md).

2. **No significance inflation.** Ban "revolutionary," "unprecedented," "paradigm shift," "paves the way," "sheds new light on," "landmark," "game-changing." Replace with the specific finding that earns its own weight. See [references/phrases.md](references/phrases.md).

3. **Strong observation verbs.** Lead results with what was measured: "We observe a 30 meV gap," not "Interestingly, a gap appears to be present." See [references/structures.md](references/structures.md).

4. **Every key claim needs a figure reference.** If a result is stated without "as shown in Fig. X," add it. Data not pointed to is data not trusted.

5. **Passive voice in methods, active in results.** "Samples were prepared by..." is correct. "The gap was observed to increase with field" hides who measured what — write "We find that the gap increases with field."

6. **Abstract structure: problem → gap → approach → result.** No filler sentences. Each sentence adds information. No announcement sentences ("In this work, we present..."). See [references/structures.md](references/structures.md).

7. **Cut significance announcements.** If the result is significant, the number makes it so. Remove sentences that announce importance without demonstrating it.

8. **Vary rhythm, but not at the cost of precision.** Two items beat three in a list — unless all three are necessary measurements. Do not fragment for drama. No em dashes.

## Quick Checks

Before delivering physics prose:

- Any vague claim without numbers? Add the measurement.
- Any significance inflation ("revolutionary," "unprecedented," "paves the way")? Cut or replace with the specific result.
- Any key result without a figure reference? Add it.
- Abstract starts with "In this work, we present..."? Cut the opener, start with the finding.
- "It is important to note that..."? Cut the announcement, state the thing directly.
- "Plays a crucial role in..."? Name the specific role with numbers.
- "Has important implications for..."? State the specific implication.
- Results section uses passive voice where an actor exists? Find the actor.
- Over-hedged claim ("it might possibly be the case that")? Replace with the appropriate observation verb and qualifier.
- Three-item list where two suffice? Cut one.
- Em-dash anywhere? Remove it.
- Methods use active voice unnecessarily? Standard procedures should be passive.

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

## Examples

See [references/examples.md](references/examples.md) for before/after transformations in physics writing contexts.

## License

MIT
