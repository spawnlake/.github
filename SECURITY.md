# Security Policy

We take the security of SpawnLake and the `boid-*` catalog seriously.

## Reporting a vulnerability

**Please do NOT report security vulnerabilities through public GitHub issues,
discussions, or pull requests.**

Instead, email **security@spawnlake.com** with:

- A description of the issue and its impact.
- Steps to reproduce (PoC welcome).
- The affected repository, version, commit, or container tag.
- Any suggested mitigation.

You should receive an acknowledgement within **48 hours**. We will keep you
informed of progress toward a fix and may ask follow-up questions.

If you prefer encrypted communication, request our PGP key in your initial
email and we will reply with it.

## Scope

This policy covers all repositories under the `spawnlake` GitHub
organization, including:

- `spawnlake-*` — control plane, data plane, gateway, console, CLI, SDKs, MCP.
- `boid-*` — published container images and their build configuration.
- `spawnlake-docs`.

## Out of scope

- Findings against third-party upstreams we package (report those upstream;
  let us know so we can patch our images).
- Social-engineering, physical attacks, or denial-of-service via volumetric
  traffic.

## Disclosure

We follow coordinated disclosure. Once a fix is available we will credit
reporters who wish to be credited in the release notes and security advisory.
