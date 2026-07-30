# LendingClub

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
