## 0.5.0
### Added
- /jobs/pipeline endpoint (create background pipeline job)
- /jobs/{job_id} endpoint (job status and progress)
- /jobs/{job_id}/cancel endpoint (cancel background job)
- /analytics/positions (compute and save positions)
- /analytics/{match_id}/positions (get cached positions)
- /analytics/possession (compute and save possession)
- /analytics/{match_id}/possession (get cached possession)
- /analytics/control_zones (compute and save control zones)
- /analytics/{match_id}/control_zones (get cached control zones)
- /analytics/momentum (compute and save momentum)
- /analytics/{match_id}/momentum (get cached momentum)
- Update OpenAPI spec to match new API endpoints

## 0.4.0
- Add Track schema
- Add POST /teams/assign (compute & persist team assignments)
- Add GET /matches/{match_id}/tracks (read assignments as array of Track)