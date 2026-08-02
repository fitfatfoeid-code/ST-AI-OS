---
id: loader_config
version: 1.0.0
module: loader
---

load_order:

  - brain/constitution/core.md
  - brain/constitution/identity.md
  - brain/constitution/mission.md
  - brain/constitution/values.md
  - brain/constitution/rules.md
  - brain/constitution/limitations.md
  - brain/constitution/communication.md

loading:

  strategy: sequential

  stop_if_missing: true

  merge: true

  preserve_order: true

output:

  merged_context
