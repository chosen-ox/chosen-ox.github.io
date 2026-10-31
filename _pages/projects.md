---
layout: single
title: "Research"
permalink: /projects/
author_profile: true
profile_page: true
excerpt: "Selected projects in autonomous research infrastructure and efficient LLM inference."
---
## Long-Horizon Autonomous Research Infrastructure

<p class="research-meta">Fall 2026</p>

Infrastructure for reliable AI research loops: agent-driven code changes,
isolated GPU experiments, candidate evaluation, and persistent experiment lineage.
Execution protocols and recovery mechanisms support concurrent workers and
process/storage failures, with fault-injection tests and TLA+ models used to
check key invariants.

## DScout: Diffusion-Drafted Speculative Decoding

<p class="research-meta">Summer 2026 · Manuscript under review</p>

Training-inference co-design for diffusion-based token drafting. The work
combines prefix-aware drafter training with acceptance-latency analysis to
improve speculative decoding efficiency.

[Paper](https://arxiv.org/abs/2610.23935)

## Efficient KV Cache Management for Agentic LLM Serving

<p class="research-meta">Spring-Summer 2026</p>

Research on memory pressure and serving efficiency in long-context, multi-turn
LLM workloads. Implemented and evaluated serving optimizations in SGLang,
studying their impact on latency and throughput across agent workloads.

## dLLM-Serve: Memory-Efficient Diffusion LLM Serving

<p class="research-meta">Spring 2025 · ICS 2026</p>

A serving system that addresses transient activation-memory peaks and changing
compute/bandwidth demands during diffusion inference, co-optimizing memory
budgets, request scheduling, and attention execution.

[Paper](https://doi.org/10.1145/3797905.3800532) ·
[Code](https://github.com/chosen-ox/dLLM-Serve)

## APEX: Asynchronous CPU-GPU Execution for LLM Inference

<p class="research-meta">Spring 2025 · IPDPS 2026</p>

An asynchronous hybrid scheduler that overlaps CPU-offloaded work with GPU
execution during memory-constrained decoding. A performance model guides
heterogeneous resource allocation.

[Paper](https://doi.org/10.1109/IPDPS65963.2026.00099)

## SLED: Distributed Speculative LLM Serving

<p class="research-meta">Spring 2025 · ACM/IEEE SEC 2025</p>

Contributed to a distributed speculative decoding framework coordinating token
drafting on heterogeneous edge devices with batched target-model verification
on a shared server.

[Paper](https://doi.org/10.1145/3769102.3770608)
