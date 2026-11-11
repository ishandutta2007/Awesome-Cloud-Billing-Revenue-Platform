# Awesome-Cloud-Billing-Revenue-Platform

## Top Cloud Billing & Revenue Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Subscription Billing, Usage Metering & Revenue Recognition Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Billing & Revenue Platforms**. These tools help SaaS and AI companies automate the full revenue lifecycle—from pricing and quoting through invoicing, dunning, payment collection, and revenue recognition—while supporting hybrid models that blend subscriptions, usage, credits, and outcome-based charges.

**Examples** include Chargebee, Stripe Billing, Zuora, Recurly, Maxio, Paddle, FastSpring, BillingPlatform, Ordway, and Rebilly (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted billing engines, subscription management, and revenue recognition—ideal for SaaS builders, finance engineers, and developers seeking transparent, vendor-neutral billing infrastructure without percentage-of-revenue fees scaling indefinitely.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Chargebee](https://www.chargebee.com/)** | Enterprise billing platform rebuilt for AI-era hybrid pricing: credits, actions, and outcomes on a single catalog with margin controls. 2026 Flow plan includes 100M usage events/month; CPQ Lite free for first 50 quotes. Gartner Leader in recurring billing three consecutive years [citation:1]. | Flow: $0 + 0.80% of monthly invoicing, or $99/month + 0.65% [citation:1] | No free tier; Flow PAYG has $0 base fee but charges 0.80% of invoicing from first dollar [citation:1] |
| **[Stripe Billing](https://stripe.com/billing)** | Developer-first recurring billing with subscriptions, usage-based invoicing, proration, and dunning. Merged Starter and Scale plans into a single Billing plan covering all subscription management features [citation:2]. Payment processing (2.9% + $0.30) is separate from Billing fees. | 0.70% of billing volume (pay-as-you-go); subscription-based plans available in most countries [citation:2][citation:12] | No free tier; Billing fee applies to all billing volume [citation:2] |
| **[Zuora](https://www.zuora.com/)** | Enterprise subscription order-to-cash platform with advanced revenue recognition (ASC 606/IFRS 15), multi-entity support, and CPQ. Growth edition supports up to 500,000 active subscribers; Enterprise up to 2,000,000 [citation:13]. | Quote-only; Vendr data shows typical total cost ~$170,000 for mid-market deployments [citation:3] | No free tier; implementation services typically 15–40% of annual platform fees [citation:3] |
| **[Recurly](https://recurly.com/)** | Subscription management with transparent pricing and optional add-ons for retention (Engage) and revenue recognition (RevRec). Starter includes 10+ payment methods, 20+ gateways, and one dunning campaign [citation:4]. | Starter: $249/month + 0.9% of billing volume (first $40K billings/month included) [citation:4] | No free tier; Starter plan has no separate free trial listed |
| **[Maxio](https://www.maxio.com/)** | Billing and financial reporting for B2B SaaS and AI with usage-based billing, recurring billing, collections/dunning, and 20+ payment gateways. Unlimited users at no additional charge [citation:5]. | Grow: $599/month (up to $100K monthly billings); Scale: quote for over $100K [citation:5] | No free tier; pricing bands are transparent but no trial mentioned |
| **[Paddle](https://www.paddle.com/)** | Merchant of Record billing platform handling payments, tax, and compliance. Pricing cards component available for developers; specific billing rates not listed in search results (varies by volume and geography). | Quote-only (varies by volume/geography) | No free tier details in search results |
| **[FastSpring](https://fastspring.com/)** | Merchant of Record with bundled payment processing, tax handling, and invoicing. Independent reports indicate common structure of ~$0.95 per transaction + ~5.9% of sale [citation:7]. | ~$0.95/transaction + ~5.9% of sale (indicative) [citation:7] | No free tier; custom quote required |
| **[BillingPlatform](https://billingplatform.com/)** | Enterprise monetization and quote-to-cash platform with hybrid pricing (bundles + usage components) configured without code. Gartner Peer Insights reviewers note flexibility in aligning marketing offers with final invoices [citation:8]. | Quote-only | No free tier; demo via sales |
| **[Ordway](https://ordwaylabs.com/)** | Billing and revenue automation platform with AutoPay, threshold billing, dunning, and cash application. Capterra listing shows limited public pricing detail; 9 verified reviews [citation:9]. | Quote-only (Capterra shows $0.01 placeholder) | No free tier details in search results |
| **[Rebilly](https://www.rebilly.com/)** | Subscription billing with orders, invoices, pricing plans, and auto-pay. Pricing calculator shows Pro plan at $125/month base + 1% revenue fee; 10 team members included, extra at $10/mo each [citation:10]. | Pro: $125/month base + 1% of monthly revenue (up to 10 team members) [citation:10] | No free tier; calculator provides transparent estimate |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kill Bill](https://github.com/killbill/killbill)** | [![Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers) | Mature open-source subscription billing and payments platform with entitlements, invoicing, usage metering, and multi-tenant support. Apache 2.0 licensed; the most established self-hosted alternative for complex subscription businesses. |
| **[Lago](https://github.com/getlago/lago)** | [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers) | Open-source usage-based billing API with metering, pricing plans, invoices, and payment orchestration. Designed as a self-hosted alternative to Chargebee and Stripe Billing for usage-heavy SaaS. |
| **[Recurso](https://github.com/recurso-dev/recurso)** | [![Stars](https://img.shields.io/github/stars/recurso-dev/recurso?style=social&color=white)](https://github.com/recurso-dev/recurso/stargazers) | Open-source (MIT) billing engine for SaaS in Go + PostgreSQL: subscriptions, invoicing, multi-currency payments, smart dunning, usage-based billing with 8 aggregations, built-in double-entry ledger, and self-serve importers from Stripe/Chargebee. |
| **[BillaBear](https://github.com/billabear/billabear)** | [![Stars](https://img.shields.io/github/stars/billabear/billabear?style=social&color=white)](https://github.com/billabear/billabear/stargazers) | Subscription management and billing system with REST API, workflow automation for retryable processes, tax management (EU reverse charge, VAT Sense integration), and multiple payment provider support. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)** | [![Stars](https://img.shields.io/github/stars/FOSSBilling/FOSSBilling?style=social&color=white)](https://github.com/FOSSBilling/FOSSBilling/stargazers) | Free, open-source billing and client management for hosting providers and digital businesses with invoicing, recurring charges, and payment gateway modules. |
| **[Akaunting](https://github.com/akaunting/akaunting)** | [![Stars](https://img.shields.io/github/stars/akaunting/akaunting?style=social&color=white)](https://github.com/akaunting/akaunting/stargazers) | Open-source accounting suite with recurring invoicing and subscription-style billing for small businesses. |
| **[Invoice Ninja](https://github.com/invoiceninja/invoiceninja)** | [![Stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers) | Self-hosted invoicing, quoting, and recurring billing platform with client portal and payment gateway integrations. |

**Frameworks for building custom systems**: Combine **Kill Bill** for entitlements and metering, **Lago** for usage-based billing, **Recurso** for ledger-backed billing logic, and **BillaBear** for workflow-heavy subscription management—all deployable via Docker Compose with PostgreSQL and Redis.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Billing platforms must comply with applicable tax regulations (VAT, GST, sales tax) and revenue recognition standards (ASC 606/IFRS 15) where applicable.
- Percentage-of-revenue pricing models can become expensive at scale; model total cost across your projected invoicing volume before committing. Self-hosted open-source billing engines require ledger reconciliation controls and financial audit trails.

---

**Made for SaaS founders, finance engineers, revenue operations teams, and developers building subscription businesses.**  
Let's make cloud billing and revenue platforms more open, transparent, and cost-predictable.
