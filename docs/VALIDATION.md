# RTS Minimal Runtime Validation

Validation for this repository has two checks:

1. Manifest verification
2. Reconstruction review

## Manifest verification

Run:

```sh
sha256sum -c manifest.sha256
```

Expected result: every listed file should return `OK`.

## Reconstruction review

Use this manual checklist to reconstruct the run:

- `intent.md` explains why the run exists.
- `spec.yaml` defines the task.
- `execution_record.jsonl` records the event.
- `manifest.sha256` verifies file integrity.
- `reconstruction.md` explains what happened.

This repository intentionally has no app code, no dependencies, and no cloud execution.
