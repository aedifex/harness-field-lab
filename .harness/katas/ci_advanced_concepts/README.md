# CI Advanced Concepts

This folder contains Harness CI kata pipelines focused on advanced CI patterns and platform behaviors.

## Current Kata

### Advanced Concepts - Caching JSON Blobs

Demonstrates data sharing between CI stages by writing JSON output in one stage and making it available to a later stage.

## Use Case

A common CI pattern is to generate structured data during one part of a build and reuse it later in the pipeline.

Examples:

- build metadata
- test summaries
- scan results
- generated config
- deployment context
- artifact manifests

This kata uses cached JSON blobs to make that pattern visible and easy to test.

## Structure

```text
ci_advanced_concepts/
├── README.md
└── Advanced_Concepts_Caching_JSON_blobs.yaml
```

## Notes

Each kata should be small, self-contained, and easy to run from Harness Pipeline Studio.
