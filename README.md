# CAD-AI-Roadmap

A curated roadmap for learning and researching AI for Computer-Aided Design (CAD).

This repository collects key papers, datasets, benchmarks, and research notes covering the evolution of CAD AI from geometric representation learning to constraint-aware CAD agents.

Our long-term research goal is:

> Transform CAD AI from one-shot CAD generation into constraint-aware incremental editing systems capable of maintaining design intent through interactive decision making.

---

## Research Roadmap

Current CAD AI research can be roughly divided into five stages:

### Stage 1: CAD Representation

How should CAD be represented for machine learning?

* Geometry Graph
* Constraint Graph
* CAD Program
* CAD Command Sequence

Representative work:

* SketchGraphs (2020)

---

### Stage 2: CAD Generation

Can CAD models be generated autoregressively like language?

Representative work:

* DeepCAD (2021)

---

### Stage 3: Conditional CAD Generation

How can user intent be incorporated into CAD generation?

Representative work:

* Text2CAD (2024)
* CAD-MLLM

---

### Stage 4: Grounded CAD Generation

How can external signals improve CAD generation quality?

Representative directions:

* Visual Feedback
* Geometry Grounding
* CAD Kernel Feedback
* Constraint Solver Feedback

Representative work:

* CADCodeVerify
* CADSmith
* Pointer-CAD
* DAVINCI

---

### Stage 5: Constraint-Aware CAD Agent

Future Direction

How can CAD AI move from static generation to interactive editing?

Key concepts:

* Constraint State
* Constraint Editing
* Incremental CAD Editing
* Constraint Solver as Environment
* Multi-Agent CAD System

Representative ongoing project:

* ConstraintRepairBench
* Constraint-aware Incremental CAD Agent

---

## Our Research Vision

Traditional CAD AI:

Text → CAD

Future CAD AI:

CAD_t + Edit Instruction → CAD_t+1

through:

Constraint State → Action → Solver Feedback → Constraint State

This paradigm transforms CAD generation into an interactive decision-making process.
