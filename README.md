# codex-continuity-marketplace

Codex marketplace source for the `codex-continuity` plugin.

## Install

```text
/plugins marketplace add hj01857655/codex-continuity-marketplace
/plugin install codex-continuity@codex-continuity-marketplace
```

The marketplace entry points to the plugin implementation repository:

```text
https://github.com/hj01857655/codex-continuity
```

`codex-continuity` now stays intentionally thin: Codex host runtime remains the source of truth for `additional_context` role handling, deduplication, and truncation, while the plugin focuses on session retrieval, digesting, and note-settling workflow.
