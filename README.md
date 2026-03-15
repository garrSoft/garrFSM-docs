# garrFSM-docs

Public, sanitized documentation mirror for the Garrison FSM project.

## Purpose

This repository exists to publish **safe architectural context** for Garrison FSM without exposing:

- secrets
- credentials
- internal-only operational details
- customer-sensitive data
- private environment configuration

Its main audience is:

- AI tools
- future maintainers
- collaborators
- public-safe architectural reference

## Source of Truth

This repository is **not** the primary authoring location.

Source of truth lives in:

- `garrFSM` for application code, schema, routes, and system context source
- internal infrastructure repositories for private ops and deployment details

This repository receives **sanitized published outputs** from the main project.

## Current Contents

- `docs/systemContext.md` — public-safe system architecture and project context

## Rules

- Keep this repository public-safe
- Do not commit secrets
- Do not commit private hostnames, credentials, or internal access details
- Do not treat this repository as the primary place for hand-edited operational documentation
- Prefer generated or published artifacts from the main source repository

## Intended Role

This repo is a documentation mirror for:

- system architecture
- high-level stack description
- sanitized database and API context
- project continuity for AI-assisted development
