<p align="center">
  <img src="https://raw.githubusercontent.com/openartifact/openartifact/main/docs/logo.png" alt="OpenArtifact logo" width="96">
</p>

<h1 align="center">OpenArtifact</h1>

<p align="center">
  <b>Self-hosted artifact repository for 16 package formats.</b><br>
  One Go binary, embedded web UI, PostgreSQL. AGPL-3.0-or-later.
</p>

<p align="center">
  <a href="https://github.com/openartifact/openartifact/releases/latest"><img src="https://img.shields.io/github/v/release/openartifact/openartifact?label=release" alt="Latest release"></a>
  <a href="https://github.com/openartifact/openartifact/actions/workflows/ci.yml"><img src="https://github.com/openartifact/openartifact/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://artifacthub.io/packages/search?repo=openartifact"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/openartifact" alt="Artifact Hub"></a>
  <a href="https://github.com/openartifact/openartifact/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-blue" alt="License"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/openartifact/openartifact/main/docs/screenshots/dashboard.png" alt="OpenArtifact dashboard" width="820">
</p>

npm · PyPI · Maven · Docker/OCI · Helm · Debian · RPM · Go · Cargo · NuGet · RubyGems · Conda · Conan · Ivy · sbt · raw

- Hosted repositories behind one URL scheme and one permission model
- RBAC with scoped tokens, OIDC and SAML SSO
- Signed APT and RPM metadata
- Vulnerability (OSV, Trivy, Grype), license and secret scans; CycloneDX/SPDX SBOMs
- Storage: filesystem, S3, GCS, Azure, OCI
- Webhooks, cleanup policies, quotas, audit log, backups, Prometheus metrics
- MCP endpoint for AI agents

## Repositories

| | |
|---|---|
| [openartifact](https://github.com/openartifact/openartifact) | Server, web UI, `oa` CLI. Issues and pull requests go here. |
| [helm-charts](https://github.com/openartifact/helm-charts) | Helm chart: `oci://ghcr.io/openartifact/charts/openartifact` |

## Get started

```sh
docker pull ghcr.io/openartifact/openartifact:latest
helm install openartifact oci://ghcr.io/openartifact/charts/openartifact
```

Docker Compose quickstart and configuration: [README](https://github.com/openartifact/openartifact#quickstart-docker-compose).

Contributing: [CONTRIBUTING.md](https://github.com/openartifact/.github/blob/main/CONTRIBUTING.md) · Security: [SECURITY.md](https://github.com/openartifact/.github/blob/main/SECURITY.md)
