# CAD AI Literature Roadmap

This reading list follows the historical evolution of CAD AI research.

---

# 1. SketchGraphs (2020)

## Paper

https://arxiv.org/abs/2007.08506

## Keywords

Constraint Graph, CAD Representation

## Core Idea

Represent CAD sketches as geometric constraint graphs.

Node:

* Line
* Arc
* Circle

Edge:

* Coincident
* Parallel
* Perpendicular
* Equal

## Contribution

Established the first large-scale CAD constraint graph dataset (15M sketches).

## Position

CAD Representation

---

# 2. DeepCAD (2021)

## Paper

https://arxiv.org/abs/2105.09492

## Keywords

CAD Program Generation

## Core Idea

Treat CAD construction history as a command sequence and generate it using Transformer.

## Contribution

Introduced CAD-as-Language paradigm.

## Position

CAD Generation

---

# 3. Text2CAD (2024)

## Paper

https://arxiv.org/abs/2409.17106

## Keywords

Text-to-CAD

## Core Idea

Generate CAD command sequences directly from natural language.

## Contribution

Built the first large-scale Text-to-CAD dataset.

## Position

Conditional CAD Generation

---

# 4. DAVINCI (2024)

## Paper

https://arxiv.org/abs/2410.22857

## Keywords

Constraint Inference

## Core Idea

Jointly predict sketch primitives and constraints from raster sketches.

## Contribution

Single-stage constrained CAD sketch inference.

## Position

Constraint-Aware CAD Understanding

---

# 5. CADCodeVerify (2024)

## Paper

https://arxiv.org/abs/2410.05340

## Keywords

Visual Feedback

## Core Idea

Use VLMs to verify generated CAD and iteratively improve results.

## Contribution

Introduced Generate → Verify → Repair paradigm.

## Position

Visual Grounding

---

# 6. Aligning Constraint Generation with Design Intent (2025)

## Keywords

Constraint Solver Feedback

## Core Idea

Use constraint solver outputs as reward signals for constraint generation.

## Contribution

Connects Design Intent and Constraint Generation through RL alignment.

## Position

Constraint Grounding

---

# 7. CADSmith (2026)

## Keywords

CAD Kernel Feedback

## Core Idea

Use OpenCASCADE kernel metrics and VLM verification to iteratively repair CAD generation.

## Contribution

Introduced Solver-in-the-loop CAD Agent.

## Position

CAD Kernel Grounding

---

# 8. Pointer-CAD (2026)

## Keywords

Geometry Grounding

## Core Idea

Use pointer networks to explicitly reference CAD entities (faces and edges).

## Contribution

Supports advanced editing operations such as Fillet and Chamfer.

## Position

Geometry Grounding

---

# Evolution of CAD AI

SketchGraphs
↓
CAD Representation

DeepCAD
↓
CAD Generation

Text2CAD
↓
Conditional Generation

DAVINCI
↓
Constraint Inference

CADCodeVerify
↓
Visual Feedback

Pointer-CAD
↓
Geometry Grounding

CADSmith
↓
CAD Kernel Feedback

Constraint Alignment
↓
Constraint Grounding

Future:
Constraint-Aware Incremental CAD Agent
