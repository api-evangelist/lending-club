# LendingClub

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

LendingClub is a US consumer-finance company and digital bank, founded in 2006 as a peer-to-peer marketplace lender and now a national bank following its 2021 acquisition of Radius Bancorp. In 2026 it rebranded as **Happen Bank, N.A.** (a subsidiary of Happen, Inc.) and moved its public web presence from `lendingclub.com` to [happen.com](https://www.happen.com/).

Backed by: canaan-partners

## API status

**LendingClub operates no public developer program.** As of the July 2026 enrichment pass:

- No developer portal, API reference, or documentation is published (`/developers` returns 404 on both domains; the sitemap has no developer or API URLs).
- No OpenAPI, AsyncAPI, GraphQL, or Protobuf specification is available to harvest.
- No first-party SDKs, CLI, MCP server, webhooks, or Agent Skills are published.
- No `.well-known` discovery documents are served — the site answers unmatched `/.well-known/` paths with a 200 HTML shell (a soft 404), so those statuses are not evidence of publication.
- No status page, vulnerability disclosure program, or trust center was found.
- The legacy Investor API host `api.lendingclub.com` still answers `/api/investor/v1/...` with HTTP 401, but it is undocumented and closed. It served the retail Notes marketplace, which LendingClub retired in December 2020.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `apis.yml` | APIs.json profile | searched |
| `lifecycle/lending-club-lifecycle.yml` | Lifecycle — rebrand, retired developer program, legacy API probe evidence | searched |
| `well-known/lending-club-well-known.yml` | Well-known discovery probe (0 documents found) | probed |
| `security/lending-club-domain-security.yml` | Domain security — TLS/HSTS/DNSSEC/CAA/SPF/DMARC | probed |
| `llms/lending-club-llms.txt` | llms.txt | generated |
