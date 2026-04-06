# Common Cloud Controls

Common Cloud Controls (CCC) is a FINOS project that provides a vendor-neutral, open-source catalog of security controls for common cloud services. Each control maps a risk to a concrete, testable requirement — making it possible to automate compliance assessments rather than answer the same questionnaire by hand.

## Repositories

| Repo | Description |
|------|-------------|
| [capability-catalogs](https://github.com/common-cloud-controls/capability-catalogs) | Capabilities for each cloud service category |
| [threat-catalogs](https://github.com/common-cloud-controls/threat-catalogs) | Threats for each cloud service category |
| [control-catalogs](https://github.com/common-cloud-controls/control-catalogs) | Security controls mapped to capabilities and threats |
| [core-catalog](https://github.com/common-cloud-controls/core-catalog) | Cross-cutting capabilities, threats, and controls that underpin all service catalogs |
| [delivery-toolkit](https://github.com/common-cloud-controls/delivery-toolkit) | CLI and GitHub Action for building and publishing catalog artifacts |
| [common-cloud-controls.github.io](https://github.com/common-cloud-controls/common-cloud-controls.github.io) | Public website — catalog content is published here on release |

## How it works

Catalog authors write YAML. On each release, the delivery toolkit validates and publishes structured artifacts to the website. Controls are expressed in a machine-readable schema aligned with the [Gemara GRC Engineering Model](https://gemara.openssf.org), so they connect directly to evaluation tooling and enforcement pipelines.

The [CNCF TAG Security Automated Governance Maturity Model](https://tag-security.cncf.io/community/resources/automated-governance-maturity-model/) describes the problem space CCC addresses: organizations that adopt CCC controls can advance their governance maturity because those controls carry built-in assessment requirements that feed automated policy evaluation.

## Contributing

CCC is developed under the [FINOS](https://www.finos.org) umbrella. See the contributing guide in the relevant catalog repository to get started.
