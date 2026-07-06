# RTS-Minimal-Runtime Status

Status: ACTIVE / REFERENCE / MINIMUM ALIVE

RTS-Minimal-Runtime is the minimal reference runtime for RTS-style reconstructability.

Its purpose is to preserve the smallest working proof of a reconstructable execution flow.

It is not a product repository.

It is not RTS-AGE.

It is not a general automation platform.

## Canonical Reference Flow

This repository should preserve the smallest reference path:

```text
intent.md -> spec.yaml -> execution_record.jsonl -> manifest.sha256 -> reconstruction.md
```

This flow is the main value of the repository.

## Current Position

RTS-Minimal-Runtime should remain small, inspectable, and stable.

Allowed by default:

- clarify documentation
- preserve the reference flow
- improve validation notes
- fix broken examples without expanding scope
- add small tests only when they protect the reference flow

Prohibited by default:

- expanding into RTS-AGE
- adding UI features
- adding cloud execution
- adding multi-agent orchestration
- adding external integrations
- turning this into a general workflow runner
- changing the canonical reference flow silently
- merging sales, product, connector, or gateway responsibilities into this repository

## Boundary

This repository proves the minimum.

RTS-AGE can experiment with agentic execution.

RTS-minicompany can operate business workflows.

seminar-compass can develop a product workflow.

RTS-Minimal-Runtime should not absorb those responsibilities.

## Minimum Alive Definition

This repository is considered Minimum Alive when:

1. The minimal reference role is explicit.
2. The canonical flow is preserved.
3. Expansion boundaries are documented.
4. No runtime behavior is changed by the status lock itself.
5. Future changes protect the reference flow rather than expanding the repository.

## Current Decision

Keep this repository.

Treat it as the minimal RTS runtime reference specimen.

Do not expand it unless a separate decision record explicitly promotes a new reference behavior.
