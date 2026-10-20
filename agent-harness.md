# Agent Harness — Harness²

A resource on recursive agent harnessing from Google Research.

## Links

- [Source code and documentation](https://github.com/google-research/harness2)
- [Research paper: Harness² — Recursive Agent Harnessing for an Open World](https://arxiv.org/abs/2610.14224)
- [Upstream license: Apache 2.0](https://github.com/google-research/harness2/blob/main/LICENSE)

## What it does

Harness² refines the system surrounding an AI model, including prompts, tools, memory, skills and orchestration, while keeping model weights fixed.

- Task-level recursion proposes harness changes, probes their effects on the current task and composes a refinement from the execution evidence.
- Harnessing-level recursion retains adopted harnesses and evidence-supported lessons to guide future tasks.

The release supports parallel and sequential recursion, with Codex and OpenCode executors. See the upstream documentation for setup and supported benchmarks.

## Context

This is a research framework; the upstream repository states that it is not an officially supported Google product. Its documented method optimises the harness with fixed model weights; describing it simply as reinforcement-learning model training would be inaccurate.

## Potential use in design-to-production workflows

An experimental application would be comparing agent workflows for component reuse, design-token adherence, accessibility checks and code quality, then retaining improvements supported by evaluation evidence. This is a proposed application, not a validated result from the paper.

Added: 20 October 2026. Summary based on the upstream README; linked resources retain their original licenses.
