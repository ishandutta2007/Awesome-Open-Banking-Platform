# Awesome-Open-Banking-Platform

# Top Open Banking Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Account Information (AIS), Payment Initiation (PIS), PSD2/Open Finance Connectivity, Bank Aggregation & Account-to-Account Payments*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Open Banking**. These systems provide regulated, API-based access to bank accounts and payment initiation so fintechs, banks, and businesses can build account aggregation, pay-by-bank, verification, and financial data products.

**Examples** include TrueLayer, Yapily, Tink, Plaid, GoCardless Bank Pay / Bank Account Data, Token.io, Volt, Trustly, Nuvei Open Banking, Fintecture, Finicity, Belvo, Salt Edge, Nordigen, Enable Banking, Lean Technologies, and Mono (the category leaders).

**Open-source emphasis**: Fully featured commercial open-banking aggregators are limited in pure open source because of regulatory licensing and bank connectivity requirements. Strong building blocks exist in the **Open Bank Project**, PSD2 client libraries, unified bank proxies, and self-hosted finance tools. This section is expanded with the most relevant open projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[TrueLayer](https://truelayer.com/)**  
  Leading UK/EU open-banking platform strong in payment initiation (PIS) and account data (AIS), widely used for pay-by-bank and payouts.

- **[Yapily](https://www.yapily.com/)**  
  Developer-focused open-banking infrastructure providing headless AIS and PIS connectivity across UK and European banks for white-label products.

- **[Tink (Visa)](https://tink.com/)**  
  Pan-European open-banking platform (now part of Visa) offering account information, payment initiation, categorisation, and income insights.

- **[Plaid](https://plaid.com/)**  
  Dominant North American bank-connectivity platform for account verification, transactions, identity, income, and investments, with expanding global coverage.

- **[GoCardless Bank Pay / Bank Account Data](https://gocardless.com/)**  
  Open-banking payments and (formerly Nordigen) account-data services focused on account-to-account payments and bank data access.

- **[Token.io](https://token.io/)**  
  European open-banking platform supporting payment initiation, variable recurring payments (VRPs), and account data with strong regulatory coverage.

- **[Volt](https://www.volt.io/)**  
  Account-to-account payment specialist using open-banking rails for instant pay-by-bank experiences.

- **[Trustly](https://www.trustly.com/)**  
  Pay-by-bank and account-to-account payment network with broad European coverage.

- **[Nuvei Open Banking](https://www.nuvei.com/)**  
  Open-banking payment capabilities within Nuvei’s broader global payments platform.

- **[Fintecture](https://www.fintecture.com/)**  
  European open-banking payment initiation and account solutions for merchants and platforms.

- **[Finicity (Mastercard)](https://www.finicity.com/)**  
  US-focused open-banking and data aggregation platform, part of Mastercard, strong in verification and lending use cases.

- **[Belvo](https://belvo.com/)**  
  Open-finance platform focused on Latin America, providing account data and payment connectivity.

- **[Salt Edge](https://www.saltedge.com/)**  
  Open-banking and data aggregation provider with broad bank coverage and enrichment services.

- **[Enable Banking](https://enablebanking.com/)**  
  PSD2-focused connectivity provider known for relatively accessible developer onboarding and European bank coverage.

- **[Lean Technologies / Mono and regional players](https://www.leantech.me/)**  
  Open-banking and open-finance platforms serving Middle East, Africa, and other emerging markets.

## Open-Source GitHub Projects
- **[Open Bank Project (OBP-API)](https://github.com/OpenBankProject/OBP-API)**  
  Leading open-source RESTful API platform for banks supporting Open Banking, PSD2, XS2A, and Open Finance — accounts, transactions, payments, consents, and internal banking APIs.

- **[Open PSD2 client frameworks](https://github.com/ExtraBB/open-psd2)**  
  Open-source libraries for working with PSD2 bank APIs that abstract differences between bank implementations.

- **[BankProxy](https://github.com/bankproxy/bankproxy)**  
  Unified HTTP API service for retrieving transactions and initiating payments, based on NextGenPSD2 / Berlin Group standards, designed to sit beside other services.

- **[Finanze](https://github.com/finanze/finanze)**  
  Self-hosted personal finance and net-worth tracker that aggregates banks (including via open-banking/PSD2 providers), investments, crypto, and real estate with a privacy-first design.

- **[Multibanking and PSD2 demo applications](https://github.com/)**  
  Open web applications demonstrating aggregation of multiple banks via PSD2 APIs, useful as reference implementations.

- **[Open Bank Project supporting tools](https://github.com/OpenBankProject)**  
  Consent helpers, API explorers, front-end applications, and testing utilities that complement the core OBP-API.

- **[Berlin Group / NextGenPSD2 related open components](https://github.com/)**  
  Community libraries and adapters implementing or consuming the common European open-banking standards.

- **[Self-hosted consent and connection managers](https://github.com/)**  
  Open tools for managing user bank consents, token refresh, and connection lifecycle in AIS/PIS flows.

- **[Transaction categorisation and enrichment open models](https://github.com/)**  
  Open-source approaches to cleaning and categorising bank transaction data once retrieved via open banking.

- **[Local-first finance dashboards with bank connectors](https://github.com/)**  
  Privacy-oriented projects that combine open-banking data sources with local encrypted storage.

### Additional Strong Open-Source Options
- Running Open Bank Project as a bank-side or sandbox open-banking layer.
- Building thin aggregation layers on top of regulated TPPs while keeping customer data in your own infrastructure.
- Using open standards (Berlin Group, UK Open Banking, FDX) as the contract even when the connectivity layer is commercial.
- Combining open personal-finance tools with commercial AIS providers for end-user products that minimise data retention.
- Community lists of PSD2/open-banking endpoints and postman collections for testing.

**Frameworks for building custom systems**: For regulated production connectivity you will almost always need a licensed TPP or a bank-side platform. Use commercial providers (TrueLayer, Yapily, Tink, Plaid, etc.) for live bank links, and layer **Open Bank Project** or open client libraries for internal APIs, sandboxes, and consent management. Self-hosted tools such as **Finanze** or custom dashboards can consume the data while keeping storage under your control. This hybrid approach maximises openness where possible while meeting regulatory and bank-connectivity realities. Pure open-source stacks are currently best suited to bank-side implementations, sandboxes, research, and privacy-focused personal tools rather than full multi-bank consumer aggregation at scale.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Open banking involves regulated financial data and payments. Operating as an Account Information Service Provider (AISP) or Payment Initiation Service Provider (PISP) generally requires authorisation from a financial regulator (FCA, national competent authorities under PSD2/PSD3, etc.). Open-source software does not replace the need for proper licensing, security, and compliance. Always consult legal and compliance experts before handling real customer bank data or initiating payments.
- Handle consents, credentials, and personal financial data with the highest care and in accordance with GDPR and applicable financial regulations.

---
**Made for fintech builders, banks, and developers working with account data and account-to-account payments.**
Let's make open banking more interoperable, transparent, and developer-friendly where regulation allows.
