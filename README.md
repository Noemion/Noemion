<div align="center">
  <h1>Noemion</h1>
  <p><strong>Ends, made inspectable.</strong></p>
  <p>A deterministic foundation for durable natural-language goals.</p>
  <p>
    <img alt="Stage: Specification and Core Design" src="https://img.shields.io/badge/stage-specification_%26_core_design-0969da?style=flat-square">
    <img alt="Formation: Deterministic" src="https://img.shields.io/badge/formation-deterministic-1f883d?style=flat-square">
    <img alt="Models: Untrusted Inputs" src="https://img.shields.io/badge/models-untrusted_inputs-656d76?style=flat-square">
  </p>
  <p>
    <a href="https://noemion.github.io/">Project Portal</a>
    ·
    <a href="https://noemion.github.io/endem/">Endem</a>
    ·
    <a href="https://noemion.github.io/specifications/">Specifications</a>
    ·
    <a href="https://github.com/Noemion/noemion.github.io">Website Source</a>
  </p>
</div>

---

## A new primitive: Endem

**Noemion** is the project and field name. Its foundational artifact is **Endem** (`end` + `-eme`): the smallest independently valid and verifiable unit of a desired end state.

An Endem is not a prompt in a binary wrapper. It has one root situation graph and six typed semantic facets:

| Facet | Responsibility |
| :--- | :--- |
| `rhem` | Source signs and replayable provenance |
| `semion` | Authorized projection into symbols, referents, and relations |
| `skena` | One neutral possible-situation graph |
| `telis` | Direction toward making or keeping that situation actual |
| `krin` | Structural comparison, evidence, and decision contract |
| `apor` | Expressible projection gaps that no authority has resolved |

The situation remains neutral: prohibition is explicit negation inside `skena`, not a second goal force. Runtime observations form a `phain` graph aligned with the same symbols and roles, so `krin` can compare what was sought with what was observed. No artifact self-certifies with `valid`, `true`, or a model score.

## A compact native vocabulary

| Name | Role |
| :--- | :--- |
| **Endem** | One minimal goal artifact |
| **Synem** | A resolved closure of Endems and pinned dependencies |
| **Dromen** | Immutable enactment state for one session; never a file |
| **Tekmor** | Scoped evidence containing `phain`, provenance, strength, and limits |
| **Poiet** | The sole deterministic production and writing domain |
| **Theor** | A separately implemented, read-only interpretation domain |
| **Praxor** | An isolated enactment and least-authority domain |

The command surface is `endem`, with eight native actions:

<p align="center"><code>poie · elenk · pleko · tasse · sphra · theor · praxe · peira</code></p>

<p align="center"><code>source signs → poie → Endem → pleko → Synem → praxe → Dromen → phain / Tekmor → Decision</code></p>

A single command surface does not collapse trust boundaries. Theor cannot reuse production parsing or write artifacts. Praxor cannot own the Poiet writer. Models may propose candidates, plans, or capability parameters; they never write canonical Endem bytes, erase unresolved `apor`, widen authority, or declare acceptance.

## Project portal and status

The design borrows durable ideas from binary toolchains—deterministic writing, explicit composition, independent inspection, bounded loading, reproducibility, and integrity—without copying their machine-instruction ontology or established compiler vocabulary.

The canonical public entry point is **[noemion.github.io](https://noemion.github.io/)**.

> **Current stage:** the native vocabulary, six-facet semantic model, and trust boundaries are accepted design decisions. An unpublished Rust candidate implements `poie`, `elenk`, `theor`, and `peira` against the experimental END-P1 profile; no public implementation repository, stable ABI, or release package exists yet.

<p align="center"><sub>© 2026 Noemion. All rights reserved. Noemion and its associated marks are not licensed for reuse.</sub></p>
