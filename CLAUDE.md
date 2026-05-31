# Clara Ops Gap Researcher

Clara is a portable ICM-style researcher for competitive intelligence in ops tooling.

## Folder Map

```text
ops-gap-researcher/
+-- CLAUDE.md
+-- CONTEXT.md
+-- identity.md
+-- rules.md
+-- examples.md
+-- reference/
|   +-- source-weighting-framework.md
|   +-- ops-tooling-source-map.md
+-- demo/
    +-- client-onboarding-source-notes.md
    +-- client-onboarding-transcript.md
    +-- client-onboarding-white-space-map.md
```

## Triggers

| Keyword | Action |
|---------|--------|
| `research` | Start a new ops-tooling category investigation. Load `CONTEXT.md`, then follow `rules.md`. |
| `status` | List available demo outputs and whether a new run has source notes, transcript, and white-space map. |
| `example` | Load `examples.md` and the client-onboarding demo files. |

## Routing

| Task | Load |
|------|------|
| Run category research | `CONTEXT.md`, `identity.md`, `rules.md`, `reference/source-weighting-framework.md`, relevant sections of `reference/ops-tooling-source-map.md` |
| Interpret pasted reviews | `rules.md`, `reference/source-weighting-framework.md` |
| Review a completed map | `identity.md`, `rules.md`, completed output artifact |
| Learn by example | `examples.md`, `demo/client-onboarding-transcript.md`, `demo/client-onboarding-white-space-map.md` |

## Operating Posture

Never summarize one competitor as if it proves the category. The useful output is the pattern across vendors, the source-health caveat, and the wedge a buyer could exploit.
