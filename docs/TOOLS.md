# Tool and evidence guide

Use the [hosted workspace](https://sonar.pactuno.online/) to run tools. This repository contains instructions and fictional examples, not the application backend.

## Audit and page evidence

| Tool area | What to inspect |
| --- | --- |
| Overview / Site crawl | Current sample, state, scope, technical score and notes. |
| Issues | Affected URL, observed evidence and suggested repair. |
| Page explorer | Returned metadata, headings, links, images and selected response signals. |
| Robots & sitemap | Crawl directives and observed discovery information. |
| HTTP & security | Selected response headers, HTTPS and mixed-content signals. |

Current crawl modes include single-page, fast up to 50 pages and deep up to 100 pages. Actual coverage can be smaller. The crawler does not render site JavaScript.

## Intelligence and comparisons

| Tool area | How to interpret it |
| --- | --- |
| Link architecture | Relationships and depth in the fetched sample; verify orphan candidates. |
| Content review | Duplicate metadata and other observed or heuristic page signals. |
| Keyword intelligence | On-page terms and supported intent/topic analysis; not a global volume index. |
| Competitor / head-to-head comparisons | Compare supported page evidence. A comparison is not private competitor analytics. |
| SERP & social previews | Draft appearance based on metadata; search/social platforms can display something different. |
| Growth and rechecks | Prioritized suggestions and supported comparisons with an owned baseline. |

Suggestions need editorial judgment. They do not guarantee visitors, rankings or AI recommendations.

## Search and performance

Authorized Search Console exports can provide real clicks, impressions, CTR and position. The [fictional example CSV](../examples/search-console-queries.csv) demonstrates a format; its rows are not market estimates.

Direct Google connections require operator configuration, consent and property permissions. A setup screen does not mean the provider is connected.

Performance tools must distinguish crawler response timing, official provider results and imported reports. Provider quotas and availability apply. Missing external evidence must remain unavailable.

## Connected-domain tools

[Domain verification](DOMAINS.md) combines a matching verified business email, domain-control proof and an exclusive organization claim.

Eligible users can request a dated score badge and the supported limited security checks. Those checks are not a full penetration test or continuous monitoring.

Dependency advisory lookups disclose package names/versions to OSV after the relevant authorization. Local log analysis is heuristic; do not post logs or private reports publicly.

## Exports and account

Use available CSV/JSON/fix-brief exports and **Crawl history** to return to owned reports. Sign-in uses an independent Sonar account. Workspace deletion and login-account erasure are different operations; read the [privacy notice](https://sonar.pactuno.online/privacy.html).

[Dashboard](DASHBOARD.md) · [Methodology](METHODOLOGY.md) · [FAQ](FAQ.md)
