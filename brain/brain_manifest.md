---
id: brain_manifest
version: 1.0.0
module: manifest
load: always
priority: critical
---

# ST AI Brain Manifest

## Purpose

This file is the entry point of the ST AI Brain.

Every AI workflow (n8n, API, or future applications) should load this file first before loading any other module.

---

## Brain Structure

1. constitution/
2. philosophy/
3. psychology/
4. reasoning/
5. algorithms/
6. modules/
7. memory/
8. prompts/

---

## Loading Rule

The AI should:

1. Read this manifest.
2. Load every module listed above.
3. Build the complete ST AI Brain before answering users.
4. Never skip the Constitution module.
