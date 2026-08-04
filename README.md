# PC Financial (pc-financial)

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
