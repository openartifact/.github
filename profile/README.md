<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://openartifact.github.io/brand/openartifact-horizontal-color-dark.svg">
    <img src="https://openartifact.github.io/brand/openartifact-horizontal-color.svg" alt="OpenArtifact" width="360">
  </picture>
</p>

<p align="center">
  <b>Self-hosted artifact repository for many package formats.</b><br>
  One Go binary, embedded web UI, PostgreSQL. Free software under the AGPL-3.0-or-later.
</p>

<p align="center">
  <a href="https://github.com/openartifact/openartifact/releases/latest"><img src="https://img.shields.io/github/v/release/openartifact/openartifact?label=release" alt="Latest release"></a>
  <a href="https://github.com/openartifact/openartifact/actions/workflows/ci.yml"><img src="https://github.com/openartifact/openartifact/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://artifacthub.io/packages/search?repo=openartifact"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/openartifact" alt="Artifact Hub"></a>
  <a href="https://github.com/openartifact/openartifact/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0--or--later-blue" alt="License"></a>
  <a href="https://api.reuse.software/info/github.com/openartifact/openartifact"><img src="https://api.reuse.software/badge/github.com/openartifact/openartifact" alt="REUSE"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/openartifact/openartifact/main/docs/assets/screenshots/dashboard.png" alt="OpenArtifact dashboard" width="820">
</p>

npm · PyPI · Maven · Docker/OCI · Helm · Debian · RPM · Go · Cargo · NuGet · RubyGems · Conda · Conan · Ivy · sbt · raw

- Hosted, proxy and group repositories behind one URL scheme and one permission model
- Projects; RBAC with scoped tokens, OIDC and SAML SSO
- Release bundles with promotion pipelines
- Federation between instances; blob replication, rebuild from storage and a disaster recovery runbook
- Declarative configuration from YAML with `oa apply`
- Signed APT and RPM metadata; vulnerability (OSV, Trivy, Grype), license and secret scans; CycloneDX/SPDX SBOMs
- Storage: filesystem, S3, GCS, Azure, OCI
- Webhooks, cleanup policies, quotas, audit log, backups, Prometheus metrics, OpenTelemetry
- White-label branding; MCP endpoint for AI agents
- Fuzzing with ClusterFuzzLite; signed releases with SBOM and build provenance

## Repositories

| | |
|---|---|
| [openartifact](https://github.com/openartifact/openartifact) | Server, web UI, `oa` CLI. Issues and pull requests go here. |
| [helm-charts](https://github.com/openartifact/helm-charts) | Helm chart: `oci://ghcr.io/openartifact/charts/openartifact` |
| [openartifact.github.io](https://github.com/openartifact/openartifact.github.io) | Website and versioned documentation |
| [brand](https://github.com/openartifact/brand) | Logos, colours, type and usage guide (CC-BY-SA-4.0) |
| [openartifact-plugin](https://github.com/openartifact/openartifact-plugin) | Jenkins plugin: upload artifacts, create bundles, promote releases, build badges |
| [drone-openartifact](https://github.com/openartifact/drone-openartifact) | Drone and Woodpecker plugin: upload artifacts and promote releases |
| [saml](https://github.com/openartifact/saml) | Fork of crewjam/saml used by the server: large signed assertion fix for goxmldsig 1.6 |

## Get started

```sh
docker pull ghcr.io/openartifact/openartifact:latest
helm install openartifact oci://ghcr.io/openartifact/charts/openartifact
```

The `oa` CLI is on the [releases page](https://github.com/openartifact/openartifact/releases/latest) for Linux, macOS and Windows (amd64, arm64):

```sh
curl -fsSL https://github.com/openartifact/openartifact/releases/latest/download/oa_<version>_linux_amd64.tar.gz | tar -xz oa
```

Docs: [installation](https://openartifact.github.io/latest/getting-started/installation) · [configuration](https://openartifact.github.io/latest/getting-started/configuration) · [CI integrations](https://openartifact.github.io/latest/integrations/ci) · [all docs](https://openartifact.github.io/latest/)

Contributing: [CONTRIBUTING.md](https://github.com/openartifact/.github/blob/main/CONTRIBUTING.md) · Security: [SECURITY.md](https://github.com/openartifact/.github/blob/main/SECURITY.md)
