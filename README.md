# Create Research Podcast

A provider-neutral Codex skill for turning papers, articles, reports, transcripts, and notes into evidence-grounded two-host podcast scripts.

The skill focuses on the editorial work that transfers across production setups: source analysis, claim mapping, episode structure, educational dialogue, and quality assurance. It does not select models, voices, speech services, music, hosting, or publishing tools.

## What it creates

Given source material, the skill produces:

- `evidence-map.json` — supported claims, source locations, qualifications, interpretations, and exclusions
- `episode-brief.md` — audience, central question, episode promise, host functions, and movement structure
- `script.md` — production-ready two-host dialogue with optional performance notes
- `qa-report.md` — factual-grounding and listening-quality checks, uncertainties, word count, and estimated runtime

## Install

Clone the repository into your Codex skills directory:

```bash
git clone https://github.com/yellowpower/create-research-podcast.git ~/.codex/skills/create-research-podcast
```

Restart Codex if the skill is not discovered immediately. You can then invoke it explicitly as `$create-research-podcast`.

## Example prompts

```text
Use $create-research-podcast to turn this paper into a 12-minute podcast
for curious general listeners.
```

```text
Use $create-research-podcast to create a two-minute preview from this
report. Preserve the limitations and give each host a distinct perspective.
```

```text
Use $create-research-podcast to audit this script against the attached
source, then revise any unsupported or unnatural passages.
```

## How it works

1. Read the complete source and establish the audience and runtime.
2. Map every material claim to a precise support location.
3. Design one central listener question and a causal episode arc.
4. Give two capable hosts complementary perspectives and rotate expertise.
5. Write dialogue for listening rather than splitting an essay between speakers.
6. Run separate factual-grounding and listening-quality passes.
7. Deliver the four-file editorial package.

The operational workflow lives in [SKILL.md](SKILL.md). Detailed dialogue guidance and QA criteria are loaded only when needed from [`references/`](references/).

## Design principles

- Evidence before narrative
- One coherent listening journey rather than a section-by-section summary
- Questions that expose real confusion or test an inference
- Audible reasoning and concrete examples
- Honest disagreement without forced consensus
- Clear separation between source findings and host interpretation
- Explicit uncertainty and runtime estimates

## Scope

This is intentionally a script-first skill. It does not require external services or API keys and does not prescribe:

- language models or providers
- speech synthesis or voices
- music or sound design
- hosting or distribution
- show branding or recurring fictional hosts

Audio production can be added separately using the user's preferred tools.

## Repository layout

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   ├── episode-brief-template.md
│   └── evidence-map-template.json
└── references/
    ├── dialogue-patterns.md
    └── quality-rubric.md
```

## License

[MIT](LICENSE)
