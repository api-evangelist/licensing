# Licensing (licensing)
An index and topic collection covering software licensing APIs across two intersecting domains: open-source license metadata and code-license detection (SPDX, OSI license list, ChooseALicense, FOSSology, ScanCode, ClearlyDefined, the GitHub License API, and Software Composition Analysis tooling from Snyk, Sonatype, Synopsys Black Duck, JFrog, Veracode, and Anchore) and commercial software licensing, entitlement, and activation APIs (Amazon License Manager, Flexera FlexNet Operations, Cryptlex, Keygen, LicenseSpring, Zentitle by Nalpeiron, Sentinel by Thales, Reprise, OpenLM, and SaaS license management platforms such as Snow Software, SoftwareOne, Trelica, CloudEagle.ai, Sastrify, Spendflo, CloudNuro, Cleanshelf, Corma, Certero, and Binadox).

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - License, Licensing, SPDX, Open Source License, License Compliance, Software Composition Analysis, Entitlement, Software Licensing, License Management, SaaS License Management

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - OSS License Schema](https://raw.githubusercontent.com/api-evangelist/licensing/refs/heads/main/json-schema/licensing-oss-license-schema.json)
- [JSONSchema - License Entitlement Schema](https://raw.githubusercontent.com/api-evangelist/licensing/refs/heads/main/json-schema/licensing-license-entitlement-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/licensing/refs/heads/main/json-ld/licensing-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/licensing/refs/heads/main/vocabulary/licensing-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Open Source License Metadata | Authoritative catalogs and identifiers for open-source licenses, including the SPDX License List, OSI-approved licenses, and ChooseALicense.com, exposed via APIs so tools can resolve canonical license identifiers, texts, and obligations. |
| Source Code License Detection | Scanners such as ScanCode, FOSSology, and ClearlyDefined inspect source trees, package manifests, and binary artifacts to detect declared and inferred licenses across millions of files and report them in SPDX or similar formats. |
| Software Composition Analysis | SCA platforms like Snyk, Sonatype, Synopsys Black Duck, JFrog Xray, Veracode SCA, and Anchore inventory open-source dependencies, attribute licenses to each component, and flag policy violations across build pipelines. |
| SBOM and License Attribution | Software Bill of Materials tooling generates SPDX or CycloneDX documents that include per-component license declarations, enabling downstream attribution, NOTICE file generation, and regulatory disclosure. |
| Commercial License Activation and Entitlement | Entitlement platforms such as Cryptlex, Keygen, LicenseSpring, Zentitle by Nalpeiron, Sentinel by Thales, Reprise, and Flexera FlexNet Operations issue, activate, validate, and revoke license keys for commercial software. |
| License Metering and Floating Licenses | OpenLM, FlexNet, and Reprise track concurrent usage of floating and named-user licenses for engineering and design software, exposing utilization, denial, and check-out events through APIs. |
| SaaS License Management | SaaS management platforms like Snow Software, SoftwareOne, Trelica, CloudEagle.ai, Sastrify, Spendflo, CloudNuro, Cleanshelf, Corma, Certero, and Binadox discover SaaS subscriptions, reconcile seat usage, and reclaim unused licenses. |
| Marketplace Entitlement and Co-Sell | Cloud marketplace and metering APIs from Amazon License Manager and Suger let ISVs grant, meter, and revoke buyer entitlements purchased through AWS, Azure, and GCP marketplaces. |

## Use Cases

| Name | Description |
|------|-------------|
| Open Source License Compliance | Engineering and legal teams scan repositories and build artifacts with FOSSology, ScanCode, Snyk, or Synopsys Black Duck to attribute licenses to every dependency and prove compliance with copyleft and attribution obligations. |
| SBOM Generation for Regulated Industries | Vendors generate SPDX or CycloneDX SBOMs that embed license declarations to satisfy U.S. Executive Order 14028, the EU Cyber Resilience Act, and medical-device, automotive, and federal procurement requirements. |
| Commercial License Activation | ISVs ship desktop and embedded software that calls Cryptlex, Keygen, LicenseSpring, or FlexNet APIs at startup to activate, validate, and periodically re-check license entitlements against a hardware fingerprint. |
| Floating License Pools for Engineering Tools | CAD, EDA, and scientific computing teams meter concurrent usage of expensive seats through OpenLM, FlexNet, and Reprise license servers, exposing real-time utilization through APIs to optimize seat counts. |
| SaaS Spend and License Optimization | IT and finance teams use SaaS management platforms to discover shadow SaaS, reconcile seats against active users, and reclaim or right-size licenses to cut software spend. |
| Cloud Marketplace Entitlement Provisioning | ISVs listed on AWS, Azure, and GCP marketplaces use Amazon License Manager and Suger to grant access to customers who purchase through the marketplace and to meter consumption-based billing. |
| Repository License Surfacing | Code hosts like GitHub expose detected license metadata via the GitHub License API so downstream tooling can resolve a project's license without re-scanning source. |
| License Policy Enforcement in CI | SCA gates in CI block builds that introduce dependencies under restricted licenses (AGPL, SSPL) using policies defined in Snyk, Sonatype, Synopsys, JFrog Xray, or Anchore. |

## Integrations

| Name | Description |
|------|-------------|
| SPDX | The SPDX License List and SBOM specification from the Linux Foundation, providing canonical identifiers and machine-readable license metadata. |
| FOSSology | Open-source license compliance scanner from the Linux Foundation that detects licenses, copyrights, and obligations across source trees. |
| ScanCode Toolkit | Open-source license, copyright, and package detection toolkit used as the core engine in ClearlyDefined and many SCA platforms. |
| ClearlyDefined | Open Source Initiative project that aggregates curated license and copyright data for open-source components and exposes it via API. |
| Snyk | Developer-first security and SCA platform that inventories open-source dependencies and attributes licenses, flagging policy violations in pull requests. |
| Synopsys Black Duck | Enterprise SCA platform for open-source license compliance, vulnerability management, and policy enforcement across software supply chains. |
| Sonatype Lifecycle | SCA and policy engine from Sonatype enforcing license and security policies against open-source components in repositories and build pipelines. |
| Flexera FlexNet Operations | Commercial license fulfillment and entitlement platform used by ISVs to issue, deliver, and manage software licenses for on-premises and embedded software. |
| Keygen | Developer-focused commercial software licensing and distribution API offering activation, validation, and entitlement for desktop, embedded, and IoT software. |
| Cryptlex | Cloud-based commercial software licensing API for activation, offline licensing, floating licenses, and machine fingerprinting. |
| LicenseSpring | Software licensing platform for ISVs providing online and offline activation, license servers, and entitlement management. |
| Zentitle by Nalpeiron | Cloud-based software monetization and entitlement platform issuing perpetual, subscription, and consumption-based licenses. |
| Sentinel by Thales | Enterprise-grade software licensing and entitlement platform widely used in industrial, medical, and embedded software. |
| OpenLM | License usage monitoring and reporting platform for floating engineering and CAD licenses across FlexNet, Reprise, DSLS, and other license servers. |
| Amazon License Manager | AWS service for managing software licenses from vendors such as Microsoft, SAP, Oracle, and IBM across AWS and on-premises infrastructure. |
| Snow Software | IT asset and SaaS management platform (now part of Flexera) providing visibility into software entitlements and consumption. |
| GitHub License API | GitHub REST API endpoints that return the detected SPDX license for a repository and serve canonical license texts for choosing a license. |

## Artifacts

Machine-readable artifacts describing licensing entities, vocabularies, and example payloads.

### JSON Schema

- [OSS License Schema](json-schema/licensing-oss-license-schema.json)
- [License Entitlement Schema](json-schema/licensing-license-entitlement-schema.json)

### JSON Structure

- [OSS License Structure](json-structure/licensing-oss-license-structure.json)
- [License Entitlement Structure](json-structure/licensing-license-entitlement-structure.json)

### JSON-LD

- [Licensing Context](json-ld/licensing-context.jsonld)

## Vocabulary

- [Licensing Vocabulary](vocabulary/licensing-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across open-source license metadata, code-license detection, SBOM/SCA tooling, commercial entitlement, and SaaS license management.

## Examples

- [OSS License Example](examples/licensing-oss-license-example.json)
- [License Entitlement Example](examples/licensing-license-entitlement-example.json)

## Network

This index references the following licensing-related provider repositories:

- [Amazon License Manager](https://github.com/api-evangelist/amazon-license-manager)
- [Anchore](https://github.com/api-evangelist/anchore)
- [Binadox](https://github.com/api-evangelist/binadox)
- [Certero](https://github.com/api-evangelist/certero)
- [Cleanshelf](https://github.com/api-evangelist/cleanshelf)
- [CloudEagle.ai](https://github.com/api-evangelist/cloudeagle)
- [CloudNuro](https://github.com/api-evangelist/cloudnuro)
- [Corma](https://github.com/api-evangelist/corma)
- [Flexera](https://github.com/api-evangelist/flexera)
- [FOSSology](https://github.com/api-evangelist/fossology)
- [GitHub](https://github.com/api-evangelist/github)
- [JFrog](https://github.com/api-evangelist/jfrog)
- [LICENSE.md](https://github.com/api-evangelist/license-md)
- [Manifest Cyber](https://github.com/api-evangelist/manifest-cyber)
- [Mendix](https://github.com/api-evangelist/mendix)
- [OpenChain](https://github.com/api-evangelist/openchain)
- [OpenSSF](https://github.com/api-evangelist/openssf)
- [Sastrify](https://github.com/api-evangelist/sastrify)
- [Snow Software](https://github.com/api-evangelist/snow-software)
- [Snyk](https://github.com/api-evangelist/snyk)
- [SoftwareOne](https://github.com/api-evangelist/softwareone)
- [Sonatype](https://github.com/api-evangelist/sonatype)
- [SPDX](https://github.com/api-evangelist/spdx)
- [Spendflo](https://github.com/api-evangelist/spendflo)
- [Suger](https://github.com/api-evangelist/suger)
- [Synopsys](https://github.com/api-evangelist/synopsys)
- [Trelica](https://github.com/api-evangelist/trelica)
- [Veracode](https://github.com/api-evangelist/veracode)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
