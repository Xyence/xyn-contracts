# xyn-contracts (starter)

This folder contains shared contracts consumed by:
- `xyence-web` (Django internal APIs, Studio client)
- `xyn-seed` (ReleaseSpec/RuntimeSpec plan/apply/status)

## Conventions
- JSON Schema Draft 2020-12
- `additionalProperties: false` by default (fail-closed)
- Never store raw secrets in specs. Use `secretRefs` / `valueFromSecret` references.

## Files
- `schemas/ReleaseSpec.schema.json`
- `schemas/RuntimeSpec.schema.json`
- `schemas/ReleasePlan.schema.json`
- `schemas/ReleaseStatus.schema.json`
- `schemas/Operation.schema.json`
# xyn-contracts
