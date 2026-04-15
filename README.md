<div align="center">
    <h1>Awesome Embodied Spatio-Temporal Agents</h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
</p>

A curated list of recent papers on **embodied spatio-temporal agents**. To reduce overlap between perception, memory, reasoning, and planning papers, this repository now uses a **task-first primary taxonomy** and **layered secondary tags**. Primary sections answer *what problem the agent is solving*; tags capture *which capabilities or methods the paper emphasizes*.

<p align="center">
    <a href="bib/awesome_embodied_agents.bib"><img src="https://img.shields.io/badge/Download-All%20Bib-8B5E3C?logo=bookstack&logoColor=white" alt="Download all bib"></a>
</p>

## News

**[2026/04/15]** Initial release.

## Overview

- [Scope](#scope)
- [Contributing](#contributing)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Generalist & Foundation Agents](#generalist--foundation-agents)
- [Navigation Agents](#navigation-agents)
- [Manipulation Agents](#manipulation-agents)
- [Embodied QA & Active Search](#embodied-qa--active-search)
- [Collaborative / Multi-Agent Embodied Systems](#collaborative--multi-agent-embodied-systems)

## Scope

This repository mainly tracks work since **2023-04-01** on **embodied spatio-temporal agents**, including papers, datasets, benchmarks, and generalist embodied stacks.

- **Primary section**: place each paper in one section by its main task or resource role
- **Profile**: short task / capability / setting tags, such as `nav`, `manipulation`, `eqa`, `multi-agent`, `benchmark`, `memory`, `planning`
- **Method**: short technical tags, such as `vla`, `vlm`, `rl`, `3d-memory`, `audio-visual`; use `-` if not needed


## Contributing

Pull requests are welcome. Please follow the instructions in [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Benchmarks & Evaluation
*Evaluation resources, datasets, and stress tests for embodied agents*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-10 | [EgoTL: Egocentric Think-Aloud Chains for Long-Horizon Tasks](https://arxiv.org/abs/2604.09535) | `long-horizon` `benchmark` `dataset` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_09535.bib) |
| 2026-04-10 | [PinpointQA: A Dataset and Benchmark for Small Object-Centric Spatial Understanding in Indoor Videos](https://arxiv.org/abs/2604.08991) | `benchmark` `grounding` `perception` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08991.bib) |
| 2026-04-09 | [PokeGym: A Visually-Driven Long-Horizon Benchmark for Vision-Language Models](https://arxiv.org/abs/2604.08340) | `generalist` `long-horizon` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08340.bib) |
| 2026-04-09 | [How Far Are Large Multimodal Models from Human-Level Spatial Action? A Benchmark for Goal-Oriented Embodied Navigation in Urban Airspace](https://arxiv.org/abs/2604.07973) | `nav` `uav` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07973.bib) |
| 2026-03-31 | [Benchmarking Interaction, Beyond Policy: a Reproducible Benchmark for Collaborative Instance Object Navigation](https://arxiv.org/abs/2604.00265) | `multi-agent` `nav` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_00265.bib) |
| 2026-03-30 | [ManipArena: Comprehensive Real-world Evaluation of Reasoning-Oriented Generalist Robot Manipulation](https://arxiv.org/abs/2603.28545) | `manipulation` `generalist` `benchmark` | - | CVPR 2026 Challenge | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_28545.bib) |
| 2026-03-18 | [AgentComm-Bench: Stress-Testing Cooperative Embodied AI Under Latency, Packet Loss, and Bandwidth Collapse](https://arxiv.org/abs/2603.20285) | `multi-agent` `benchmark` `communication` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20285.bib) |
| 2025-12-31 | [VLN-MME: Diagnosing MLLMs as Language-guided Visual Navigation agents](https://arxiv.org/abs/2512.24851) | `nav` `benchmark` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24851.bib) |
| 2025-12-31 | [DarkEQA: Benchmarking Vision-Language Models for Embodied Question Answering in Low-Light Indoor Environments](https://arxiv.org/abs/2512.24985) | `eqa` `benchmark` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24985.bib) |
| 2025-12-19 | [Embodied4C: Measuring What Matters for Embodied Vision-Language Navigation](https://arxiv.org/abs/2512.18028) | `nav` `benchmark` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_18028.bib) |
| 2025-12-04 | [When Robots Should Say "I Don't Know": Benchmarking Abstention in Embodied Question Answering](https://arxiv.org/abs/2512.04597) | `eqa` `benchmark` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_04597.bib) |
| 2023-10-13 | [Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/abs/2310.08864) | `generalist` `dataset` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2310_08864.bib) |

## Generalist & Foundation Agents
*Generalist VLA/VLM agents, reusable architectures, and cross-task embodied systems*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-12 | [From Perception to Planning: Evolving Ego-Centric Task-Oriented Spatiotemporal Reasoning via Curriculum Learning](https://arxiv.org/abs/2604.10517) | `generalist` `spatio-temporal` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_10517.bib) |
| 2026-04-10 | [Spatio-Temporal Grounding of Large Language Models from Perception Streams](https://arxiv.org/abs/2604.07592) | `generalist` `spatio-temporal` `grounding` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07592.bib) |
| 2026-04-09 | [3D-VCD: Hallucination Mitigation in 3D-LLM Embodied Agents through Visual Contrastive Decoding](https://arxiv.org/abs/2604.08645) | `generalist` `grounding` | `scene-graph` | CVPR 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08645.bib) |
| 2026-04-09 | [Visually-grounded Humanoid Agents](https://arxiv.org/abs/2604.08509) | `generalist` `humanoid` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08509.bib) |
| 2026-04-09 | [RoboAgent: Chaining Basic Capabilities for Embodied Task Planning](https://arxiv.org/abs/2604.07774) | `generalist` `planning` | `agent-system` | CVPR 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07774.bib) |
| 2026-04-08 | [HY-Embodied-0.5: Embodied Foundation Models for Real-World Agents](https://arxiv.org/abs/2604.07430) | `generalist` | `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07430.bib) |
| 2026-04-08 | [AEROS: A Single-Agent Operating Architecture with Embodied Capability Modules](https://arxiv.org/abs/2604.07039) | `generalist` `planning` | `agent-system` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07039.bib) |
| 2026-04-07 | [Grounding Hierarchical Vision-Language-Action Models Through Explicit Language-Action Alignment](https://arxiv.org/abs/2604.05614) | `generalist` | `vla` `hierarchical` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_05614.bib) |
| 2026-04-07 | [SnapFlow: One-Step Action Generation for Flow-Matching VLAs via Progressive Self-Distillation](https://arxiv.org/abs/2604.05656) | `generalist` | `vla` `diffusion` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_05656.bib) |
| 2026-04-06 | [StarVLA: A Lego-like Codebase for Vision-Language-Action Model Developing](https://arxiv.org/abs/2604.05014) | `generalist` | `vla` `platform` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_05014.bib) |
| 2026-03-31 | [DIAL: Decoupling Intent and Action via Latent World Modeling for End-to-End VLA](https://arxiv.org/abs/2603.29844) | `generalist` `world-model` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_29844.bib) |
| 2026-03-26 | [Persistent Robot World Models: Stabilizing Multi-Step Rollouts via Reinforcement Learning](https://arxiv.org/abs/2603.25685) | `generalist` `world-model` | `rl` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_25685.bib) |
| 2026-03-17 | [When Should a Robot Think? Resource-Aware Reasoning via Reinforcement Learning for Embodied Robotic Decision-Making](https://arxiv.org/abs/2603.16673) | `generalist` `reasoning` | `rl` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_16673.bib) |
| 2026-03-13 | [RoboStream: Weaving Spatio-Temporal Reasoning with Memory in Vision-Language Models for Robotics](https://arxiv.org/abs/2603.12939) | `generalist` `reasoning` `memory` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_12939.bib) |
| 2026-03-13 | [ReMem-VLA: Empowering Vision-Language-Action Model with Memory via Dual-Level Recurrent Queries](https://arxiv.org/abs/2603.12942) | `generalist` `memory` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_12942.bib) |
| 2025-12-22 | [Vision-Language-Policy Model for Dynamic Robot Task Planning](https://arxiv.org/abs/2512.19178) | `generalist` `planning` `control` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_19178.bib) |
| 2024-06-13 | [OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/abs/2406.09246) | `generalist` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2406_09246.bib) |
| 2024-05-20 | [Octo: An Open-Source Generalist Robot Policy](https://arxiv.org/abs/2405.12213) | `generalist` `control` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2405_12213.bib) |
| 2023-07-28 | [RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/abs/2307.15818) | `generalist` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2307_15818.bib) |

## Navigation Agents
*Navigation, localization, audio-visual navigation, and navigation-centric planning/world modeling*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-09 | [WorldMAP: Bootstrapping Vision-Language Navigation Trajectory Prediction with Generative World Models](https://arxiv.org/abs/2604.07957) | `nav` `world-model` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07957.bib) |
| 2026-04-09 | [HiRO-Nav: Hybrid ReasOning Enables Efficient Embodied Navigation](https://arxiv.org/abs/2604.08232) | `nav` `reasoning` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08232.bib) |
| 2026-04-05 | [Hypothesis Graph Refinement: Hypothesis-Driven Exploration with Cascade Error Correction for Embodied Navigation](https://arxiv.org/abs/2604.04108) | `nav` `planning` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_04108.bib) |
| 2026-04-02 | [Reliability-Aware Geometric Fusion for Robust Audio-Visual Navigation](https://arxiv.org/abs/2604.02391) | `nav` `perception` | `audio-visual` | IJCNN 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_02391.bib) |
| 2026-03-26 | [Policy-Guided World Model Planning for Language-Conditioned Visual Navigation](https://arxiv.org/abs/2603.25981) | `nav` `world-model` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_25981.bib) |
| 2026-03-20 | [Memory Over Maps: 3D Object Localization Without Reconstruction](https://arxiv.org/abs/2603.20530) | `nav` `localization` | `3d-memory` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20530.bib) |
| 2026-03-20 | [Semantic Audio-Visual Navigation in Continuous Environments](https://arxiv.org/abs/2603.19660) | `nav` `control` | `audio-visual` | CVPR 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19660.bib) |
| 2026-03-20 | [CeRLP: A Cross-embodiment Robot Local Planning Framework for Visual Navigation](https://arxiv.org/abs/2603.19602) | `nav` `planning` `control` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19602.bib) |
| 2026-03-18 | [OmniVLN: Omnidirectional 3D Perception and Token-Efficient LLM Reasoning for Visual-Language Navigation across Air and Ground Platforms](https://arxiv.org/abs/2603.17351) | `nav` `perception` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_17351.bib) |
| 2026-03-18 | [AgentVLN: Towards Agentic Vision-and-Language Navigation](https://arxiv.org/abs/2603.17670) | `nav` `planning` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_17670.bib) |
| 2026-03-16 | [EmergeNav: Structured Embodied Inference for Zero-Shot Vision-and-Language Navigation in Continuous Environments](https://arxiv.org/abs/2603.16947) | `nav` `reasoning` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_16947.bib) |
| 2026-03-06 | [History-Conditioned Spatio-Temporal Visual Token Pruning for Efficient Vision-Language Navigation](https://arxiv.org/abs/2603.06480) | `nav` `perception` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_06480.bib) |
| 2025-12-25 | [AstraNav-World: World Model for Foresight Control and Consistency](https://arxiv.org/abs/2512.21714) | `nav` `world-model` `control` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21714.bib) |
| 2025-12-25 | [AstraNav-Memory: Contexts Compression for Long Memory](https://arxiv.org/abs/2512.21627) | `nav` `long-horizon` `memory` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21627.bib) |
| 2025-12-24 | [ETP-R1: Evolving Topological Planning with Reinforcement Fine-tuning for Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2512.20940) | `nav` `planning` | `rl` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_20940.bib) |

## Manipulation Agents
*Grasping, manipulation, household execution, and manipulation-centric planning/world modeling*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-10 | [AssemLM: Spatial Reasoning Multimodal Large Language Models for Robotic Assembly](https://arxiv.org/abs/2604.08983) | `manipulation` `assembly` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_08983.bib) |
| 2026-04-08 | [A Physical Agentic Loop for Language-Guided Grasping with Execution-State Monitoring](https://arxiv.org/abs/2604.07395) | `manipulation` `grasping` `control` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_07395.bib) |
| 2026-03-29 | [ProgressVLA: Progress-Guided Diffusion Policy for Vision-Language Robotic Manipulation](https://arxiv.org/abs/2603.27670) | `manipulation` | `vla` `diffusion` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_27670.bib) |
| 2026-03-28 | [LOME: Learning Human-Object Manipulation with Action-Conditioned Egocentric World Model](https://arxiv.org/abs/2603.27449) | `manipulation` `world-model` `perception` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_27449.bib) |
| 2026-03-25 | [Chameleon: Episodic Memory for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2603.24576) | `manipulation` `long-horizon` `memory` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_24576.bib) |
| 2026-03-24 | [ABot-PhysWorld: Interactive World Foundation Model for Robotic Manipulation with Physics Alignment](https://arxiv.org/abs/2603.23376) | `manipulation` `world-model` | `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_23376.bib) |
| 2026-03-10 | [See, Plan, Rewind: Progress-Aware Vision-Language-Action Models for Robust Robotic Manipulation](https://arxiv.org/abs/2603.09292) | `manipulation` `planning` | `vla` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_09292.bib) |
| 2026-02-25 | [LiLo-VLA: Compositional Long-Horizon Manipulation via Linked Object-Centric Policies](https://arxiv.org/abs/2602.21531) | `manipulation` `long-horizon` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_21531.bib) |
| 2025-12-25 | [HELP: Hierarchical Embodied Language Planner for Household Tasks](https://arxiv.org/abs/2512.21723) | `manipulation` `household` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_21723.bib) |
| 2025-12-21 | [ChronoDreamer: Action-Conditioned World Model as an Online Simulator for Robotic Planning](https://arxiv.org/abs/2512.18619) | `manipulation` `world-model` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_18619.bib) |
| 2025-12-18 | [MomaGraph: State-Aware Unified Scene Graphs with Vision-Language Model for Embodied Task Planning](https://arxiv.org/abs/2512.16909) | `manipulation` `planning` | `scene-graph` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_16909.bib) |
| 2023-07-11 | [VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models](https://arxiv.org/abs/2307.05973) | `manipulation` `planning` | `vlm` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2307_05973.bib) |

## Embodied QA & Active Search
*Embodied question answering, active search, exploration, and long-horizon reasoning*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-03-19 | [GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137) | `active-search` `memory` | `3d-memory` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_19137.bib) |
| 2026-03-10 | [Memory-Guided View Refinement for Dynamic Human-in-the-loop EQA](https://arxiv.org/abs/2603.09541) | `eqa` `memory` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_09541.bib) |
| 2026-02-17 | [FAST-EQA: Efficient Embodied Question Answering with Global and Local Region Relevancy](https://arxiv.org/abs/2602.15813) | `eqa` `perception` `reasoning` | - | WACV 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_15813.bib) |
| 2026-02-17 | [HIMM: Human-Inspired Long-Term Memory Modeling for Embodied Exploration and Question Answering](https://arxiv.org/abs/2602.15513) | `eqa` `active-search` `memory` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_15513.bib) |
| 2025-12-30 | [Align While Search: Belief-Guided Exploratory Inference for World-Grounded Embodied Agents](https://arxiv.org/abs/2512.24461) | `active-search` `world-model` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_24461.bib) |
| 2025-12-18 | [SNOW: Spatio-Temporal Scene Understanding with World Knowledge for Open-World Embodied Reasoning](https://arxiv.org/abs/2512.16461) | `active-search` `perception` `reasoning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_16461.bib) |
| 2025-12-02 | [Vision to Geometry: 3D Spatial Memory for Sequential Embodied MLLM Reasoning and Exploration](https://arxiv.org/abs/2512.02458) | `active-search` `reasoning` | `3d-memory` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_02458.bib) |
| 2025-11-24 | [Prune-Then-Plan: Step-Level Calibration for Stable Frontier Exploration in Embodied Question Answering](https://arxiv.org/abs/2511.19768) | `eqa` `active-search` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2511_19768.bib) |
| 2025-07-17 | [Enter the Mind Palace: Reasoning and Planning for Long-term Active Embodied Question Answering](https://arxiv.org/abs/2507.12846) | `eqa` `long-horizon` `planning` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2507_12846.bib) |
| 2025-07-16 | [3D-MoRe: Unified Modal-Contextual Reasoning for Embodied Question Answering](https://arxiv.org/abs/2507.12026) | `eqa` `reasoning` `perception` | - | IROS 2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2507_12026.bib) |
| 2025-06-01 | [GraphPad: Inference-Time 3D Scene Graph Updates for Embodied Question Answering](https://arxiv.org/abs/2506.01174) | `eqa` `reasoning` | `scene-graph` | CVPR 2025 Workshop | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2506_01174.bib) |
| 2025-05-20 | [Memory-Centric Embodied Question Answering](https://arxiv.org/abs/2505.13948) | `eqa` `memory` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2505_13948.bib) |
| 2025-02-18 | [CityEQA: A Hierarchical LLM Agent on Embodied Question Answering Benchmark in City Space](https://arxiv.org/abs/2502.12532) | `eqa` `planning` | `hierarchical` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2502_12532.bib) |

## Collaborative / Multi-Agent Embodied Systems
*Multi-agent collaboration, communication, and human-robot coordination*

| Date | Paper Title | Profile | Method | Venue | Resources |
|------|-------------|---------|--------|-------|-----------|
| 2026-04-07 | [CoEnv: Driving Embodied Multi-Agent Collaboration via Compositional Environment](https://arxiv.org/abs/2604.05484) | `multi-agent` `planning` `communication` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_05484.bib) |
| 2026-03-24 | [A Multimodal Framework for Human-Multi-Agent Interaction](https://arxiv.org/abs/2603.23271) | `multi-agent` `human-robot` `communication` | - | HRI 2026 Workshop | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_23271.bib) |
| 2026-03-21 | [Does Peer Observation Help? Vision-Sharing Collaboration for Vision-Language Navigation](https://arxiv.org/abs/2603.20804) | `multi-agent` `nav` `communication` | - | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20804.bib) |
| 2025-11-30 | [Transforming Monolithic Foundation Models into Embodied Multi-Agent Architectures for Human-Robot Collaboration](https://arxiv.org/abs/2512.00797) | `multi-agent` `human-robot` | `foundation-model` | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_00797.bib) |
