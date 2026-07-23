# Associated Bank (associated-banc-corp)

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
