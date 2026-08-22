# F.N.B. Corporation (fnb-corp)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
