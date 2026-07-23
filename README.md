# F.N.B. Corporation (fnb-corp)

F.N.B. Corporation (NYSE: FNB) is a diversified financial services holding company headquartered in Pittsburgh, Pennsylvania, and the parent of First National Bank of Pennsylvania, an FDIC-insured, state-chartered commercial bank. With roughly $50 billion in total assets at year-end 2025, FNB is a regional super-community bank operating around 350 branches across seven states and Washington, D.C., offering commercial banking, consumer banking and wealth management through its eStore digital platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fnb-corp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fnb-corp/refs/heads/main/apis.yml)

## Open Finance / API Posture

F.N.B. Corporation exposes **no first-party public developer portal or documented API**. Probing the institution's infrastructure confirms this:

- `developer.fnb-online.com`, `developers.fnb-online.com`, and `api.fnb-online.com` all return **HTTP 301 redirects to the marketing homepage** (`https://www.fnb-online.com/`) — there is no dedicated developer subdomain.
- `www.fnb-online.com/developers`, `/developer`, and `/api` all return **HTTP 404** — no developer documentation is published.

Consumer-permissioned account, balance and transaction data for First National Bank of Pennsylvania is reachable **only through third-party data aggregators** (notably [Plaid](https://plaid.com/institutions/fnb/)), which build to Financial Data Exchange (FDX) standards. No direct FDX membership or public CFPB Section 1033 data-access posture is documented by the institution itself as of this profile.

This is the honest, common posture for a U.S. regional bank: open finance participation happens on the aggregator side, not via a first-party bank API.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Consumer Banking
- Commercial Banking
- Wealth Management
- Data Aggregation
- Open Finance

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### FNB Consumer Data Access (Aggregator-Only)

F.N.B. Corporation publishes no first-party developer API. Consumer-permissioned data for First National Bank of Pennsylvania is available only through third-party aggregators such as Plaid. This is an honest pointer to that aggregator access path, not a first-party FNB API surface.

- **Human URL:** [https://plaid.com/institutions/fnb/](https://plaid.com/institutions/fnb/)

#### Tags

- Data Aggregation
- Open Finance
- Consumer Banking

#### Properties

- [Documentation](https://plaid.com/institutions/fnb/)

## Common Properties

- [Website](https://www.fnb-online.com/)
- [Privacy Policy](https://www.fnb-online.com/privacy)
- [Terms of Service](https://www.fnb-online.com/terms-of-use)
- [Support](https://www.fnb-online.com/contact-us)
- [LinkedIn](https://www.linkedin.com/company/f-n-b--corporation)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
