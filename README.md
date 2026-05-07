<div align="center">
    <h1>Awesome Embodied Brain Models</h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
</p>

A curated list of recent work on **brain models for embodied agents**: foundation models, agent systems, simulators, and benchmarks for spatio-temporal perception and task planning in embodied AI. The repository prioritizes work that serves as the "brain" of embodied agents — models that perceive, reason, plan, and act in physical environments.

<p align="center">
    <a href="bib/awesome_embodied_agents.bib"><img src="https://img.shields.io/badge/Download-All%20Bib-8B5E3C?logo=bookstack&logoColor=white" alt="Download all bib"></a>
</p>

## News

**[2026/05/07]** Cleanup: removed 5 purely VLA-focused papers (RT-2, Octo, OpenVLA, VLA Foundry, StarVLA). Added 7 brain VLM foundation models: RoboBrain / 2.0 / 2.5, EmbodiedGPT, LEO, IGOR, EnerVerse. Repository now has 97 papers.

**[2026/05/07]** Major restructure: renamed to **Awesome Embodied Brain Models**. New 4-section taxonomy: Simulators / Benchmarks / Models / Agents. Added ET-Plan-Bench, EmbodiedBench, PARTNR, PaLM-E, Diffusion Policy, VIMA, Cosmos, Gemini Robotics, and more. Removed papers not directly relevant to brain model/agent focus.

**[2026/04/15]** Initial release.

## Overview

- [Scope](#scope)
- [Contributing](#contributing)
- [Simulators](#simulators)
- [Benchmarks](#benchmarks)
- [Models](#models)
- [Agents](#agents)

## Scope

This repository tracks work on **brain models for embodied agents** — the models and agent systems responsible for spatio-temporal perception and task planning in embodied AI.

- **Simulators**: Simulation environments, platforms, and data ecosystems for embodied agent research.
- **Benchmarks**: Evaluation protocols that measure embodied planning, reasoning, and agent capabilities.
- **Models**: Foundation models that serve as the "brain" — VLMs, VLAs, world models, diffusion policies, and generalist policies for embodied AI.
- **Agents**: Agent systems built on foundation models for navigation, manipulation, exploration, and collaboration.


## Contributing

Pull requests are welcome. Please follow the instructions in [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Simulators
*Simulation environments, platforms, and data ecosystems for embodied agent research.*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-02-11 | [MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation](https://arxiv.org/abs/2602.11337) | `generalist` `nav` `manipulation` `dataset` | `platform` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_11337.bib) |
| 2023-10-19 | [Habitat 3.0: A Co-Habitat for Humans, Avatars and Robots](https://arxiv.org/abs/2310.13724) | `generalist` `multi-agent` | `simulator` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2310_13724.bib) |
| 2025-03-09 | [AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems](https://arxiv.org/abs/2503.06669) | `generalist` `manipulation` `platform` | `simulator` `dataset` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_06669.bib) |
| 2026-04-07 | [CoEnv: Driving Embodied Multi-Agent Collaboration via Compositional Environment](https://arxiv.org/abs/2604.05484) | `multi-agent` `planning` `communication` | `simulator` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_05484.bib) |
| 2023-10-13 | [Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/abs/2310.08864) | `generalist` `dataset` | `platform` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2310_08864.bib) |

---

## Benchmarks
*Evaluation benchmarks for embodied planning, reasoning, and agent capabilities.*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2024-10-18 | [ET-Plan-Bench: Embodied Task-level Planning Benchmark Towards Spatial-Temporal Cognition with Foundation Models](https://arxiv.org/abs/2410.14682) | `benchmark` `planning` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2410_14682.bib) |
| 2024-07-06 | [MFE-ETP: A Comprehensive Evaluation Benchmark for Multi-modal Foundation Models on Embodied Task Planning](https://arxiv.org/abs/2407.05047) | `benchmark` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2407_05047.bib) |
| 2025-02-13 | [EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents](https://arxiv.org/abs/2502.09560) | `benchmark` `generalist` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2502_09560.bib) |
| 2025-01-21 | [EmbodiedEval: Evaluate Multimodal LLMs as Embodied Agents](https://arxiv.org/abs/2501.11858) | `benchmark` `generalist` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2501_11858.bib) |
| 2024-10-31 | [PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks](https://arxiv.org/abs/2411.00081) | `multi-agent` `benchmark` `planning` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2411_00081.bib) |
| 2025-12-19 | [Embodied4C: Measuring What Matters for Embodied Vision-Language Navigation](https://arxiv.org/abs/2512.18028) | `nav` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_18028.bib) |
| 2025-12-31 | [VLN-MME: Diagnosing MLLMs as Language-guided Visual Navigation Agents](https://arxiv.org/abs/2512.24851) | `nav` `benchmark` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24851.bib) |
| 2026-04-21 | [RoboWM-Bench: A Benchmark for Evaluating World Models in Robotic Manipulation](https://arxiv.org/abs/2604.19092) | `manipulation` `benchmark` `world-model` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_19092.bib) |
| 2026-04-18 | [LongBench: Evaluating Robotic Manipulation Policies on Real-World Long-Horizon Tasks](https://arxiv.org/abs/2604.16788) | `manipulation` `long-horizon` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_16788.bib) |
| 2026-04-09 | [PokeGym: A Visually-Driven Long-Horizon Benchmark for Vision-Language Models](https://arxiv.org/abs/2604.08340) | `generalist` `long-horizon` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08340.bib) |
| 2026-03-30 | [ManipArena: Comprehensive Real-world Evaluation of Reasoning-Oriented Generalist Robot Manipulation](https://arxiv.org/abs/2603.28545) | `manipulation` `generalist` `benchmark` | - | CVPR 2026 Challenge | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_28545.bib) |
| 2026-04-18 | [Chain Of Interaction Benchmark (COIN): When Reasoning meets Embodied Interaction](https://arxiv.org/abs/2604.16886) | `generalist` `long-horizon` `benchmark` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_16886.bib) |
| 2026-04-13 | [EmbodiedGovBench: A Benchmark for Governance, Recovery, and Upgrade Safety in Embodied Agent Systems](https://arxiv.org/abs/2604.11174) | `generalist` `benchmark` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_11174.bib) |
| 2026-03-18 | [AgentComm-Bench: Stress-Testing Cooperative Embodied AI Under Latency, Packet Loss, and Bandwidth Collapse](https://arxiv.org/abs/2603.20285) | `multi-agent` `benchmark` `communication` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20285.bib) |
| 2025-12-31 | [DarkEQA: Benchmarking Vision-Language Models for Embodied Question Answering in Low-Light Indoor Environments](https://arxiv.org/abs/2512.24985) | `eqa` `benchmark` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24985.bib) |

---

## Models
*Foundation models that serve as the "brain" of embodied agents: VLMs, VLAs, world models, diffusion policies, and generalist policies.*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2023-03-06 | [PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378) | `generalist` `robotics` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2303_03378.bib) |
| 2023-05-29 | [PaLI-X: On Scaling up a Multilingual Vision and Language Model](https://arxiv.org/abs/2305.18565) | `generalist` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2305_18565.bib) |
| 2023-05-24 | [EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought](https://arxiv.org/abs/2305.15021) | `generalist` `reasoning` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2305_15021.bib) |
| 2023-06-26 | [Kosmos-2: Grounding Multimodal Large Language Models to the World](https://arxiv.org/abs/2306.14824) | `generalist` `grounding` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2306_14824.bib) |
| 2023-11-21 | [An Embodied Generalist Agent in 3D World](https://arxiv.org/abs/2311.12871) | `generalist` `grounding` `reasoning` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2311_12871.bib) |
| 2025-03-25 | [Gemini Robotics: Bringing AI into the Physical World](https://arxiv.org/abs/2503.20020) | `generalist` `robotics` | `vla` `foundation-model` `reasoning` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_20020.bib) |
| 2025-01-03 | [EnerVerse: Envisioning Embodied Future Space for Robotics Manipulation](https://arxiv.org/abs/2501.01895) | `generalist` `world-model` | `vlm` `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2501_01895.bib) |
| 2025-01-07 | [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) | `generalist` `world-model` | `foundation-model` `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2501_03575.bib) |
| 2025-02-27 | [RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete](https://arxiv.org/abs/2502.21257) | `generalist` `robotics` `reasoning` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2502_21257.bib) |
| 2025-07-02 | [RoboBrain 2.0 Technical Report](https://arxiv.org/abs/2507.02029) | `generalist` `robotics` `planning` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2507_02029.bib) |
| 2026-01-21 | [RoboBrain 2.5: Depth in Sight, Time in Mind](https://arxiv.org/abs/2601.14352) | `generalist` `robotics` `spatio-temporal` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2601_14352.bib) |
| 2026-03-24 | [ABot-PhysWorld: Interactive World Foundation Model for Robotic Manipulation with Physics Alignment](https://arxiv.org/abs/2603.23376) | `manipulation` `world-model` | `foundation-model` `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_23376.bib) |
| 2025-12-21 | [ChronoDreamer: Action-Conditioned World Model as an Online Simulator for Robotic Planning](https://arxiv.org/abs/2512.18619) | `manipulation` `world-model` `planning` | `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_18619.bib) |
| 2026-03-31 | [DIAL: Decoupling Intent and Action via Latent World Modeling for End-to-End VLA](https://arxiv.org/abs/2603.29844) | `generalist` `world-model` | `vla` `latent-dynamics` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_29844.bib) |
| 2026-03-26 | [Persistent Robot World Models: Stabilizing Multi-Step Rollouts via Reinforcement Learning](https://arxiv.org/abs/2603.25685) | `generalist` `world-model` | `rl` `latent-dynamics` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_25685.bib) |
| 2026-04-16 | [World-Value-Action Model: Implicit Planning for Vision-Language-Action Systems](https://arxiv.org/abs/2604.14732) | `generalist` `planning` `world-model` | `vla` `latent-dynamics` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_14732.bib) |
| 2026-04-09 | [WorldMAP: Bootstrapping Vision-Language Navigation Trajectory Prediction with Generative World Models](https://arxiv.org/abs/2604.07957) | `nav` `world-model` `planning` | `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07957.bib) |
| 2026-03-26 | [Policy-Guided World Model Planning for Language-Conditioned Visual Navigation](https://arxiv.org/abs/2603.25981) | `nav` `world-model` `planning` | `latent-dynamics` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_25981.bib) |
| 2025-12-25 | [AstraNav-World: World Model for Foresight Control and Consistency](https://arxiv.org/abs/2512.21714) | `nav` `world-model` `control` | `video-prediction` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21714.bib) |
| 2023-03-07 | [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137) | `manipulation` `robotics` | `diffusion-policy` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2303_04137.bib) |
| 2024-10-10 | [RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation](https://arxiv.org/abs/2410.07864) | `manipulation` `robotics` | `diffusion-policy` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2410_07864.bib) |
| 2022-10-06 | [VIMA: General Robot Manipulation with Multimodal Prompts](https://arxiv.org/abs/2210.03094) | `manipulation` `robotics` | `foundation-model` `multimodal` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2210_03094.bib) |
| 2024-02-15 | [Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots](https://arxiv.org/abs/2402.10329) | `manipulation` `robotics` | `foundation-model` `policy` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2402_10329.bib) |
| 2024-10-17 | [Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance](https://arxiv.org/abs/2410.13816) | `generalist` `robotics` | `foundation-model` `policy` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2410_13816.bib) |
| 2024-11-04 | [IGOR: Image-GOal Representations are the Atomic Control Units for Foundation Models in Embodied AI](https://arxiv.org/abs/2411.00785) | `generalist` `robotics` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2411_00785.bib) |
| 2023-07-19 | [XSkill: Cross Embodiment Skill Discovery](https://arxiv.org/abs/2307.09955) | `generalist` `robotics` | `foundation-model` `skill-learning` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2307_09955.bib) |
| 2026-04-10 | [Spatio-Temporal Grounding of Large Language Models from Perception Streams](https://arxiv.org/abs/2604.07592) | `generalist` `spatio-temporal` `grounding` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07592.bib) |
| 2026-04-09 | [3D-VCD: Hallucination Mitigation in 3D-LLM Embodied Agents through Visual Contrastive Decoding](https://arxiv.org/abs/2604.08645) | `generalist` `grounding` | `scene-graph` `contrastive-decoding` | CVPR 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08645.bib) |
| 2023-12-24 | [ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation](https://arxiv.org/abs/2312.16217) | `manipulation` `reasoning` | `vlm` `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2312_16217.bib) |
| 2026-03-06 | [History-Conditioned Spatio-Temporal Visual Token Pruning for Efficient Vision-Language Navigation](https://arxiv.org/abs/2603.06480) | `nav` `perception` `spatio-temporal` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_06480.bib) |
| 2026-03-13 | [RoboStream: Weaving Spatio-Temporal Reasoning with Memory in Vision-Language Models for Robotics](https://arxiv.org/abs/2603.12939) | `generalist` `reasoning` `memory` `spatio-temporal` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_12939.bib) |
| 2025-12-25 | [AstraNav-Memory: Contexts Compression for Long Memory](https://arxiv.org/abs/2512.21627) | `nav` `long-horizon` `memory` `temporal-reasoning` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21627.bib) |
| 2026-03-25 | [Chameleon: Episodic Memory for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2603.24576) | `manipulation` `long-horizon` `memory` `temporal-reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_24576.bib) |
| 2026-03-17 | [When Should a Robot Think? Resource-Aware Reasoning via Reinforcement Learning for Embodied Robotic Decision-Making](https://arxiv.org/abs/2603.16673) | `generalist` `reasoning` `temporal-reasoning` | `rl` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_16673.bib) |
| 2025-12-22 | [Vision-Language-Policy Model for Dynamic Robot Task Planning](https://arxiv.org/abs/2512.19178) | `generalist` `planning` `control` `temporal-reasoning` | `vlm` `policy` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_19178.bib) |
| 2025-12-25 | [HELP: Hierarchical Embodied Language Planner for Household Tasks](https://arxiv.org/abs/2512.21723) | `manipulation` `household` `planning` | `hierarchical` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21723.bib) |
| 2025-12-24 | [ETP-R1: Evolving Topological Planning with Reinforcement Fine-tuning for Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2512.20940) | `nav` `planning` `temporal-reasoning` | `rl` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_20940.bib) |
| 2025-12-18 | [MomaGraph: State-Aware Unified Scene Graphs with Vision-Language Model for Embodied Task Planning](https://arxiv.org/abs/2512.16909) | `manipulation` `planning` | `scene-graph` `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_16909.bib) |
| 2026-03-13 | [ReMem-VLA: Empowering Vision-Language-Action Model with Memory via Dual-Level Recurrent Queries](https://arxiv.org/abs/2603.12942) | `generalist` `memory` `temporal-reasoning` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_12942.bib) |
| 2026-02-25 | [LiLo-VLA: Compositional Long-Horizon Manipulation via Linked Object-Centric Policies](https://arxiv.org/abs/2602.21531) | `manipulation` `long-horizon` `planning` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_21531.bib) |

---

## Agents
*Agent systems built on foundation models for navigation, manipulation, exploration, and collaboration.*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-23 | [A Deployable Embodied Vision-Language Navigation System with Hierarchical Cognition and Context-Aware Exploration](https://arxiv.org/abs/2604.21363) | `nav` `planning` `reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_21363.bib) |
| 2026-04-21 | [LiveVLN: Breaking the Stop-and-Go Loop in Vision-Language Navigation](https://arxiv.org/abs/2604.19536) | `nav` `control` `spatio-temporal` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_19536.bib) |
| 2026-04-09 | [HiRO-Nav: Hybrid ReasOning Enables Efficient Embodied Navigation](https://arxiv.org/abs/2604.08232) | `nav` `reasoning` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08232.bib) |
| 2026-03-18 | [OmniVLN: Omnidirectional 3D Perception and Token-Efficient LLM Reasoning for Visual-Language Navigation across Air and Ground Platforms](https://arxiv.org/abs/2603.17351) | `nav` `perception` `reasoning` `spatio-temporal` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_17351.bib) |
| 2026-03-18 | [AgentVLN: Towards Agentic Vision-and-Language Navigation](https://arxiv.org/abs/2603.17670) | `nav` `planning` | `vlm` `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_17670.bib) |
| 2026-03-16 | [EmergeNav: Structured Embodied Inference for Zero-Shot Vision-and-Language Navigation in Continuous Environments](https://arxiv.org/abs/2603.16947) | `nav` `reasoning` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_16947.bib) |
| 2026-03-20 | [CeRLP: A Cross-embodiment Robot Local Planning Framework for Visual Navigation](https://arxiv.org/abs/2603.19602) | `nav` `planning` `control` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19602.bib) |
| 2026-04-05 | [Hypothesis Graph Refinement: Hypothesis-Driven Exploration with Cascade Error Correction for Embodied Navigation](https://arxiv.org/abs/2604.04108) | `nav` `planning` `reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_04108.bib) |
| 2026-04-02 | [Reliability-Aware Geometric Fusion for Robust Audio-Visual Navigation](https://arxiv.org/abs/2604.02391) | `nav` `perception` | `audio-visual` | IJCNN 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_02391.bib) |
| 2026-03-20 | [Semantic Audio-Visual Navigation in Continuous Environments](https://arxiv.org/abs/2603.19660) | `nav` `control` | `audio-visual` | CVPR 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19660.bib) |
| 2026-04-23 | [Long-Horizon Manipulation via Trace-Conditioned VLA Planning](https://arxiv.org/abs/2604.21924) | `manipulation` `long-horizon` `planning` `spatio-temporal` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_21924.bib) |
| 2026-04-21 | [GenerativeMPC: VLM-RAG-guided Whole-Body MPC with Virtual Impedance for Bimanual Mobile Manipulation](https://arxiv.org/abs/2604.19522) | `manipulation` `nav` `planning` `control` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_19522.bib) |
| 2026-04-15 | [ESCAPE: Episodic Spatial Memory and Adaptive Execution Policy for Long-Horizon Mobile Manipulation](https://arxiv.org/abs/2604.13633) | `manipulation` `nav` `long-horizon` `memory` `spatio-temporal` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_13633.bib) |
| 2026-03-09 | [MoMaStage: Skill-State Graph Guided Planning and Closed-Loop Execution for Long-Horizon Indoor Mobile Manipulation](https://arxiv.org/abs/2603.08383) | `manipulation` `nav` `long-horizon` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_08383.bib) |
| 2026-02-09 | [UniPlan: Vision-Language Task Planning for Mobile Manipulation with Unified PDDL Formulation](https://arxiv.org/abs/2602.08537) | `manipulation` `nav` `long-horizon` `planning` | `hierarchical` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_08537.bib) |
| 2026-02-04 | [Integrated Exploration and Sequential Manipulation on Scene Graph with LLM-based Situated Replanning](https://arxiv.org/abs/2602.04419) | `manipulation` `nav` `planning` `reasoning` | `scene-graph` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_04419.bib) |
| 2025-05-05 | [MORE: Mobile Manipulation Rearrangement Through Grounded Language Reasoning](https://arxiv.org/abs/2505.03035) | `manipulation` `nav` `long-horizon` `reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2505_03035.bib) |
| 2025-03-11 | [Instruction-Augmented Long-Horizon Planning: Embedding Grounding Mechanisms in Embodied Mobile Manipulation](https://arxiv.org/abs/2503.08084) | `manipulation` `nav` `long-horizon` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_08084.bib) |
| 2024-11-07 | [DynaMem: Online Dynamic Spatio-Semantic Memory for Open World Mobile Manipulation](https://arxiv.org/abs/2411.04999) | `manipulation` `nav` `memory` `spatial-memory` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2411_04999.bib) |
| 2024-04-16 | [Closed-Loop Open-Vocabulary Mobile Manipulation with GPT-4V](https://arxiv.org/abs/2404.10220) | `manipulation` `nav` `planning` `reasoning` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2404_10220.bib) |
| 2026-04-14 | [DeCoNav: Dialog enhanced Long-Horizon Collaborative Vision-Language Navigation](https://arxiv.org/abs/2604.12486) | `multi-agent` `nav` `long-horizon` `communication` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_12486.bib) |
| 2026-03-21 | [Does Peer Observation Help? Vision-Sharing Collaboration for Vision-Language Navigation](https://arxiv.org/abs/2603.20804) | `multi-agent` `nav` `communication` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20804.bib) |
| 2026-03-24 | [A Multimodal Framework for Human-Multi-Agent Interaction](https://arxiv.org/abs/2603.23271) | `multi-agent` `human-robot` `communication` | `agent-system` | HRI 2026 Workshop | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_23271.bib) |
| 2025-11-30 | [Transforming Monolithic Foundation Models into Embodied Multi-Agent Architectures for Human-Robot Collaboration](https://arxiv.org/abs/2512.00797) | `multi-agent` `human-robot` | `foundation-model` `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_00797.bib) |
| 2025-12-30 | [Align While Search: Belief-Guided Exploratory Inference for World-Grounded Embodied Agents](https://arxiv.org/abs/2512.24461) | `active-search` `world-model` `reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24461.bib) |
| 2025-12-18 | [SNOW: Spatio-Temporal Scene Understanding with World Knowledge for Open-World Embodied Reasoning](https://arxiv.org/abs/2512.16461) | `active-search` `perception` `reasoning` `spatio-temporal` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_16461.bib) |
| 2025-11-24 | [Prune-Then-Plan: Step-Level Calibration for Stable Frontier Exploration in Embodied Question Answering](https://arxiv.org/abs/2511.19768) | `eqa` `active-search` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2511_19768.bib) |
| 2025-07-17 | [Enter the Mind Palace: Reasoning and Planning for Long-term Active Embodied Question Answering](https://arxiv.org/abs/2507.12846) | `eqa` `long-horizon` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2507_12846.bib) |
| 2026-03-19 | [GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137) | `active-search` `memory` `spatial-memory` | `3d-memory` `nerf-gs` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19137.bib) |
| 2026-03-20 | [Memory Over Maps: 3D Object Localization Without Reconstruction](https://arxiv.org/abs/2603.20530) | `nav` `localization` `spatial-memory` | `3d-memory` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20530.bib) |
| 2025-12-02 | [Vision to Geometry: 3D Spatial Memory for Sequential Embodied MLLM Reasoning and Exploration](https://arxiv.org/abs/2512.02458) | `active-search` `reasoning` `spatial-memory` | `3d-memory` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_02458.bib) |
| 2026-02-17 | [HIMM: Human-Inspired Long-Term Memory Modeling for Embodied Exploration and Question Answering](https://arxiv.org/abs/2602.15513) | `eqa` `active-search` `memory` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_15513.bib) |
| 2025-02-18 | [CityEQA: A Hierarchical LLM Agent on Embodied Question Answering Benchmark in City Space](https://arxiv.org/abs/2502.12532) | `eqa` `planning` | `hierarchical` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2502_12532.bib) |
| 2025-05-20 | [Memory-Centric Embodied Question Answering](https://arxiv.org/abs/2505.13948) | `eqa` `memory` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2505_13948.bib) |
| 2026-02-17 | [FAST-EQA: Efficient Embodied Question Answering with Global and Local Region Relevancy](https://arxiv.org/abs/2602.15813) | `eqa` `perception` `reasoning` | `agent-system` | WACV 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_15813.bib) |
| 2026-04-12 | [From Perception to Planning: Evolving Ego-Centric Task-Oriented Spatiotemporal Reasoning via Curriculum Learning](https://arxiv.org/abs/2604.10517) | `generalist` `spatio-temporal` `planning` `temporal-reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_10517.bib) |
| 2026-04-10 | [EgoTL: Egocentric Think-Aloud Chains for Long-Horizon Tasks](https://arxiv.org/abs/2604.09535) | `long-horizon` `benchmark` `dataset` `temporal-reasoning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_09535.bib) |
