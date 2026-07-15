<div align="center">
  <h1>Noemion</h1>
  <p><strong>Goals are too important to live only in a prompt.</strong></p>
  <p>Researching a durable, inspectable foundation for natural-language goals.</p>
  <p>
    <img alt="Stage: Research and specification" src="https://img.shields.io/badge/stage-research_%26_specification-0969da?style=flat-square">
  </p>
  <p>
    <a href="https://noemion.github.io/">Project portal</a>
    ·
    <a href="https://noemion.github.io/docs/getting-started.html">Start here</a>
    ·
    <a href="https://noemion.github.io/architecture/">Architecture</a>
    ·
    <a href="https://noemion.github.io/specifications/">Specifications</a>
  </p>
</div>

---

## The problem

AI systems can take powerful actions, yet their goals are often trapped in temporary conversations, scattered instructions, and model interpretations that are difficult to inspect later.

When the goal matters, “the model probably understood” is not a strong enough foundation.

## The idea

Noemion explores a different approach: keep natural language human-readable while making its meaning, unresolved gaps, desired outcome, and acceptance conditions explicit enough for software to inspect.

At the center is **Endem**—a proposed artifact for one independently understandable and verifiable desired end state. Think of it as a goal that can carry its own context without pretending uncertainty has disappeared.

The long-term direction is simple to state, even if it is hard to build:

- preserve what people actually said;
- make interpretation and remaining ambiguity visible;
- separate model suggestions from trusted decisions;
- compare intended outcomes with scoped evidence;
- keep formation, inspection, and execution in separate trust boundaries.

Natural language remains the interface. Silent reinterpretation stops being the architecture.

## Current status

Noemion is currently a research and specification project. The public work includes project definitions, architecture boundaries, design proposals, draft specifications, threat analysis, and validation plans.

There is no released Ktisor, Theor, Drasor, or `endem` implementation yet. No executable package, stable ABI, or production compatibility claim is available.

The best place to explore the work is the **[Noemion project portal](https://noemion.github.io/)**.

<p align="center"><sub>© 2026 Noemion. All rights reserved. Noemion and its associated marks are not licensed for reuse.</sub></p>
