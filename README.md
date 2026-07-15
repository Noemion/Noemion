<div align="center">
  <h1>Noemion</h1>
  <p><strong>For decades, software compiled code written by programmers for machines.<br>The AI era needs a way for everyone to compile human intent for intelligent systems.</strong></p>
  <p>Noemion researches how ordinary people can compile natural-language goals into durable, inspectable artifacts.</p>
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

## A new software boundary

AI systems can take powerful actions, yet their goals are often trapped in temporary conversations, scattered instructions, and model interpretations that are difficult to inspect later.

When the goal matters, “the model probably understood” is not a strong enough foundation.

Noemion's thesis is deliberately ambitious: the people setting a goal should be able to compile their own intent into something an AI system can use without silently redefining it.

This is not natural-language-to-code. It is **intent-to-artifact**.

## What compilation means

In Noemion, compilation means a reviewable path from ordinary language to a durable goal artifact. The process keeps the source human-readable while making its interpretation, unresolved gaps, desired outcome, and acceptance conditions explicit enough for software to inspect.

At the center is **Endem**—a proposed artifact for one independently understandable and verifiable desired end state. Think of it as a goal that can carry its own context without pretending uncertainty has disappeared.

The direction is simple to state, even if it is hard to build:

- preserve what people actually said;
- make interpretation and remaining ambiguity visible;
- separate model suggestions from trusted decisions;
- compare intended outcomes with scoped evidence;
- keep formation, inspection, and execution in separate trust boundaries.

Compilation may stop when meaning is missing. An AI system may use the result, but it does not silently become the authority over what the user meant.

## Current status

Noemion is currently a research and specification project. The public work includes project definitions, architecture boundaries, design proposals, draft specifications, threat analysis, and validation plans.

There is no released Ktisor, Theor, Drasor, or `endem` implementation yet. No executable package, stable ABI, or production compatibility claim is available.

The best place to explore the work is the **[Noemion project portal](https://noemion.github.io/)**.

<p align="center"><sub>© 2026 Noemion. All rights reserved. Noemion and its associated marks are not licensed for reuse.</sub></p>
