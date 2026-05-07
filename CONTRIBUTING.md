# Contributing to Awesome Embodied Brain Models

Thanks for contributing.

## How to Add a Paper

1. Add the paper to the **single best primary section** in `README.md` under the current four-way taxonomy: **Simulators**, **Benchmarks**, **Foundation Brain Models**, or **Brain Agents**. Prefer the section that best reflects the paper's main contribution to embodied brain models and agents.
2. Keep the table format consistent:

```text
| YYYY-MM-DD | [Paper Title](link) | `profile-tag(s)` or - | `method-tag(s)` or - | Venue or - | resources |
```

3. Fill the two tag columns explicitly: use **Profile** for task / setting / capability cues, and **Method** for technical route cues. Use `-` for empty columns.
4. Add a BibTeX entry under `bib/entries/`.
5. Append the same entry to `bib/awesome_embodied_agents.bib`.
6. Submit a pull request with a short note about the primary section choice and any non-obvious tags.

## Primary Section Guide

- **Simulators**: Simulation environments, platforms, and data ecosystems for embodied agent research. Includes general-purpose simulators (e.g., Habitat, Isaac Sim), task-specific environments, data platforms, and training stacks that enable brain model research.
- **Benchmarks**: Datasets and evaluation protocols that measure embodied planning, reasoning, or brain model capabilities. Includes navigation benchmarks, manipulation benchmarks, planning/reasoning benchmarks, multi-agent benchmarks, and stress tests.
- **Foundation Brain Models**: Foundation models that serve as the "brain" of embodied agents — VLMs, VLAs, world models, diffusion policies, and other general-purpose models for embodied AI. The primary contribution should be a new model architecture or training method, not a specific agent application.
- **Brain Agents**: Agent systems built on foundation models for specific tasks — navigation agents, manipulation agents, exploration agents, multi-agent systems, and collaborative agents. The primary contribution should be the agent's task performance or system design.

If a paper could fit multiple sections, prefer the section that best reflects its **main contribution** to embodied brain models, then capture the rest through tags.

## Tag Guide

Prefer compact tags from a small, reusable vocabulary. Put task / setting / capability cues into **Profile**, and keep technical route cues in **Method**.

- **Profile tags**: `generalist`, `nav`, `manipulation`, `eqa`, `active-search`, `multi-agent`, `benchmark`, `dataset`, `perception`, `localization`, `reasoning`, `memory`, `world-model`, `planning`, `control`, `communication`, `grounding`, `spatio-temporal`, `long-horizon`, `grasping`, `household`, `human-robot`, `humanoid`, `spatial-memory`, `temporal-reasoning`, `counterfactual`, `4d-perception`, `robotics`, `policy`
- **Method tags**: `vla`, `vlm`, `diffusion`, `hierarchical`, `rl`, `scene-graph`, `3d-memory`, `audio-visual`, `foundation-model`, `agent-system`, `platform`, `video-prediction`, `latent-dynamics`, `nerf-gs`, `contrastive-decoding`, `fine-tuning`, `cot`, `diffusion-policy`, `flow-matching`, `simulator`, `policy`

If a paper spans multiple areas, choose the primary section by its **main contribution to embodied brain models** and encode the cross-cutting aspects in `Profile` / `Method` instead of duplicating the entry.

## Curation Rules

- Prioritize papers on **brain models for embodied agents**: foundation models (VLMs, VLAs, world models, diffusion policies) and agent systems built on them for spatio-temporal perception and task planning.
- Agentic systems with explicit spatial and/or temporal loops using foundation models should be preferred.
- World models with explicit spatio-temporal structure for embodied prediction and planning are in scope.
- Benchmarks that measure brain model capabilities (planning, reasoning, spatio-temporal understanding) are in scope.
- Supporting platform and simulator papers are in scope when they enable brain model research.
- **Foundation Brain Models vs Brain Agents boundary**: If the paper introduces a new model architecture → Foundation Brain Models. If it applies a model to a specific task → Brain Agents. When ambiguous, prefer Brain Agents.
- Pure perception-only or narrow EQA papers without planning components are usually out of scope.
- The current repository scope starts at `2023-04-01`. Earlier papers can be added later in a dedicated historical section.
- Use the official paper page whenever possible.
- If a paper is only on arXiv, write `-` in the venue column.
- Keep tags short, reusable, and task-oriented.

## Questions

Open an issue or submit a PR comment if a paper's primary section is ambiguous or if a new reusable tag seems necessary.
