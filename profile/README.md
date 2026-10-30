<div align="center">

# Open Intent Schema

**What was asked, what was built, and the proof in between.**

An open, vendor-neutral data standard that links requirements to independent evidence<br>
that software does what was asked, even when AI agents built it.

[Website](https://openintentschema.io) ·
[Getting started](https://openintentschema.io/getting-started/) ·
[Specification](https://github.com/openintentschema/openintentschema/tree/main/specification) ·
[Open RFCs](https://github.com/openintentschema/openintentschema/issues?q=label%3Arfc)

</div>

---

### What is OIS?

Think of it as an **SBOM for requirements**: an SBOM lists what software contains; OIS states what it must do and how that is proven.

OIS records intents and their acceptance criteria, the artifacts produced, who or what produced them and with which context, the evidence from test runs, the decisions at quality gates, and the findings when something goes wrong. A signed **Quality Passport** bundles all of it for a release.

> **Status:** Specification v0.1, working draft, open for discussion with design partners. Any part may change before 1.0.

### Repositories

| Repository | What's inside | Install |
|---|---|---|
| [**openintentschema**](https://github.com/openintentschema/openintentschema) | Specification, JSON Schema, conformance fixtures, profiles, website | – |
| [**tools**](https://github.com/openintentschema/tools) | Reference CLI `ois`: validator, test report adapters, passports, signing (Python) | `pip install ois-tools` |
| [**tools-js**](https://github.com/openintentschema/tools-js) | Second validator implementation (Node.js) | `npm install ois-tools` |

The Python tools are also available as a container image for projects in any language: `ghcr.io/openintentschema/ois-tools`

### Try it in 15 minutes

Turn the JUnit XML of an existing pipeline into OIS records: **[Getting started →](https://openintentschema.io/getting-started/)**

### Conformance levels

**Level 1 Observe** – emit records for existing outputs ·
**Level 2 Intent-aware** – read intents, record complete context ·
**Level 3 Attested** – signed bundles and passports, verifiable identity

### Built on open standards

Gherkin · EARS · in-toto · DSSE · Sigstore · SLSA · CloudEvents · W3C Trace Context · JSON Schema 2020-12 · RFC 8785

### Get involved

- Changes to the data model, rules, schema or passport format start as an [RFC issue](https://github.com/openintentschema/openintentschema/issues?q=label%3Arfc)
- Read the [contributing guide](https://github.com/openintentschema/openintentschema/blob/main/.github/CONTRIBUTING.md) and how decisions are made in [GOVERNANCE.md](https://github.com/openintentschema/openintentschema/blob/main/GOVERNANCE.md)
- Interested in becoming a design partner? Write to the editors at [editors@openintentschema.io](mailto:editors@openintentschema.io)
- Security issues: [SECURITY.md](https://github.com/openintentschema/openintentschema/blob/main/.github/SECURITY.md)

<sub>Schema, code and fixtures: Apache-2.0 · Specification text: CC BY 4.0</sub>
