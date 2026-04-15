# Contributing to Awesome Embodied Spatio-Temporal Agents

Thanks for contributing.

## How to Add a Paper

1. Add the paper to the **single best primary section** in `README.md`.
2. Keep the table format consistent:

```text
| YYYY-MM-DD | [Paper Title](link) | `profile-tag(s)` or - | `method-tag(s)` or - | Venue or - | resources |
```

3. Fill the two tag columns explicitly: use **Profile** for task / setting / capability cues, and **Method** for technical route cues. Use `-` for empty columns.
4. Add a BibTeX entry under `bib/entries/`.
5. Append the same entry to `bib/awesome_embodied_agents.bib`.
6. Submit a pull request with a short note about the primary section choice and any non-obvious tags.

## Primary Section Guide

- **Benchmarks & Evaluation**: datasets, diagnostic suites, stress tests, and evaluation resources.
- **Generalist & Foundation Agents**: generalist embodied models, VLA/VLM systems, reusable architectures, and cross-task agent frameworks.
- **Navigation Agents**: navigation, localization, audio-visual navigation, and navigation-centric planning/world modeling.
- **Manipulation Agents**: grasping, manipulation, household execution, and manipulation-centric planning/world modeling.
- **Embodied QA & Active Search**: embodied question answering, active search, exploration, and reasoning-led environment understanding.
- **Collaborative / Multi-Agent Embodied Systems**: collaborative embodied systems, communication, and multi-agent coordination.

## Tag Guide

Prefer compact tags from a small, reusable vocabulary. Put task / setting / capability cues into **Profile**, and keep technical route cues in **Method**.

- **Profile tags**: `generalist`, `nav`, `manipulation`, `eqa`, `active-search`, `multi-agent`, `benchmark`, `dataset`, `perception`, `localization`, `reasoning`, `memory`, `world-model`, `planning`, `control`, `communication`, `grounding`, `spatio-temporal`, `uav`, `long-horizon`, `grasping`, `household`, `human-robot`, `assembly`, `humanoid`
- **Method tags**: `vla`, `vlm`, `diffusion`, `hierarchical`, `rl`, `scene-graph`, `3d-memory`, `audio-visual`, `foundation-model`, `agent-system`, `platform`

If a paper spans multiple areas, choose the primary section by its **main task or resource role** and encode the cross-cutting aspects in `Profile` / `Method` instead of duplicating the entry.

## Curation Rules

- Prioritize papers on embodied spatio-temporal agents, especially work centered on generalist agents, navigation, manipulation, active reasoning, memory/world models, and decision-making.
- The current repository scope starts at `2023-04-01`. Earlier papers can be added later in a dedicated historical section.
- Use the official paper page whenever possible.
- If a paper is only on arXiv, write `-` in the venue column.
- Keep tags short, reusable, and task-oriented.

## Questions

Open an issue or submit a PR comment if a paper's primary section is ambiguous or if a new reusable tag seems necessary.
