# Signifyd (signifyd)
Signifyd is an ecommerce fraud prevention, chargeback protection, and revenue optimization platform headquartered in San Jose, California. Its Commerce Protection Platform applies machine learning, elastic linking, and a merchant consortium covering roughly 98% of US online shoppers to make real-time guarantee decisions on orders. Merchants integrate via the Checkout, Sale, Transaction, Decisions, Returns, Sales Tax, and Feedback APIs (v2 and v3) with synchronous responses and/or asynchronous webhooks, and Signifyd financially guarantees approved orders against fraudulent chargebacks.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/signifyd/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Fraud, Fraud Prevention, Chargebacks, Ecommerce, Payments, Risk, Machine Learning, Commerce Protection, Account Protection, Returns

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Signifyd Sale (Checkout) API
Submit checkout and sale events for real-time fraud and chargeback risk evaluation. Checkout flow supports pre-authorization screening; Sale flow handles post-authorization order submission. Returns a guarantee decision (ACCEPT / HOLD / REJECT) within hundreds of milliseconds.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

- [Documentation](https://developer.signifyd.com/main/reference)
- [Getting Started](https://developer.signifyd.com/main/docs/getting-started)

### Signifyd Transaction API
Submit finalized order and payment transaction details after authorization so Signifyd can reconcile the pre-auth Checkout decision with the captured transaction and finalize the chargeback guarantee.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

### Signifyd Decisions API
Programmatically retrieve guarantee decisions, case details, and policy results — checkpointAction, checkpointActionReason, matched policies, and the ML score — to drive capture, ship, cancel, or manual review.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

### Signifyd Feedback API
Report observed user outcomes back to Signifyd to close the loop between real-time decisions and production reality. Dedicated endpoints cover Account Opening, Login, and Modification flows plus chargeback and fraud outcome reporting.

**Human URL:** [https://developer.signifyd.com/main/docs/feedback-api-overview](https://developer.signifyd.com/main/docs/feedback-api-overview)

### Signifyd Returns API
Submit return events for evaluation by Signifyd's Return Insights and Return Abuse Prevention models. Powers the Instant Refunds product and helps identify abusive returners.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

### Signifyd Sales Tax API
Nexus-aware US sales tax calculation, filing, and remittance across state and local jurisdictions.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

### Signifyd Account Protection API
Score non-purchase journeys — Account Opening, Login, and Modification — against account takeover, synthetic identity, and bonus abuse. Pairs with dedicated Feedback endpoints per checkpoint.

**Human URL:** [https://developer.signifyd.com/main/reference](https://developer.signifyd.com/main/reference)

### Signifyd Webhooks API
Receive asynchronous decision notifications via the `ORDER_CHECKPOINT_ACTION_UPDATE` topic, covering CHECKOUT, SALE, TRANSACTION, REROUTE, MERCHANT_REVIEW, and SIGNIFYD_REVIEW checkpoints. Each delivery is signed with an HMAC-SHA256 signature in the `SIGNIFYD-SEC-HMAC-SHA256` header.

**Human URL:** [https://developer.signifyd.com/main/docs/configuring-webhooks](https://developer.signifyd.com/main/docs/configuring-webhooks)

## Common Properties

- [Portal — signifyd.com](https://www.signifyd.com)
- [Portal — Developer Hub](https://developer.signifyd.com/)
- [Documentation — Developer Docs](https://developer.signifyd.com/main/docs)
- [Documentation — API Reference](https://developer.signifyd.com/main/reference)
- [Documentation — v3.0 Reference](https://developer.signifyd.com/main/v3.0/reference)
- [Documentation — v2.0 Reference](https://developer.signifyd.com/main/v2.0/reference)
- [GettingStarted](https://developer.signifyd.com/main/docs/getting-started)
- [Authentication](https://developer.signifyd.com/main/docs/authenticating)
- [Pricing](https://www.signifyd.com/pricing/)
- [AboutUs](https://www.signifyd.com/about-us/)
- [Blog](https://www.signifyd.com/blog/)
- [CaseStudies](https://www.signifyd.com/customers/)
- [Library](https://www.signifyd.com/resources/)
- [PrivacyPolicy](https://www.signifyd.com/legal/privacy-policy/)
- [TermsOfService](https://www.signifyd.com/legal/terms-of-use/)
- [Support](https://support.signifyd.com/)
- [LinkedIn](https://www.linkedin.com/company/signifyd)
- [Twitter](https://twitter.com/signifyd)
- [YouTube](https://www.youtube.com/c/Signifyd)
- [GitHubOrganization](https://github.com/signifyd)
- [SDK — PHP](https://github.com/signifyd/php)
- [Integrations — Magento 2](https://github.com/signifyd/magento2)
- [Integrations — Magento 1](https://github.com/signifyd/magento1)
- [Integrations — Salesforce Commerce Cloud](https://github.com/signifyd/Salesforce-Commerce-Cloud)
- [Documentation — API Blueprint repo](https://github.com/signifyd/docs)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
