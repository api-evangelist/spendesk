# Spendesk (spendesk)

Spendesk is an AI-powered spend management and procurement platform trusted by over 200,000 users across Europe. It provides corporate cards (virtual and physical), expense claim management, invoice processing, approval workflows, and real-time budget monitoring in a single platform. The Spendesk Public API enables partners and customers to programmatically integrate card issuance, transaction retrieval, expense claims, vendor and invoice management, accounting exports, and webhook subscriptions into their own systems.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/spendesk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spendesk/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=spendesk-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=spendesk-api-evangelist&utm_content=repo)

## Tags

- Spend Management
- Corporate Cards
- Expense Management
- Invoices
- Procurement
- FinTech
- Accounting
- Payments

## APIs

| Name | Description | Documentation |
|------|-------------|---------------|
| Spendesk Public API | REST API for managing corporate cards, expense claims, vendor invoices, wallet summaries, settlements, bank fees, members, suppliers, cost centers, analytical fields, and webhook subscriptions. | [docs](https://developer.spendesk.com/reference/general) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/spendesk-plans-pricing.yml](plans/spendesk-plans-pricing.yml) |
| Rate Limits | [rate-limits/spendesk-rate-limits.yml](rate-limits/spendesk-rate-limits.yml) |
| FinOps | [finops/spendesk-finops.yml](finops/spendesk-finops.yml) |

**Key rate limits:**
- 50 requests/minute per entity (API key / customer)
- 250 requests/minute per OAuth2 partner
- 5 concurrent requests maximum for any consumer
- HTTP 429 returned when exceeded; retry after `x-ratelimit-reset` seconds

**Plan requirements:** API access requires Premium or Enterprise subscription.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.spendesk.com/ |
| Documentation | https://developer.spendesk.com/ |
| GitHub Organization | https://github.com/Spendesk |
| LinkedIn | https://www.linkedin.com/company/spendesk |
| X (Twitter) | https://twitter.com/Spendesk |
| Blog | https://www.spendesk.com/blog/ |
| Pricing | https://www.spendesk.com/pricing/ |
| Status Page | https://status.spendesk.com/ |
| Changelog | https://developer.spendesk.com/changelog |
| Postman Collection | https://www.postman.com/spendesk-pde-sas/spendesk-public-api/collection/q48314q/spendesk-public-api |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
