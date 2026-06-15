# Razorpay (razorpay)

Razorpay is India's leading full-stack payments and business banking platform, enabling merchants to accept, process, and disburse payments across cards, UPI, netbanking, wallets, EMI, and BNPL through a single integration. Its developer platform exposes a fully RESTful API at https://api.razorpay.com/v1 (with select v2 resources) returning JSON, secured by HTTP Basic authentication using a key_id and key_secret pair. Beyond core payment processing, Razorpay offers payment links, hosted pages, subscriptions, smart routing, refunds, settlements, payouts via RazorpayX, and KYC-driven onboarding.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/razorpay/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/razorpay/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Payments
- Payment Gateway
- Fintech
- India
- UPI
- Subscriptions
- Payouts
- Checkout

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Razorpay Core REST API

RESTful API covering orders, payments, refunds, customers, tokens, invoices, payment links, virtual accounts, settlements, transfers, subscriptions, and webhooks. Authentication is HTTP Basic using the API key_id as username and key_secret as password; all endpoints return JSON and follow standard HTTP semantics.

- **Human URL:** [https://razorpay.com/docs/api/](https://razorpay.com/docs/api/)
- **Base URL:** `https://api.razorpay.com/v1`

#### Tags

- Payments
- REST API
- Basic Auth
- JSON

#### Properties

- [Documentation](https://razorpay.com/docs/api/)
- [Authentication](https://razorpay.com/docs/api/authentication/)
- [Postman  Collection](https://www.postman.com/razorpaydev/razorpay-public-workspace/overview)
- [Webhooks](https://razorpay.com/docs/webhooks/)
- [Errors](https://razorpay.com/docs/errors/)
- [Postman Collection](collections/razorpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/razorpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Razorpay Payments API

Subset of the core REST API focused on creating orders, capturing authorized payments, fetching payment details, issuing refunds, and retrieving transfers for split settlements between linked accounts.

- **Human URL:** [https://razorpay.com/docs/api/payments/](https://razorpay.com/docs/api/payments/)
- **Base URL:** `https://api.razorpay.com/v1`

#### Tags

- Payments
- Orders
- Refunds

#### Properties

- [Documentation](https://razorpay.com/docs/api/payments/)
- [Postman Collection](collections/razorpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/razorpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Razorpay Webhooks

Event-driven webhook surface that POSTs JSON payloads to a merchant-configured HTTPS endpoint when subscribed events occur across payments, orders, refunds, subscriptions, invoices, settlements, Smart Collect virtual accounts, payment links, Route transfers, disputes, and payment downtime advisories. Each delivery is signed with an HMAC-SHA256 hex digest of the raw request body using the merchant's webhook secret, transmitted via the X-Razorpay-Signature header.

- **Human URL:** [https://razorpay.com/docs/webhooks/](https://razorpay.com/docs/webhooks/)

#### Tags

- Webhooks
- Events
- AsyncAPI
- HMAC-SHA256

#### Properties

- [Documentation](https://razorpay.com/docs/webhooks/)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/razorpay/refs/heads/main/asyncapi/razorpay-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Signature Validation](https://razorpay.com/docs/webhooks/validate-test/)
- [Event Payloads](https://razorpay.com/docs/webhooks/payloads/)
- [Postman Collection](collections/razorpay.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/razorpay.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/razorpay)
- [Website](https://razorpay.com)
- [Documentation](https://razorpay.com/docs/)
- [API Reference](https://razorpay.com/docs/api/)
- [Pricing](https://razorpay.com/pricing/)
- [Sign Up](https://dashboard.razorpay.com/signup)
- [Dashboard](https://dashboard.razorpay.com)
- [Support](https://razorpay.com/support/)
- [Status Page](https://status.razorpay.com)
- [Git Hub](https://github.com/razorpay)
- [Blog](https://razorpay.com/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
