# Associated Bank (associated-banc-corp)

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

Associated Bank, N.A. is the primary banking subsidiary of Associated Banc-Corp (NYSE: ASB), a nationally chartered commercial bank and the largest bank holding company headquartered in Wisconsin, based in Green Bay. With roughly $50 billion in total assets following the April 2026 acquisition of American National Corporation, Associated operates a full-service Midwest banking franchise of more than 200 locations across Wisconsin, Illinois, Iowa, Minnesota, Missouri and Nebraska, serving consumer, business, commercial and wealth-management customers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/associated-banc-corp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/associated-banc-corp/refs/heads/main/apis.yml)

## Open Finance Posture

Associated Bank does **not** publish a first-party public developer portal or downloadable OpenAPI/Swagger specifications. Its posture is honest and typical of a US regional bank:

- **No first-party developer API.** Probes of `developer.associatedbank.com`, `api.associatedbank.com` and `apis.associatedbank.com` do not resolve.
- **Core-provider stack.** Digital and core banking run on Jack Henry; the institution is documented on Jack Henry's `jackhenry.dev` as a jXchange SOAP provider (Account History Search, Account Inquiry, Account Relationship Search, Transaction Add). This is partner/enterprise-gated, not a self-serve public API, and no public WSDL/OpenAPI is published.
- **Aggregator access.** Consumer-permissioned data is reached through third-party aggregators (Plaid, Tink/TrueLayer), not a direct first-party API.
- **Commercial platform.** Treasury/commercial customers use the login-gated **Associated Connect** portal.
- **FDX / CFPB 1033.** No Financial Data Exchange participation and no published Section 1033 data-access posture found as of this review (2026-07-23).

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Banking
- Data Aggregation
- Open Finance

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Associated Bank jXchange (Jack Henry) Integration

Core-banking integration surfaced through Associated Bank's core provider, Jack Henry, via the jXchange SOAP API platform. Documented services include Account History Search, Account Inquiry, Account Relationship Search and Transaction Add. Partner/enterprise-gated and core-provider-mediated — not a first-party public API.

- **Human URL:** [https://jackhenry.dev/jxchange-soap/api-provider/associated-bank/](https://jackhenry.dev/jxchange-soap/api-provider/associated-bank/)

#### Tags

- Core Banking
- SOAP
- Jack Henry
- jXchange

#### Properties

- [Documentation](https://jackhenry.dev/jxchange-soap/api-provider/associated-bank/)

## Common Properties

- [Website](https://www.associatedbank.com/)
- [Blog / Newsroom](https://newsroom.associatedbank.com/)
- [LinkedIn](https://www.linkedin.com/company/associated-bank)
- [Privacy Policy](https://www.associatedbank.com/privacy)
- [Terms of Use](https://www.associatedbank.com/terms-of-use)
- [Support / Contact](https://www.associatedbank.com/contact)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
