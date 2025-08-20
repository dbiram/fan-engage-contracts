# Fan Engage — Contracts

Source of truth for API and data contracts used across the stack.

## Contents
- `openapi.yaml` – HTTP interface for `fan-engage-api` (FastAPI)
- `schemas/` – JSON Schemas for persisted artifacts (e.g., Event, Detection)

## Why a separate repo?
Versioned contracts let frontend, API, workers, and ML iterate independently.
Pin by tag (`v0.x`) to avoid breaking changes.

## Versioning
- Follow **semver**:
  - `MAJOR`: breaking field/route changes
  - `MINOR`: new endpoints/fields (backwards compatible)
  - `PATCH`: docs/typos

## Release
Tag and push:
```bash
git tag v0.1.0
git push origin v0.1.0
```
