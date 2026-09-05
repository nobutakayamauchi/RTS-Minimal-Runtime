# AGENTS.md

## Status
**COLD / MINIMAL PROOF / EXPLICIT REFERENCE ONLY**

RTS-Minimal-Runtime is a deliberately tiny proof of reconstructable RTS flow. It is not the active full RTS architecture and is not a general runtime/product expansion target.

## Load rule
Open this repository only when the task explicitly needs the minimal proof flow:

```text
intent.md -> spec.yaml -> execution_record.jsonl -> manifest.sha256 -> reconstruction.md
```

Do not include it in ordinary cross-repository implementation discovery.

## Scope
Keep the proof minimal. UI, cloud execution, multi-agent automation, product expansion, and full RTS-AGE integration are out of scope unless a new explicit decision changes the proof boundary.

## Context budget
The repository is small; still load only the proof files required for the active verification. Do not pull in original RTS history or broader ecosystem context unless the question explicitly requires comparison.

## Stop condition
If the task asks for a production/full runtime rather than this minimal proof, stop and route to the relevant current canonical repository.