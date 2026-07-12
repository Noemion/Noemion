<div align="center">
  <h1>Noemion</h1>
  <p><strong>Ends, made inspectable.</strong></p>
  <p>A deterministic foundation for durable natural-language goals.</p>
  <p>
    <img alt="Stage: Specification and Core Design" src="https://img.shields.io/badge/stage-specification_%26_core_design-0969da?style=flat-square">
    <img alt="Core: Deterministic" src="https://img.shields.io/badge/core-deterministic-1f883d?style=flat-square">
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

**Noemion** is the project and ecosystem name. Its core engineering term is **Endem** (`end` + `-eme`): the smallest independently valid and verifiable unit of a desired end state.

An Endem is not a prompt wrapped in a binary container. It carries one root case graph together with five explicit projection groups:

| `say` | `mean` | `case` | `when` | `open` |
| :--- | :--- | :--- | :--- | :--- |
| Source signs and provenance | Authorized meaning projection | One possible target situation | Fulfillment observations and authority | Preserved projection gaps |

The relation graph itself carries the logical form: the artifact does not self-certify through a `logical_form`, `valid`, or `true` label. Invalid sign combinations, unresolved projections, and insufficient observations remain distinct as `no-sense`, `open`, and `unknown`.

<p align="center"><code>source → form → Endem → [optional bind → Weave] → run → Frame → Witness</code></p>

## One compact application surface

The project plans one public command, `endem`, instead of a family of prefixed tools:

| Command | Responsibility |
| :--- | :--- |
| `endem form` | Deterministically form an Endem from controlled source bindings |
| `endem check` | Validate the actual artifact and return scoped verification evidence |
| `endem bind` | Resolve references and build a closed Weave |
| `endem pack` / `seal` | Prepare a release and bind an external signature response |
| `endem see` | Inspect with a separately implemented, read-only parser |
| `endem run` | Start an isolated runner with explicit capabilities and acceptance policy |
| `endem test` | Run conformance, reproducibility, malformed-input, and cross-reader tests |

A single user-facing command does not collapse trust domains. `see` must remain independent of the production reader, and `run` must execute in a separate least-privilege process. Models may propose candidates; they never write canonical Endem bytes, widen authority, or declare acceptance.

## Artifact vocabulary

- **Endem** — one minimal goal unit.
- **Weave** — a resolved closure of two or more Endems and their pinned dependencies; one self-contained Endem needs no Weave.
- **Frame** — the immutable loaded state for one run; it is not a file format.
- **Witness** — scoped evidence and decisions from a run; it is evidence, not a claim of mathematical proof.

The design borrows durable ideas from compiler and binary toolchains—deterministic writing, linking, relocation-like reference binding, independent inspection, loading, stripping, and integrity checks—without copying their machine-instruction ontology or their application count.

## Project portal and status

The canonical public entry point is **[noemion.github.io](https://noemion.github.io/)**. It keeps accepted decisions, proposed mechanisms, and verified implementation evidence visibly separate.

> **Current stage:** accepted vocabulary, propositional projection semantics, and application topology; specification and secure core design are in progress. No stable wire format, ABI, production command, or release package exists yet.

<p align="center"><sub>© 2026 Noemion. All rights reserved. Noemion and its associated marks are not licensed for reuse.</sub></p>
