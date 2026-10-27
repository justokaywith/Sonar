<div align="center">
  <a href="https://sonar.pactuno.online/"><img src="assets/sonar.svg" alt="Sonar by Pactuno" width="96"></a>
  <h1>Sonar — website intelligence, made clear</h1>
  <p><strong>Know your website. See what comes next.</strong></p>
  <p>Free, on-demand website SEO audits. Real page evidence. A clearer next step.</p>
  <p>
    <a href="https://sonar.pactuno.online/"><strong>Open Sonar</strong></a>
    &nbsp;·&nbsp; <a href="docs/QUICKSTART.md">Quick start</a>
    &nbsp;·&nbsp; <a href="docs/TOOLS.md">Explore the tools</a>
    &nbsp;·&nbsp; <a href="https://pactuno.online/blog/">Read the guides</a>
  </p>
  <p>
    <img src="https://img.shields.io/badge/status-early_access-0a84ff" alt="Status: early access">
    <img src="https://img.shields.io/badge/use-free-10213e" alt="Free hosted tool">
    <img src="https://img.shields.io/badge/repository-docs_%26_examples-008baf" alt="Public documentation and examples">
  </p>
</div>

---

![Sonar: inspect a website, understand the evidence and verify the change](assets/sonar-banner.svg)

**Start here:** [Workspace](https://sonar.pactuno.online/) · [First audit](docs/QUICKSTART.md) · [Dashboard](docs/DASHBOARD.md) · [Scoring](docs/METHODOLOGY.md) · [FAQ](docs/FAQ.md) · [Roadmap](ROADMAP.md) · [Contribute](CONTRIBUTING.md)

## Stop collecting warnings. Start understanding them.

A missing title. An unexpected canonical. A useful page with no incoming links in your crawl sample. An audit should help you find the affected URL, understand the evidence and decide what to fix.

Sonar brings that workflow into one hosted workspace: inspect public pages, review technical findings, plan improvements and recheck the published result.

**This is Sonar’s public documentation and community repository.** The hosted application and infrastructure source remain private. You do not need to clone this repository or install a server to use Sonar.

## Dashboard at a glance

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/dashboard-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/dashboard-light.png">
  <img src="assets/dashboard-light.png" alt="Actual Sonar workbench with the website URL field, crawl-scope selector and tool navigation">
</picture>

*Actual public product captures, without signing in or selecting a report. No customer information or invented results. The image follows your GitHub color preference.*

[Dashboard walkthrough →](docs/DASHBOARD.md)

## Run your first audit

1. Open [Sonar](https://sonar.pactuno.online/).
2. Enter a public HTTPS website.
3. Choose **Single page audit**, **Fast crawl · up to 50 pages**, or **Deep crawl · up to 100 pages**.
4. Select **Analyze website**, then review **Issues** and **Page explorer**.
5. Make the change in your own website’s editor or codebase, then recheck it.

Basic audits work without an account. Keep the tab open while crawl steps run; pause/resume controls and **Crawl history** help you continue. The page limit is a maximum sample, not a promise to fetch every page.

[Full quick start and troubleshooting →](docs/QUICKSTART.md)

## What you can do

| Capability | How it helps |
| --- | --- |
| Website crawling | Inspect one page or a bounded, resumable original-HTML site sample. |
| Technical findings | Review affected URLs, evidence and explanations for metadata, indexability, headings, images and selected response signals. |
| Page explorer | Examine what the crawler actually received for an individual URL. |
| Internal-link analysis | Review sampled relationships, depth and orphan candidates before adding useful links. |
| Content and keyword review | Inspect page text, duplicate metadata and heuristic topic/intent signals. |
| Growth and rechecks | Turn findings into a repair plan and compare a follow-up page audit with an owned baseline. |
| Performance reports | Keep crawler response timing separate from official PageSpeed/Lighthouse evidence; provider availability and imports have their own limits. |
| Search performance | Analyze authorized Search Console exports; direct connections depend on configured access and permissions. |
| Comparisons and exports | Compare supported page evidence and export available findings as CSV, JSON or a fix brief. |
| Verified-domain tools | Use domain-control proof and a verified business mailbox for eligible badges and limited owner-authorized security checks. |

[Tool guide, sources and limitations →](docs/TOOLS.md)

## A number should tell you where it came from

| Evidence | What it means | What it does not mean |
| --- | --- | --- |
| Crawled HTML | What Sonar received from pages in this sample | Everything a JavaScript-rendering browser or search engine sees |
| Provider data or imports | Measurements from the stated account, source and period | A global keyword-volume or competitive-traffic database |
| Content and link heuristics | Candidates worth reviewing with context | Proven cannibalization, traffic decay, exploitability or ranking predictions |
| Technical health score | Sonar’s weighted checklist for fetched pages | Google ranking, Ahrefs Domain Rating or a security certification |

Unavailable data stays unavailable. More numbers are not a reason to invent a metric.

[Read the methodology →](docs/METHODOLOGY.md)

## From finding to verified change

~~~mermaid
flowchart LR
    U["Public HTTPS URL"] --> C["Scoped HTML crawl"]
    C --> E["Page evidence and findings"]
    E --> R["Review and prioritize"]
    R --> F["Fix in your own website"]
    F --> V["Recheck the published page"]
~~~

Sonar does not automatically edit your website or guarantee a search result position.

## Sign in when you need a workspace

Create an independent Sonar account with a username, email and password. Sign in with your username or email; this is separate from a Pactuno account.

Business-domain features additionally require a verified matching company mailbox and domain-control proof. An organization claim is exclusive: another claimant is directed to their company administrator.

If the administrator has left, use the documented reclaim process. Support reviews company authority and fresh proof; an email draft does not transfer ownership automatically.

[Domain connection and reclaim guide →](docs/DOMAINS.md)

## A 90+ badge, with evidence

An eligible badge requires:

- A matching verified business email and current domain-control proof.
- Current organization-administrator ownership.
- A completed eligible root-site crawl with no critical findings.
- A server-calculated technical score of at least 90.

Public verification explains the sample, dates and current status. Badges expire within the applicable 60-day freshness window and can become invalid earlier. They are **not** a malware-free seal, independent certification or guarantee against hacking.

[Badge requirements and scoring →](docs/METHODOLOGY.md#badge)

## Learn the workflow, then compare the tools

Sonar articles are published in the **Pactuno Blog**:

- [How to Run a Website SEO Audit](https://pactuno.online/blog/website-seo-audit-guide)
- [How to Find and Fix Orphan Pages](https://pactuno.online/blog/find-fix-orphan-pages)
- [Sonar vs Ahrefs vs Semrush: SEO Guide](https://pactuno.online/blog/sonar-vs-ahrefs-semrush)

The comparison explains where a focused crawler fits and where an external research index is needed. Sonar does not claim dataset or feature parity with Ahrefs or Semrush.

## Clear limits, from the start

Sonar is early access. Crawls have shared capacity, time, page and storage safeguards. They read original HTML and do not execute website JavaScript.

Sonar does not operate a global backlink index, global keyword-volume database or arbitrary competitor-traffic feed. Limited security checks are not a penetration test or continuous attack monitoring. Integrations can require operator configuration, permissions and provider quota.

[FAQ](docs/FAQ.md) · [Roadmap](ROADMAP.md) · [Privacy](https://sonar.pactuno.online/privacy.html)

## Help make Sonar easier to use

- [Report a reproducible problem](https://github.com/justokaywith/Sonar/issues/new?template=bug.yml)
- [Suggest a feature](https://github.com/justokaywith/Sonar/issues/new?template=feature.yml)
- [Improve a guide](docs/CONTRIBUTOR-QUICKSTART.md)
- [Report a vulnerability privately](https://github.com/justokaywith/Sonar/security/advisories/new)

No subscription or private account access is needed to contribute documentation. Use fictional examples and redact screenshots. Never post credentials, verification files, private scans or customer logs.

[Contributing](CONTRIBUTING.md) · [Code of conduct](CODE_OF_CONDUCT.md) · [Security policy](SECURITY.md) · [Documentation/example license](LICENSE)

If Sonar helps you, star this repository to follow its progress.

Built by [Pactuno](https://pactuno.online/), alongside [Relay](https://relay.pactuno.online/) and [Blackout](https://pactuno.online/blackout.html).
