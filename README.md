# RootCause-AI — OTel First-Divergence Reproduction

Reproducible case of a silent state mutation across an agent handoff.

The case demonstrates a required field (`metrics.schema_version`) disappearing during PlannerAgent execution while the execution remains successful from the span-status perspective.

This repository distinguishes native OTel identifiers from application-level and synthetic/canonical identifiers.

See `trace.json` and `state-diff.json` for the machine-readable reproduction artifacts.
