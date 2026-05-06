# RTS Minimal Runtime

This repository is a minimal proof-of-runtime for RTS.

It proves the smallest reconstructable RTS flow:

```text
intent.md -> spec.yaml -> execution_record.jsonl -> manifest.sha256 -> reconstruction.md
```

The purpose is to show that a human intent can be captured, converted into a minimal spec, recorded as an execution event, verified with a manifest, and reconstructed afterward.

Out of scope:

- UI
- Cloud execution
- Multi-agent automation
- Product expansion
- Full RTS-AGE integration
