# Monetization (monetization)
An index and topic collection covering API and SaaS monetization platforms: billing engines, subscription management, usage metering, usage-based pricing, revenue recognition, and the products that operate the monetization surface for digital businesses. This collection brings together vendors used to model pricing, meter usage, bill customers, recognize revenue, and operate the commercial layer of APIs and SaaS products. It spans full-stack billing platforms like Stripe, Chargebee, Recurly, Maxio, and Zuora; metering-first engines like Lago, OpenMeter, Metronome, Orb, Amberflo, Togai, and m3ter; entitlements and packaging tools like Stigg and Schematic; API-native monetization layers like Apigee Monetization, Zuplo, Moesif, and APIToolkit; and procurement, marketplace, and revenue-operations tools like Vendr, Tropic, Suger, ChartMogul, ProfitWell, and Sage Intacct.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Monetization, Billing, Subscription, Metering, Usage-Based Pricing, Revenue Recognition, Pricing

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Subscription Schema](https://raw.githubusercontent.com/api-evangelist/monetization/refs/heads/main/json-schema/monetization-subscription-schema.json)
- [JSONSchema - Usage Event Schema](https://raw.githubusercontent.com/api-evangelist/monetization/refs/heads/main/json-schema/monetization-usage-event-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/monetization/refs/heads/main/json-ld/monetization-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/monetization/refs/heads/main/vocabulary/monetization-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Subscription Management | Platforms like Chargebee, Recurly, Maxio, and Stripe Billing manage the full subscription lifecycle including signup, renewals, upgrades, downgrades, cancellations, dunning, and proration. |
| Usage Metering and Event Ingestion | Metering engines like Lago, OpenMeter, Metronome, Orb, Amberflo, Togai, and m3ter ingest high-volume usage events from APIs and SaaS products and convert them into billable quantities. |
| Usage-Based and Hybrid Pricing | Modern billing platforms model flat, tiered, volume, graduated, package, and usage-based pricing alongside committed-spend and prepaid credit models common in API and infrastructure businesses. |
| Invoicing and Payments | Monetization platforms generate invoices, calculate taxes, collect payments, manage payment methods, and retry failed charges across global payment rails. |
| Revenue Recognition and Finance Sync | Billing systems push booked, billed, and recognized revenue into ERP and accounting systems like Sage Intacct, NetSuite, and QuickBooks for ASC 606 / IFRS 15 compliant revenue recognition. |
| Entitlements and Feature Packaging | Tools like Stigg and Schematic separate pricing from feature gating, exposing entitlement checks so engineering can enforce plans without redeploying. |
| API Monetization and Analytics | API-native monetization layers like Apigee Monetization, Zuplo, Moesif, and APIToolkit attach pricing, plans, quotas, and analytics directly to API gateways and traffic. |
| Procurement, Marketplaces, and RevOps | Procurement and marketplace tools like Vendr, Tropic, and Suger, alongside RevOps analytics from ChartMogul and ProfitWell, manage the buy-side and post-billing reporting surface of monetization. |

## Use Cases

| Name | Description |
|------|-------------|
| SaaS Subscription Billing | Operate recurring subscription plans for a SaaS product with trials, proration, dunning, and tax handling using platforms like Chargebee, Recurly, Maxio, or Stripe Billing. |
| Usage-Based API Pricing | Meter API calls, tokens, compute, or data egress and bill customers per-unit, in tiers, or against prepaid credits using Lago, Metronome, Orb, Amberflo, m3ter, or Togai. |
| Hybrid Subscription and Consumption Billing | Combine fixed subscription fees with usage overages and committed-spend contracts for AI, data, and infrastructure products. |
| Feature Entitlements and Plan Gating | Drive feature access and plan limits from a central entitlements service like Stigg or Schematic instead of hardcoding plan logic in the application. |
| Cloud Marketplace Monetization | Sell through AWS, Azure, and GCP marketplaces with usage-based metering and contract billing via Suger and integrated marketplace billing flows. |
| API Gateway Monetization | Attach plans, quotas, and per-call pricing to APIs at the gateway layer using Apigee Monetization or Zuplo, and analyze monetized traffic with Moesif or APIToolkit. |
| Revenue Reporting and Subscription Analytics | Track MRR, ARR, churn, expansion, and cohort retention with ChartMogul and ProfitWell on top of upstream billing systems. |
| ERP and Revenue Recognition Sync | Reconcile billed and recognized revenue between subscription billing and finance ledgers like Sage Intacct, NetSuite, or Zuora Revenue. |

## Integrations

| Name | Description |
|------|-------------|
| Stripe Billing | Stripe's subscription, invoicing, and usage-based billing product, layered on top of Stripe's payments and tax infrastructure. |
| Chargebee | Subscription management and recurring billing platform for SaaS and subscription businesses, with deep finance and CRM integrations. |
| Recurly | Subscription billing platform focused on subscription lifecycle, dunning, and payments optimization. |
| Lago | Open-source usage-based billing and metering engine offering self-hosted and cloud deployments. |
| Metronome | Usage-based billing platform purpose-built for AI, data, and infrastructure companies running hybrid pricing models. |
| Orb | Usage-based billing platform for modern software businesses with sophisticated pricing and event-driven metering. |
| m3ter | Metering and pricing engine providing real-time event ingestion, pricing logic, and billing automation for API and SaaS products. |
| Stigg | Pricing and entitlements infrastructure that decouples feature gating and plan configuration from application code. |
| Apigee Monetization | API monetization layer for Google Cloud Apigee, attaching rate plans, transactions, and revenue reporting to managed APIs. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Subscription Schema](json-schema/monetization-subscription-schema.json)
- [Usage Event Schema](json-schema/monetization-usage-event-schema.json)

### JSON Structure

- [Subscription Structure](json-structure/monetization-subscription-structure.json)
- [Usage Event Structure](json-structure/monetization-usage-event-structure.json)

### JSON-LD

- [Monetization Context](json-ld/monetization-context.jsonld)

## Vocabulary

- [Monetization Vocabulary](vocabulary/monetization-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across subscription billing, usage metering, entitlements, and API monetization.

## Network

This index references the following monetization and billing repositories:

- [Amberflo](https://github.com/api-evangelist/amberflo)
- [Apigee](https://github.com/api-evangelist/apigee)
- [APIToolkit](https://github.com/api-evangelist/apitoolkit)
- [Chargebee](https://github.com/api-evangelist/chargebee)
- [ChartMogul](https://github.com/api-evangelist/chartmogul)
- [HostBill](https://github.com/api-evangelist/hostbill)
- [Invoice Ninja](https://github.com/api-evangelist/invoice-ninja)
- [Lago](https://github.com/api-evangelist/lago)
- [m3ter](https://github.com/api-evangelist/m3ter)
- [Maxio](https://github.com/api-evangelist/maxio)
- [Metronome](https://github.com/api-evangelist/metronome)
- [Moesif](https://github.com/api-evangelist/moesif)
- [Orb](https://github.com/api-evangelist/orb)
- [ProfitWell](https://github.com/api-evangelist/profitwell)
- [Recurly](https://github.com/api-evangelist/recurly)
- [Sage Intacct](https://github.com/api-evangelist/sage-intacct)
- [Schematic](https://github.com/api-evangelist/schematic)
- [Stigg](https://github.com/api-evangelist/stigg)
- [Stripe](https://github.com/api-evangelist/stripe)
- [Suger](https://github.com/api-evangelist/suger)
- [Togai](https://github.com/api-evangelist/togai)
- [Tropic](https://github.com/api-evangelist/tropic)
- [Vendr](https://github.com/api-evangelist/vendr)
- [Zoho Invoice](https://github.com/api-evangelist/zoho-invoice)
- [Zuora](https://github.com/api-evangelist/zuora)
- [Zuplo](https://github.com/api-evangelist/zuplo)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
