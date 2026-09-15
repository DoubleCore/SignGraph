<div align="center">

# SignGraph — Research Reproduction Fork

**Continuous Sign Language Recognition · Graph Modeling · CVPR 2024**

![Fork](https://img.shields.io/badge/Repository-Fork-6E7781?style=flat-square&logo=github)
![Research](https://img.shields.io/badge/Type-Research%20Reproduction-111827?style=flat-square)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CVPR](https://img.shields.io/badge/Paper-CVPR%202024-2563EB?style=flat-square)

A personal research fork of [`gswycf/SignGraph`](https://github.com/gswycf/SignGraph).

</div>

## Repository Context

This repository is **not the original SignGraph implementation**. The model, paper, official code, reported checkpoints, and published results belong to the SignGraph authors and upstream repository.

I use this fork as a reproducibility and experimentation workspace for continuous sign language research.

## Research Focus

The upstream project implements **SignGraph: A Sign Sequence is Worth Graphs of Nodes** and provides experiments for continuous sign language recognition across datasets including PHOENIX14, PHOENIX14-T, and CSL-Daily.

My interest in this codebase is broader than simply running the checkpoint:

- understand the graph-based sequence representation;
- reproduce the published training / evaluation pipeline;
- compare WER behavior across datasets;
- study how the visual backbone can connect with later SLT systems;
- use the implementation as a reference point for CSLR → SLT research;
- document reproducibility gaps instead of silently treating paper numbers as reproduced results.

## Research Workflow

```text
Paper
  ↓
Official implementation
  ↓
Environment reconstruction
  ↓
Dataset / checkpoint validation
  ↓
Reproduction
  ↓
Controlled modifications
  ↓
Measured comparison
```

## Upstream Reported Results

The upstream repository reports SignGraph WER results for PHOENIX14, PHOENIX14-T, and CSL-Daily. Those values are **upstream results**, not automatically results reproduced by this fork.

For official numbers, weights, training commands, and citations, refer to:

[`gswycf/SignGraph`](https://github.com/gswycf/SignGraph)

Paper: **SignGraph: A Sign Sequence is Worth Graphs of Nodes**, CVPR 2024.

## Status

`Research Fork` · `Reproduction Workspace` · `CSLR / SLT Research`

Any future DoubleCore experimental result should be reported separately from the upstream paper result with its own environment, dataset split, checkpoint, and metric.
