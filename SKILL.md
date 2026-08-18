---
name: create-research-podcast
description: Turn papers, articles, reports, transcripts, notes, or other source material into an evidence-grounded two-host podcast package. Use when Codex needs to analyze source material, build a claim map, design an accessible episode arc, write natural educational dialogue, revise a podcast script, or audit a research podcast for factual grounding and listening quality.
---

# Create Research Podcast

Create a production-ready, two-host podcast script from user-supplied source material. Keep the workflow provider-neutral and stop at the editorial handoff unless the user explicitly requests additional production work.

## Choose the task

- For a new episode, complete the full workflow below.
- For a script revision, preserve approved material, rebuild the evidence map if needed, and run the same quality gates.
- For an audit, read `references/quality-rubric.md`, compare the script with its sources, and report specific fixes before rewriting.
- For a short preview, keep the same evidence discipline but narrow the episode to one central question and one or two learning loops.

## 1. Confirm the brief

Identify the source material, audience, approximate runtime, language, host format, and requested deliverables. Infer sensible defaults when they do not materially change the result:

- general curious audience
- two capable adult hosts
- accessible language without flattening the research
- a complete script plus evidence map, episode brief, and QA report

Do not invent access to a source. If essential source content is unavailable, request it or clearly limit the episode to the material that is available.

## 2. Build the evidence map

Read the complete source before drafting. Copy `assets/evidence-map-template.json` when creating files.

For every material claim, record:

- the concise claim
- the exact support location
- the support level: `direct`, `synthesis`, or `uncertain`
- any qualification the spoken version must retain

Separate source findings from host interpretation. Never turn an implication, limitation, opinion, or open question into an established result. Exclude interesting claims that cannot be supported.

## 3. Design one listening journey

Copy `assets/episode-brief-template.md` when creating files. Define:

- one central listener question
- the promise made near the opening
- three to six concept movements
- one concrete worked example or scenario
- the practical takeaway
- the final idea or question that should remain with the listener

Make each movement answer the previous movement and create the need for the next. Avoid a sequence of unrelated paper sections.

## 4. Assign host functions

Give the hosts complementary perspectives rather than fixed intelligence levels. Let expertise rotate by topic.

At each concept cluster, assign:

- one host to model the reasoning
- one host to surface a plausible listener question, test the mental model, or challenge an assumption

Keep both hosts intellectually credible. Distinguish them through priorities, conversational behavior, and reasoning style rather than stereotypes. Do not fabricate personal lives, credentials, fieldwork, or off-mic experiences.

Read `references/dialogue-patterns.md` before drafting the full dialogue.

## 5. Draft for listening

Use speaker labels consistently. Write speech, not an essay split between two names.

- Open with a welcome or hook, identify the hosts if appropriate, and state the episode promise early.
- Explain one difficult idea at a time.
- Use questions that expose real confusion or test an inference.
- Let a host reason through at least one example instead of stating only conclusions.
- Use short reactions only when they change the relationship, rhythm, or understanding.
- Allow disagreement when the source or implications warrant it. Neither host must always win, apologize, or manufacture consensus.
- Restate essential qualifications naturally rather than hiding them in disclaimers.
- End after delivering the promised insight; do not add a generic summary that drains the ending.

Estimate runtime using the spoken word count and an explicit assumed pace. Label the result as an estimate until real audio is measured.

## 6. Run two editorial passes

First run a source pass:

1. Match every factual claim to the evidence map.
2. Flag distortions, missing qualifications, unsupported examples, and invented specificity.
3. Revise until no material unsupported claim remains.

Then run a listening pass using `references/quality-rubric.md`:

1. Test the central question and causal flow.
2. Remove alternating mini-lectures, empty questions, repetitive agreement, and predictable one-line debates.
3. Check accessibility, host distinction, pacing, emotional credibility, and ending payoff.
4. Read difficult passages aloud when possible and simplify tongue-twisting sentences.

Do not claim the script passed audio fidelity, voice stability, loudness, or silence checks unless finished audio was actually inspected.

## 7. Deliver the package

Unless the user requests another format, provide:

1. `evidence-map.json` — supported claims and qualifications
2. `episode-brief.md` — audience, promise, central question, movements, and host functions
3. `script.md` — exact spoken dialogue with optional performance notes kept separate
4. `qa-report.md` — source and listening findings, remaining uncertainties, word count, and estimated runtime

Keep citations in the evidence map and episode notes. Avoid reading citation syntax aloud unless the user explicitly wants spoken references.

## Boundaries

- Remain neutral about language models, speech providers, voices, and hosting platforms.
- Do not require API keys or external services.
- Do not copy branding, fictional hosts, music, or private continuity from another show.
- Treat optional audio production as a separate user-directed stage.
- Respect source licenses and quotation limits. Prefer original explanation over extended quotation.
