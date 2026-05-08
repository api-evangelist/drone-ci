# Drone (drone-ci)

Drone is a container-native open-source continuous delivery platform owned by Harness. Pipelines are defined in YAML and executed in Docker containers. The Drone server exposes a REST API used by the Drone CLI, dashboard and SDKs. Drone Enterprise has been consolidated into Harness Continuous Integration.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Drone Server REST** — `http://<drone-server>:8080/api` — Bearer-token auth. Resources: builds, repos, cron, secrets, users, templates, logs, queue. [Docs](https://docs.drone.io/api/).

## OpenAPI
Drone does not currently publish a public OpenAPI/Swagger document for the server REST API; pipeline did not retrieve a spec into `openapi/`. SDKs (Go, Node, Python) cover the surface.

## Tags
DevOps, CI/CD, Container-Native, Open Source, YAML, Harness

## Common Properties
- [Website](https://www.drone.io/) · [Docs](https://docs.drone.io/) · [Source](https://github.com/harness/drone)
- [Owner: Harness CI](https://www.harness.io/products/continuous-integration)
- [Plans](plans/drone-ci-plans-pricing.yml) — partially reconciled (editions; commercial pricing rolled into Harness)
- [Rate Limits](rate-limits/drone-ci-rate-limits.yml) — operational knobs documented; no managed quota
- [FinOps](finops/drone-ci-finops.yml) — reconciled, FOCUS-aligned

## Editions (reconciled)
- **Drone Open Source** — Apache 2.0; free.
- **Harness Continuous Integration** — commercial successor to Drone Enterprise; sold via Harness sales.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
