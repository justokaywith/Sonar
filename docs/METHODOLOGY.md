# Evidence, score and limits

Sonar reads original returned HTML and selected public response signals. It does not execute the target website's JavaScript. A report describes the pages actually fetched, not every page that might exist.

## Technical score

Each applicable check has a weight:

- Pass: full weight.
- Notice: 70% of its weight.
- Warning or error: zero.
- Failed HTTP page fetch: a page score of zero.

A page score is 100 × earned weight ÷ available weight. The site score is the rounded average of fetched page scores. Pages are normalized separately, so dividing combined raw weights may give a different result.

The score is not Google ranking, Ahrefs Domain Rating, a visitor count or a security certification. Changing the sample can change the average without changing any individual page.

[Public scoring explanation](https://sonar.pactuno.online/methodology/)

## Crawl scope

The current UI offers single-page audits, a fast crawl up to 50 pages and a deep crawl up to 100 pages. Site discovery is bounded by depth, robots rules, time/body/storage budgets and shared capacity.

A smaller sample can be valid. Read the notes and use comparable scopes when rechecking. Closing the tab pauses client-driven crawl work; it is not an unattended crawler.

A missing incoming link makes a page an orphan candidate within the sample. It is not proof that no link exists on another page or after rendering.

## Separate sources stay separate

- On-page word frequency is not measured search demand.
- Keyword overlap is not proven cannibalization.
- Content age is not measured traffic decay.
- Crawler response timing is not a Core Web Vital.
- Authorized Search Console data describes the stated property and period.
- Imported data retains its source and coverage limits.
- PageSpeed/Lighthouse evidence must come from the stated provider or supplied report.
- Provider failure is unavailable evidence, not a passing score.

Sonar does not operate a global backlink or keyword-volume database. Draft previews do not guarantee the search engine's final appearance.

## Badge

An eligible badge requires a completed root-site crawl, a score at least 90, no critical findings, matching verified business email, exact-origin domain-control proof and current organization-administrator ownership.

The server calculates eligibility. The public record exposes the origin, score, sample and dates. Audit/proof freshness bounds expiry to at most 60 days; a newer completed crawl or a changed claim can invalidate the badge earlier.

A badge is not an independent certification, malware-free claim or guarantee against hacking. Read its current verification record rather than relying only on a copied image.

## Security scope

Limited, owner-authorized checks inspect public signals and fixed exposure candidates. Secret response bodies are not downloaded by those checks. No password attack, exploit execution or broad active penetration test is provided.

Supported dependency advisory lookups use [OSV](https://osv.dev/). A lookup failure does not mean a package is safe. Local log heuristics do not establish that a breach has or has not occurred.

## Privacy and resource limits

Private reports are owner-scoped. Independent Sonar accounts use username/email/password; passwords use salted scrypt and sessions use opaque Secure/HttpOnly cookies. Business-domain actions additionally require verified mailbox ownership.

Supported local imports stay in the browser unless a flow explicitly describes an external request. Never upload private information to GitHub.

Report retention and shared capacity are bounded. Workspace-data deletion does not automatically delete the separate Sonar login account. See the [live privacy notice](https://sonar.pactuno.online/privacy.html) and contact support for account erasure.

## References

- [Google Search Essentials](https://developers.google.com/search/docs/essentials)
- [Google Core Web Vitals](https://developers.google.com/search/docs/appearance/core-web-vitals)
- [OWASP Secure Headers](https://owasp.org/www-project-secure-headers/)

[Quick start](QUICKSTART.md) · [Tool guide](TOOLS.md) · [Domain requirements](DOMAINS.md)
