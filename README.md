# Weatherbys Bank (weatherbys-bank)

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
