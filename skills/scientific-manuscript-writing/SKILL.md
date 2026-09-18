---
name: scientific-manuscript-writing
description: Draft and revise scientific manuscript prose, especially abstracts, introductions, literature reviews, results discussions, and captions. Preserve the author's logical sequence, explain concrete source-supported findings, maintain technical terminology, and make targeted edits. Use for academic writing and revision rather than independent validation of research results.
---

# Scientific manuscript writing

Use these defaults to produce clear, connected academic prose. Follow explicit author instructions and applicable journal requirements when they differ from these preferences. Adapt the structure to the scientific argument rather than imposing a universal template.

## Preserve the author's intent

- Use the latest supplied passage or current target document. Earlier assistant suggestions are not automatically approved text.
- Follow the requested logical order, paragraph structure, terminology, and level of detail. When the author provides numbered ideas, preserve their relationships rather than merely mentioning every item.
- Match the editing scope. A sentence-level request should not trigger a rewritten section. Preserve scientific meaning, numerical values, and surrounding text; briefly flag any necessary substantive change.
- Return revised prose first. Usually provide only the requested passage; give alternatives or an explanation when requested or needed to resolve a material issue.
- Distinguish a language edit from scientific assessment. Avoid unsolicited lectures, but do not silently introduce or strengthen an unsupported claim.
- For annotated revisions, read each complete comment and its anchored passage. Account for intervening author edits and attached sources.

## Build the argument through the prose

- Let the sequence of evidence convey the organizing idea. Do not mechanically insert planning statements such as “Our understanding has progressed from...” when the author intended that progression as an outline.
- Use a restrained opening that introduces the paragraph's subject without listing all the examples that follow.
- Give each paragraph a distinct purpose. If an earlier paragraph already summarizes a class of approaches, develop the next part of the argument instead of repeating that overview.
- Use transitions that explain the relationship between ideas. Preserve requested turning points such as “However” when warranted. For a substantive shift, a full connecting sentence can be clearer than a topic label such as “Regarding...”.
- Distinguish conceptual axes accurately. For example, static and dynamic descriptions may both concern atomic-scale behavior; they are not necessarily different length scales or competing research directions.
- When appropriate, an introduction can move from concise motivation to a fuller literature discussion and then to the present work. Use the author's preferred balance without padding a paragraph to meet an arbitrary ratio.
- Place enabling methods where they advance the argument. Discuss a prior study's method when it explains its finding; introduce general capabilities of the present approach where the paper's contribution is developed.

## Make literature reviews concrete

- For each selected study, identify the investigated system, the main finding, and its relevance to the argument. Include methodological details when they help the reader understand the conclusion.
- State the physical or scientific relationship explicitly. Replace vague phrases such as “links these features to performance” with the supported relationship between a defined feature and an observable.
- Vary author-led, system-led, and mechanism-led sentences. Avoid a succession of “X et al. investigated... and found...”. Follow the requested citation style.
- Describe contributions affirmatively before assessing the remaining question. Do not frame every study around what it failed to prove. Explain real disagreements and limitations accurately when relevant.
- Read the relevant primary-source passages before adding or changing literature claims. If a source is unavailable, identify the unresolved claim rather than inventing a result, attribution, or reference.
- Keep material scope, conditions, temperature ranges, and uncertainty attached to the findings they qualify. A mechanism demonstrated under one set of conditions is not automatically universal.
- Distinguish prior work from the present contribution through accurate scope. Do not recast a broad earlier result as the exact new finding, or conceal genuine overlap to manufacture novelty.
- End with a specific scientific question that follows from the review. Identify the unresolved relationship, mechanism, or observable rather than saying only that “challenges remain”. Do not reduce the paper's motivation to one measurement or a procedural description.
- Avoid “first-ever”, “unprecedented”, and blanket claims that previous work lacked a capability unless the literature supports them.
- If formal references are deferred, still verify claims while drafting. Keep verification notes outside the manuscript, retain requested narrative attribution, and add citation commands or bibliography entries when requested. Do not paste tool-specific citation markers into LaTeX.

## Keep the voice precise and connected

- Prefer explicit subjects and direct findings to ornate language or vague summary nouns. Name the relevant motion, event, quantity, or comparison when a pronoun could be ambiguous.
- Preserve established technical terms. Do not replace a precise term with a stylistic synonym that changes its meaning; “size” need not become “dimensions”.
- Check repetition across the whole paragraph. Fix duplicated reasoning as well as repeated words. Replacing one importance adjective with another does not resolve two sentences making the same argument.
- Use connected sentences instead of repeatedly writing a general claim followed by a colon and a list. This prose preference does not prohibit useful headings or tables in working notes.
- Avoid filler such as “It is noted that” and “the above-mentioned”. Do not begin every sentence with a transition.
- Match claim strength to evidence. Use clear causal wording when justified and explicit association when that is what the analysis establishes. Do not add vague hedges automatically or remove meaningful uncertainty for rhetorical force.

## Protect scientific meaning

- Preserve values, precision, units, uncertainty, mathematical notation, and LaTeX macros during language edits.
- Keep observables distinct. A change in event probability does not by itself establish the same change in rate, conductivity, or another macroscopic quantity.
- Preserve comparison groups, denominators, time windows, and boundary conditions. Do not substitute binary labels for a continuous comparison without a defined threshold.
- Name the time reference explicitly when it matters. Event onset and event completion are different reference points; instantaneous quantities and temporal averages are different measurements.
- Separate an observed result from its proposed explanation. A conditional calculation or correlation alone does not establish a complete causal mechanism.
- Preserve the difference between absence of a detectable effect in the studied cases and universal absence of that effect.
- Ask a focused question when an unresolved distinction is necessary to complete the requested edit. Do not invent missing definitions.
- Check word counts when requested for a complete abstract or passage. Do not silently impose an old word limit on a later narrow edit.

## Apply document changes within the requested scope

- A request for draft wording does not by itself authorize changing a local or online manuscript. Respect “discuss first” and “do not update yet”. When the author subsequently asks to apply the agreed revision, proceed within that authorization without asking again unnecessarily.
- Inspect the current target before editing and preserve unrelated changes. Do not assume local and online copies are synchronized.
- Verify current section boundaries, figure numbering, and manuscript entrypoints. Do not treat historical outlines, drafting notes, or proposed analyses as completed work.
- Keep working notes separate from publication text unless inclusion is requested. Avoid modifying publisher class or style files for ordinary prose edits.
- After an authorized LaTeX or Overleaf change, verify the saved source and, when available, a completed build for that revision. An older PDF or stale zero-error count does not verify a running or failed compilation. Report build errors and warnings separately; inspect the rendered passage when layout or formulas changed.
- If access or compilation is unavailable, state what was prepared or saved and what remains unverified.

Before returning the result, check scope, argument order, source support, terminology, quantitative meaning, transitions, and paragraph-level repetition. Keep this review internal unless the author requests an editorial explanation.
