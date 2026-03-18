# Structures to Avoid (Physics Edition)

## Passive Voice — Allowed in Methods, Flagged in Results

**Passive is CORRECT and conventional in experimental procedures:**
- "Samples were cleaved in ultra-high vacuum (UHV)."
- "Spectra were recorded at T = 4.2 K."
- "Calculations were performed within DFT using the PBE functional."
- "The tip was stabilized at V = 100 mV, I = 500 pA."

Do not change these. Experimental procedures use passive by convention.

**Passive is WRONG when results hide the actor:**

| Wrong | Right |
|-------|-------|
| "A gap was observed to open at the Fermi energy." | "We observe a gap opening at the Fermi energy." |
| "The asymmetry was found to be 20-fold." | "We find a 20-fold asymmetry." |
| "The feature is attributed to..." | "We attribute this feature to..." |
| "It was concluded that..." | "We conclude that..." |

**Rule:** If "we" can be the natural subject, use it. If the equipment or sample is the only possible subject, passive is fine.

## False Agency — Revised for Physics

Instruments, data, and figures can "show," "reveal," and "indicate" in physics writing. This is standard.

**Legitimate physics agency — do not flag:**
- "The spectrum shows a peak at 150 meV." ✓
- "Fig. 1 reveals the atomic structure of the grain boundary." ✓
- "The data indicate a phase transition at B = 4 T." ✓
- "STM measurements reveal spatial modulations of the LDOS." ✓
- "The tunneling conductance shows a suppression near zero bias." ✓

**Flag only when a human actor is hidden where one should be named:**
- "The results suggest that the gap opens." → "We find that the gap opens."
- "It was concluded from this that..." → "We conclude that..."

## Significance Inflation Structures

The most common AI tell in physics writing. Announces importance without demonstrating it.

| Pattern | Problem |
|---------|---------|
| "This is a significant advance in the field." | Announcement without evidence |
| "These results represent a major breakthrough." | Announcement without evidence |
| "This work opens new possibilities for..." | Vague; state the specific possibility with numbers |
| "Our findings pave the way for future research on..." | Generic; cut or name the specific research |
| "This demonstrates the power of our approach." | Let the result speak |
| "This illustrates the importance of..." | State what the importance is |
| "...establishing X as a promising platform for..." | Only if you then specify what X enables |

**Instead:** End with the result. "We demonstrate a 20-fold reflection asymmetry arising from layer-polarization mismatch at stacking domain boundaries" closes stronger than appending a significance announcement.

## Missing Quantification

Vague claims are structurally broken in physics text:

| Pattern | Fix |
|---------|-----|
| "The gap is large." | Add the measured value and units. |
| "The asymmetry is significant." | State the ratio or magnitude. |
| "At low temperatures..." | Specify the temperature. |
| "Under high magnetic fields..." | Specify the field. |
| "The feature shifts considerably." | State the shift in meV, nm, or relevant units. |
| "The signal is enhanced." | State the enhancement factor. |
| "Good agreement with theory." | State the quantitative comparison. |

Every claim about magnitude needs a number. Every number needs units. Every measurement needs its experimental conditions stated or referenced.

## Abstract Structure Violations

The abstract must follow: **problem → knowledge gap → approach → key result**. Flag these violations:

| Pattern | Problem |
|---------|---------|
| Opens with "In this work, we present..." | Wastes the first sentence on announcement; start with the problem or the result |
| No knowledge gap stated | Reader does not know why this work was necessary |
| No quantitative result in abstract | Abstract reads as press release, not summary |
| Ends with "Further work is needed..." | Weak close; end with the result or its specific implication |
| "Our results have important implications for..." | Vague; state the implication |

## Binary Contrasts

These create false drama. State the point directly.

| Pattern | Problem |
|---------|---------|
| "Not because X. Because Y." | Telegraphed reversal |
| "The answer isn't X. It's Y." | Predictable pivot |
| "not X, it's Y" / "isn't X, it's Y" | Mechanical contrast |
| "not just X but also Y" | Additive hedge |

**Instead:** State Y directly. Drop the negation.

Exception: "In contrast to X, we find Y" is legitimate comparative language in physics when two systems or approaches are directly compared with quantitative backing.

## Negative Listing

Listing what something is *not* before revealing what it *is*.

| Pattern | Problem |
|---------|---------|
| "Not a X... Not a Y... A Z." | Dramatic buildup through negation |
| "It wasn't X. It wasn't Y. It was Z." | Same structure, past tense |

**Instead:** State Z directly.

## Dramatic Fragmentation

Still wrong in physics writing.

| Pattern | Problem |
|---------|---------|
| "[Noun]. That's it." | Performative simplicity |
| Short staccato sentences stacked for emphasis | Drama without data |
| Paragraph-ending one-liner for punch | Vary endings |

**Instead:** Complete sentences. Physics content carries the weight.

## Rhetorical Setups

| Pattern | Problem |
|---------|---------|
| "What if [reframe]?" | Socratic posturing; state the finding |
| "Think about it:" | Condescending; cut |
| "The question is not X. It is Y." | Reframe cliché |
| "Here's what I mean:" | Cut; just say what you mean |

## Rhythm Patterns

| Pattern | Fix |
|---------|-----|
| Three-item lists where two suffice | Cut one — unless all three are measured quantities that must all be cited |
| Em-dashes | Remove. Use commas or parentheses. |
| Every result sentence same length | Vary structure |
| Paragraph starts with "So," | Cut "So," and start with content |
| "It is well known that..." | Cut opener; state the fact or cite it |
| "Obviously..." / "Clearly..." as openers | Cut adverb; state the fact |
