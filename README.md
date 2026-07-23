# PC Financial (pc-financial)

PC Financial (President's Choice Financial) is the financial-services brand of Canadian grocery giant Loblaw Companies Limited. Its personal banking and Mastercard credit-card products are issued by President's Choice Bank, a federally chartered Schedule I bank and CDIC member. The digital-first, branchless brand centers on the no-fee PC Money Account, PC Financial Mastercard credit cards, and deep integration with the PC Optimum loyalty program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pc-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pc-financial/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Canada
- Schedule I Bank
- Digital Banking
- Credit Cards
- Loyalty
- Interac
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open Finance & API Posture

PC Financial runs **no public first-party developer portal or API**. Probes of `developer.pcfinancial.ca` and `api.pcfinancial.ca` do not resolve (no DNS / connection refused); only the consumer marketing site at `www.pcfinancial.ca` responds (HTTP 200).

- **Consumer-Driven Banking (CDB):** Canada's federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, overseen by the FCAC) is legislated but not yet operational. There is no live open-banking mandate and no PC Financial CDB/FDX endpoint. No published PC Financial position on the framework was found.
- **Aggregator access:** Consumer account data access today is aggregator/screen-scraping-based via third parties such as **Plaid** and **Finicity (Mastercard)**, not a first-party API. This is the honest reality for the brand.
- **Payments rails:** The PC Money Account supports **Interac e-Transfer**. Cards operate on the **Mastercard** network. No documented public API around either rail.
- **Ownership note:** In December 2025 **Equitable Bank (EQB)** agreed to acquire PC Financial from Loblaw for roughly $800 million; this profile tracks the Canadian President's Choice Bank entity.

No downloadable OpenAPI/Swagger specifications exist to harvest.

## APIs

None. PC Financial exposes no public developer API surface. Consumer data access is available only through third-party aggregators (Plaid, Finicity).

## Common Properties

- [Website](https://www.pcfinancial.ca/en/)
- [Terms of Service](https://www.pcoptimum.ca/presidents-choice-financial-legal)
- [Privacy Policy](https://www.pcoptimum.ca/presidents-choice-financial-legal)
- [Support](https://www.pcfinancial.ca/en/contact-us/)
- [Documentation / FAQ](https://www.pcfinancial.ca/en/faqs/)
- [LinkedIn](https://www.linkedin.com/company/president's-choice-financial)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
