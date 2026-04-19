# Amberflo (amberflo)

Amberflo is a cloud metering, usage-based billing, and AI cost management platform. It provides real-time event ingestion, customer billing automation, AI gateway capabilities, and FinOps visibility for API-driven and AI-powered businesses. The platform supports usage-based, token-based, seat-based, and outcome-based pricing models with automated invoicing and embeddable billing dashboards.

**URL:** [https://www.amberflo.io/](https://www.amberflo.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Usage-Based Billing, Metering, FinOps, AI Cost Management, Billing, Monetization

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

## APIs

### Amberflo Metering API

The Amberflo Metering API provides meter definition management, high-throughput event ingestion, usage queries, raw event queries, and filtering rules. It supports real-time metering for API calls, tokens, and custom events with automatic aggregation and deduplication.

**Human URL:** [https://docs.amberflo.io/reference/ingest-meters](https://docs.amberflo.io/reference/ingest-meters)

#### Tags

 - Metering, Event Ingestion, Usage Tracking

#### Properties

- [Documentation](https://docs.amberflo.io/reference/ingest-meters)
- [APIReference](https://docs.amberflo.io/reference/ingest-meters)
- [OpenAPI](openapi/amberflo-metering-openapi.yaml)

### Amberflo Billing API

The Amberflo Billing API manages customers, pricing plans, invoices, prepaid orders, promotions, commitments, and billing analysis for usage-based monetization workflows.

**Human URL:** [https://docs.amberflo.io/reference/customers](https://docs.amberflo.io/reference/customers)

#### Tags

 - Billing, Customers, Invoicing, Pricing Plans

#### Properties

- [Documentation](https://docs.amberflo.io/reference/customers)
- [APIReference](https://docs.amberflo.io/reference/customers)
- [OpenAPI](openapi/amberflo-billing-openapi.yaml)

### Amberflo Cost Tracking API

The Amberflo Cost Tracking API provides AI and cloud cost management capabilities including cloud provider integrations, business unit management, cost allocation rules, budget management, and cost query analytics.

**Human URL:** [https://docs.amberflo.io/reference/cloud-cost-tracking](https://docs.amberflo.io/reference/cloud-cost-tracking)

#### Tags

 - Cost Tracking, FinOps, Cloud Cost Management, Budgets

#### Properties

- [Documentation](https://docs.amberflo.io/reference/cloud-cost-tracking)
- [APIReference](https://docs.amberflo.io/reference/cloud-cost-tracking)

### Amberflo AI Gateway API

The Amberflo AI Gateway provides a unified API for routing requests to 1,500+ LLM models with intelligent model routing, cost optimization, built-in fallbacks, and MCP server traffic monitoring.

**Human URL:** [https://docs.amberflo.io/docs/ai-gateway](https://docs.amberflo.io/docs/ai-gateway)

#### Tags

 - AI Gateway, LLM, Model Routing, AI Cost Management

#### Properties

- [Documentation](https://docs.amberflo.io/docs/ai-gateway)

## Common Properties

- [Website](https://www.amberflo.io/)
- [Documentation](https://docs.amberflo.io/)
- [DeveloperPortal](https://docs.amberflo.io/)
- [GettingStarted](https://docs.amberflo.io/docs/quick-start)
- [APIReference](https://docs.amberflo.io/reference/)
- [SignUp](https://ui.amberflo.io/cGxnLXNpZ251cA==)
- [Login](https://ui.amberflo.io/login)
- [Pricing](https://www.amberflo.io/pricing)
- [Blog](https://www.amberflo.io/resources/blog)
- [TermsOfService](https://www.amberflo.io/legal/terms-and-condition)
- [PrivacyPolicy](https://www.amberflo.io/legal/privacy-policy)
- [TrustCenter](https://trust.amberflo.io/)
- [GitHubOrganization](https://github.com/amberflo)
- [SDK - Python SDK](https://pypi.org/project/amberflo-metering-python/)
- [SDK - TypeScript SDK](https://github.com/amberflo/metering-typescript)
- [SDK - Go SDK](https://github.com/amberflo/metering-go)

## Features

| Name | Description |
|------|-------------|
| Real-Time Event Ingestion | Ingest millions to billions of high-cardinality usage events in real time with idempotency, deduplication, and automatic aggregation. |
| AI Cost Management | Unified LLM access and control across 1,500+ models with per-unit costs, rollups, budgets, Cost Guards, and margin analysis per customer. |
| AI Gateway and Model Routing | Single API for multiple LLM providers with intelligent cost optimization, automatic retries, fallbacks, and MCP server traffic monitoring. |
| Usage-Based Billing | Flexible billing models including usage-based, token-based, seat-based, fixed fee, and outcome-based pricing with multi-currency support and automated invoicing. |
| Embeddable Billing Dashboards | Customer-facing billing portals and dashboards via a React.js UI Kit with custom domain support and SSO integration. |
| Revenue Operations | Revenue recognition automation, RevRec ledger tracking, tax management, and integrations with Stripe and NetSuite. |
| Budget Management | Spending limits, threshold alerts, Cost Guards, and automated notifications for cloud and AI cost governance. |
| Chargeback and Showback | Chargeback rates, quotes, and invoices for internal cost allocation and showback reporting across business units. |

## Use Cases

| Name | Description |
|------|-------------|
| API Monetization | Meter API usage and automatically bill customers based on calls, tokens, or custom events with flexible pricing models. |
| AI Cost Governance | Track and govern LLM spending across teams and customers with budgets, alerts, and per-customer cost attribution. |
| SaaS Billing Automation | Automate end-to-end billing for SaaS products with usage-based pricing plans, invoicing, and customer portals. |
| Cloud FinOps | Allocate and showback cloud costs to business units and customers using automated cost allocation rules and chargeback workflows. |
| Customer Cost Transparency | Provide customers with real-time visibility into their usage and costs via embedded dashboards and billing portals. |
| Usage Analytics and Reporting | Query and analyze usage data in real time with batch and sparse query modes, raw event queries, and revenue calculation analytics. |

## Integrations

| Name | Description |
|------|-------------|
| Stripe | Native integration with Stripe for payment processing and revenue operations workflows. |
| NetSuite | Integration with NetSuite for revenue recognition and financial reporting. |
| Kong | Official Kong plugin for metering API requests handled by Kong instances and monetizing APIs. |
| AWS SaaS Builder Toolkit | Integration with AWS SaaS Builder Toolkit for SaaS billing and metering best practices on AWS. |
| LiteLLM | Logging callback for LiteLLM to meter LLM usage and monitor AI costs. |
| AWS Lambda | Examples and utilities for metering AWS Lambda function invocations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amberflo Metering API](openapi/amberflo-metering-openapi.yaml)
- [Amberflo Billing API](openapi/amberflo-billing-openapi.yaml)

### JSON Schema

- [metering-api-meter-event-schema.json](json-schema/metering-api-meter-event-schema.json)
- [metering-api-meter-definition-schema.json](json-schema/metering-api-meter-definition-schema.json)
- [metering-api-usage-query-request-schema.json](json-schema/metering-api-usage-query-request-schema.json)
- [metering-api-usage-query-response-schema.json](json-schema/metering-api-usage-query-response-schema.json)
- [billing-api-customer-schema.json](json-schema/billing-api-customer-schema.json)
- [billing-api-invoice-schema.json](json-schema/billing-api-invoice-schema.json)
- [billing-api-prepaid-order-schema.json](json-schema/billing-api-prepaid-order-schema.json)
- [and 7 more...](json-schema/)

### JSON Structure

- [14 JSON Structure files](json-structure/)

### JSON-LD

- [amberflo-metering-api-context.jsonld](json-ld/amberflo-metering-api-context.jsonld)
- [amberflo-billing-api-context.jsonld](json-ld/amberflo-billing-api-context.jsonld)
- [and 6 more...](json-ld/)

### Examples

- [14 example JSON files](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amberflo Metering API](capabilities/shared/metering-api.yaml) — 4 operations for event ingestion and usage queries
- [Amberflo Billing API](capabilities/shared/billing-api.yaml) — 4 operations for customer and billing management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Usage-Based Monetization](capabilities/usage-based-monetization.yaml) | Metering API, Billing API | 8 | Product Manager, Finance Team, API Developer |

## Vocabulary

- [Amberflo Vocabulary](vocabulary/amberflo-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 9 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amberflo Spectral Rules](rules/amberflo-spectral-rules.yml) — 25 rules across 10 categories enforcing Amberflo API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
