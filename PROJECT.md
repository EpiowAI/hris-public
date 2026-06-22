# hris-public

This repository is an incubating placeholder for a public HRIS-related project.
It has no committed product implementation, production service, package, API,
or deploy path yet.

## Lifecycle

- State: `incubating`
- Layer: `other`
- Machine manifest: [`.doctrine/project.json`](./.doctrine/project.json)

## Goals

- Preserve a doctrine-compatible entry point so future agents can discover the
  central standards before initializing the project.
- Require the owning project to define concrete goals, boundaries, public
  surfaces, and delivery proof before production work starts.

## Non-Goals

- Do not treat this placeholder as a production HRIS product.
- Do not add data models, integrations, deployment paths, or commercial
  commitments without a project-specific ADR or manifest update.

## Boundary

This repository currently owns only its initialization metadata. It does not
own HRIS domain behavior, customer data processing, auth, billing, deployment,
or public API behavior until those facts are explicitly declared here and in
`.doctrine/project.json`.

## Public Surfaces

- Documentation: `AGENTS.md`, `PROJECT.md`, `.doctrine/project.json`

## Delivery

No CI or deployment is defined. Production proof is not applicable until the
repository contains implementation or release artifacts.

## Commercial Direction

Not applicable. No pricing, packaging, paid entitlement, or commercial
experiment is declared for this placeholder.
