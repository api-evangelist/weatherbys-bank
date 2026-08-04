# Weatherbys Bank (weatherbys-bank)

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

Weatherbys Bank is a small, family-owned UK private bank, part of the Weatherbys Banking Group, trading since James Weatherby founded the family business in 1770 and incorporated as Weatherbys Bank Limited in 1994. It serves private, business, and racing customers through Weatherbys Private Bank and Weatherbys Racing Bank, and is authorised by the PRA and regulated by the FCA. As an FCA-authorised ASPSP it is a regulated participant in UK Open Banking (PSD2), publishing OBIE-conformant Open Data and Read/Write API surfaces. It is not one of the CMA9 mandated banks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/weatherbys-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/weatherbys-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- Private Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

Weatherbys' Open Banking gateway is hosted on Oracle Banking APIs (BaaS) at `openbanking.weatherbysbank.com`. There is no separately branded public developer portal; the OBIE API surfaces below follow the UK Open Banking Standard. The bank's Open Banking host resets TLS connections presented without a client certificate, so no live Open Data endpoint returned a 200 at review time — the Open Data APIs are represented as documented/standard and marked unverified. The OpenAPI documents referenced are the shared OBIE Open Data standard specifications (Swagger 2.0), not bank-proprietary contracts.

### Weatherbys Bank Open Data ATM Locator API

PUBLIC, unauthenticated OBIE Open Data ATM Locator API — reference data for the bank's ATMs (postal address, geographic coordinates, services). Conforms to the OBIE Open Data API Standard v2.3.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v2.3`

#### Tags

- Open Data
- ATM Locator
- Public

#### Properties

- [OpenAPI](openapi/obie-opendata-atm-locator-standard.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/atmlocator/atm-locator.html)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

### Weatherbys Bank Open Data Branch Locator API

PUBLIC, unauthenticated OBIE Open Data Branch Locator API — reference data for the bank's branches. Conforms to the OBIE Open Data API Standard v2.3.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v2.3`

#### Tags

- Open Data
- Branch Locator
- Public

#### Properties

- [OpenAPI](openapi/obie-opendata-branch-locator-standard.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/branchlocator/branch-locator.html)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

### Weatherbys Bank Open Data Personal Current Accounts API

PUBLIC, unauthenticated OBIE Open Data Personal Current Accounts (PCA) API — reference product data (features, fees, rates, eligibility). Conforms to the OBIE Open Data API Standard v2.4.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v2.4`

#### Tags

- Open Data
- Personal Current Accounts
- Public

#### Properties

- [OpenAPI](openapi/obie-opendata-personal-current-accounts-standard.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/pca/pca.html)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

### Weatherbys Bank Open Data Business Current Accounts API

PUBLIC, unauthenticated OBIE Open Data Business Current Accounts (BCA) API — reference product data for business current accounts. Conforms to the OBIE Open Data API Standard v2.4.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v2.4`

#### Tags

- Open Data
- Business Current Accounts
- Public

#### Properties

- [OpenAPI](openapi/obie-opendata-business-current-accounts-standard.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/bca/bca.html)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

### Weatherbys Bank Account and Transaction Information API (AIS)

OBIE Read/Write Account and Transaction Information API (AISP). FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 strong customer authentication) — requires OBIE/eIDAS certificates and dynamic client registration.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v3.1/aisp`

#### Tags

- Read/Write
- Account Information
- AIS

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### Weatherbys Bank Payment Initiation API (PIS)

OBIE Read/Write Payment Initiation API (PISP). FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA) — requires OBIE/eIDAS certificates and dynamic client registration.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v3.1/pisp`

#### Tags

- Read/Write
- Payment Initiation
- PIS

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### Weatherbys Bank Confirmation of Funds API (CBPII)

OBIE Read/Write Confirmation of Funds API (CBPII). FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA) — requires OBIE/eIDAS certificates and dynamic client registration.

- **Human URL:** [https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- **Base URL:** `https://openbanking.weatherbysbank.com/open-banking/v3.1/cbpii`

#### Tags

- Read/Write
- Confirmation of Funds
- CBPII

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

## Common Properties

- [Website](https://www.weatherbys.bank/)
- [Sign In](https://odbx.weatherbysbank.com/)
- [Documentation](https://www.openbanking.org.uk/regulated-providers/weatherbys-bank-limited/)
- [LinkedIn](https://www.linkedin.com/company/weatherbys-banking-group)
- [Blog](https://www.weatherbys.bank/insights/)
- [Status Page](https://www.weatherbys.bank/help-and-support/service-updates/)
- [Support](https://www.weatherbys.bank/help-and-support/)
- [Terms of Service](https://www.weatherbys.bank/terms-conditions/)
- [Privacy Policy](https://www.weatherbys.bank/privacy-policy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
