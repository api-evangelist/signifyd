# Signifyd (signifyd)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
