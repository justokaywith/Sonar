# Evidence, score and limits

Sonar checks original HTML and selected public response headers. Individual checks have declared weights. Passing checks earn their weight, notices earn 70%, warnings/errors earn zero. Failed page fetches count as zero; scores are not floored to make them look better.

A site run is a sample of at most 25 pages, depth four, with bounded discovery, request time/body size and report storage. The safe report budget can end it earlier; the report states that limit. Robots rules are respected. External links not fetched are not falsely certified as working. A page with no incoming sampled links is an orphan candidate, not proof of a site-wide orphan.

On-page keyword overlap is not proven cannibalization. Content age is not measured search-traffic decay. Search Console imports contain the user's real metrics; no global competitor estimates are invented.

## Badge
Requires a completed eligible root site crawl, score at least 90, no critical findings, matching verified business email, exact-origin domain-control file proof and current organization administrator ownership. Score is calculated server-side, not accepted from the client. Badge records expire after seven days, and newer completed site crawls invalidate older badges. Public verification exposes only origin, sample count, score and dates. It is not a security seal.

## Security scope
Limited owner-authorized checks read public response headers and use HEAD for three fixed exposure candidates, with a missing-path control. Secret bodies are not downloaded. No SQL payload injection, password attack, exploit execution, database access or active broad scanner is performed. Dependency advisories use [OSV](https://osv.dev/). Local log heuristics are not continuous monitoring or breach confirmation.

## Privacy and quotas
See the live [privacy notice](https://sonar.pactuno.online/privacy.html). Private reports are owner-scoped. Sessions use opaque Secure/HttpOnly cookies. Local Search Console/log imports remain in the browser. Stored reports are retained up to 30 days, subject to storage limits. The daily cleanup job also expires old sessions. The owner can delete Sonar workspace data without deleting their Pactuno account.

Current free safeguards include five crawl starts per minute per hashed IP, a shared 200-start daily budget and 50 active runs. These are abuse safeguards, not an unlimited service promise.

## Standards references
- [Google Search Essentials](https://developers.google.com/search/docs/essentials)
- [Google Core Web Vitals](https://developers.google.com/search/docs/appearance/core-web-vitals)
- [PageSpeed Insights API](https://developers.google.com/speed/docs/insights/v5/get-started)
- [OWASP Secure Headers](https://owasp.org/www-project-secure-headers/)

This repository does not claim the global datasets of [Ahrefs](https://ahrefs.com/) or [Semrush](https://www.semrush.com/), or claim competitors lack a feature without current evidence.
