## YoMemo Prompts Library

Version: **v0.0.0**

This repository contains reusable prompts and protocols for YoMemo and its integrations
(MCP servers, official client, IDE agents, etc.).

### Layout

- `system-v0.0.0.txt`  
  Advanced Memory Engine & Ontology Protocol (initial public snapshot).  
  Canonical spec for ELAP metrics, AMP/PRT triggers, and `save_memory` / `load_memories`
  behavior.

Planned structure as this library grows:

- `protocols/` – core, low-level protocols (few and stable).
- `scenarios/` – scenario-specific prompt templates built on the protocols.
- `recipes/` – concrete examples and one-off setups.

### Versioning

- The **library version** starts at `v0.0.0` for this initial snapshot.
- Individual protocols (like future protocol revisions) may have their own internal version labels.

### GitHub

- GitHub repo: `https://github.com/yomemoai/yomemo-prompts`  
- Direct link to the initial protocol file:  
  `https://github.com/yomemoai/yomemo-prompts/blob/main/system-v0.0.0.txt`

