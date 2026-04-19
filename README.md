# Amazon Config (amazon-config)
AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past, enabling assessment, auditing, and evaluation of configurations for compliance and security governance. It records configuration changes continuously, evaluates compliance against rules, and supports automated remediation of noncompliant resources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-config/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Auditing, AWS, Compliance, Configuration Management, Governance, Security

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Config API
The AWS Config API provides 92 operations for managing configuration recording, evaluating resource compliance against rules, querying resource configurations, tracking configuration history, managing conformance packs, configuring remediation, and aggregating configuration data across accounts and regions.

**Human URL:** [https://aws.amazon.com/config/](https://aws.amazon.com/config/)

#### Tags:

 - Auditing, AWS, Compliance, Configuration Management, Governance

#### Properties

- [Documentation](https://docs.aws.amazon.com/config/latest/developerguide/)
- [OpenAPI](openapi/amazon-config-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/config/latest/APIReference/)
- [Pricing](https://aws.amazon.com/config/pricing/)
- [GettingStarted](https://aws.amazon.com/config/getting-started/)
- [FAQ](https://aws.amazon.com/config/faq/)
- [JSONSchema](json-schema/config-config-rule-schema.json)
- [JSONStructure](json-structure/config-config-rule-structure.json)
- [JSON-LD](json-ld/amazon-config-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/config/)
- [Documentation](https://docs.aws.amazon.com/config/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/mt/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/config/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-config)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Configuration Recording | Continuously record configuration changes to all supported AWS resources in your account with detailed configuration items. |
| Config Rules | Evaluate AWS resource configurations against desired settings using AWS-managed or custom Lambda-based rules. |
| Conformance Packs | Deploy collections of Config rules and remediation actions as a single unit across an AWS Organization. |
| Configuration History | View detailed configuration history for any AWS resource including who changed what and when. |
| Resource Inventory | Maintain a complete inventory of all AWS resources in your account with current and past configurations. |
| Automated Remediation | Automatically remediate noncompliant resources using SSM Automation documents triggered by Config rules. |
| Multi-Account Aggregation | Aggregate configuration and compliance data from multiple accounts and regions into a single view. |
| Advanced Query | Use SQL-like queries to search across resource configurations and compliance states. |

## Use Cases

| Name | Description |
|------|-------------|
| Security and Compliance Auditing | Continuously audit AWS resource configurations against security benchmarks like CIS, PCI DSS, and HIPAA. |
| Change Management | Track who changed what configuration on which resource and when for change management and troubleshooting. |
| Resource Inventory | Maintain an always-current inventory of all AWS resources for asset management and CMDB purposes. |
| Drift Detection | Detect configuration drift from approved baselines and trigger alerts or automated remediation. |
| Incident Investigation | Reconstruct the configuration state of resources at any point in time to aid incident investigation. |
| Governance at Scale | Enforce organization-wide governance policies using conformance packs deployed across all accounts. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CloudTrail | Correlate Config configuration items with CloudTrail API activity to understand who made changes. |
| AWS Security Hub | Send Config compliance findings to Security Hub for centralized security posture management. |
| Amazon S3 | Deliver configuration snapshots and history to S3 for long-term storage and analysis. |
| Amazon SNS | Send notifications for compliance changes and configuration changes via SNS topics. |
| AWS Systems Manager | Use SSM Automation documents as remediation targets for Config rules. |
| AWS Organizations | Deploy Config rules and conformance packs across entire AWS Organizations for governance at scale. |
| AWS Lambda | Create custom Config rules using Lambda functions for organization-specific compliance requirements. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Config OpenAPI](openapi/amazon-config-openapi.yml)

### JSON Schema

479 schema files extracted from the OpenAPI specification covering all request/response models.

### JSON Structure

479 JSON Structure files converted from JSON Schema using the json-structure.org specification.

### JSON-LD

- [Amazon Config Context](json-ld/amazon-config-context.jsonld) — 262 types, 327 properties

### Examples

479 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Config API](capabilities/shared/config.yaml) — 11 operations for compliance rules, resource inventory, and remediation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Config Compliance and Governance](capabilities/compliance-governance.yaml) | Amazon Config API | 10 | Security Engineer, Compliance Officer |

## Vocabulary

- [Amazon Config Vocabulary](vocabulary/amazon-config-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Config Spectral Rules](rules/amazon-config-spectral-rules.yml) — 23 rules across 13 categories enforcing Amazon Config API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
