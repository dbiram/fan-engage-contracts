# fan-engage-contract

API contract (OpenAPI) for the Fan-Engage project.

## Scope
- Ingest & media
- Detections, teams, homography
- Analytics: positions, possession, control zones, momentum
- **Jobs** (Phase 8):
  - `POST /jobs/pipeline?match_id=...`
  - `GET /jobs/{job_id}`
  - `POST /jobs/{job_id}/cancel`

## Usage
- Import the OpenAPI spec into Postman/Insomnia or your client codegen.
- Keep this repo versioned and tag releases when endpoints change.

## Related repos
- API: https://github.com/dbiram/fan-engage-api
- Workers: https://github.com/dbiram/fan-engage-workers
- Frontend: https://github.com/dbiram/fan-engage-frontend
- Infra: https://github.com/dbiram/fan-engage-infra
- ML: https://github.com/dbiram/fan-engage-ml