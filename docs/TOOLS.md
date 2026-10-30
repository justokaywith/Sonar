# Sonar Tool & Evidence Guide

Access the hosted workbench at [sonar.pactuno.online](https://sonar.pactuno.online/). This repository provides documentation, architectural guides, and verification references.

---

## 1. Audit & Page Evidence Tools

| Tool Area | Scope & Inspection Targets |
| --- | --- |
| **Overview / Site Crawl** | Evaluates overall site health, crawl sample size, technical score, and edge response metrics. |
| **Issues Engine** | Highlights affected URLs with explicit evidence blocks and suggested engineering remediation. |
| **Page Explorer** | Deep inspection of raw returned HTML: metadata, heading structure, links, media, and response headers. |
| **Robots & Sitemap** | Parses crawl access rules, XML sitemap locations, and discovery directives. |
| **HTTP & Security** | Evaluates Content-Security-Policy (CSP), Strict-Transport-Security (HSTS), referrer policies, and mixed-content risks. |

Crawl modes include single-page audits, fast crawls up to 50 pages, and deep crawls up to 100 pages. The crawler evaluates original server-rendered HTML without client-side JavaScript execution.

---

## 2. Standards Triad & AI Intelligence Tools

| Tool Area | Primary Function |
| --- | --- |
| **Standards Triad** | Comprehensive dashboard evaluating domain composite authority across CiteRank, Information Gain, and Update Resilience. |
| **CiteRank (CR) Audit** | Evaluates Generative Engine Optimization (GEO): AI machine legibility, nested JSON-LD schema graphs, atomic Q&A structures, and `/llms.txt` presence. |
| **Information Gain (IGS)** | Audits content novelty delta, empirical calculations, and primary citations against Google Patent US 10,795,944 to defeat commodity AI summaries. |
| **Update Resilience (URI)** | Evaluates algorithmic stability: orphan page detection, canonical chain integrity, and server edge response velocity. |

---

## 3. Speed, Performance & Search Intelligence

| Tool Area | Technical Metrics |
| --- | --- |
| **Core Web Vitals Engine** | Sub-2-second edge diagnostic engine measuring FCP, LCP, CLS, TBT, Speed Index, and TTFB across Mobile (4G) and Desktop profiles. |
| **Competitor Benchmarking** | Side-by-side head-to-head comparison of two domains on technical health, edge latency, indexability, and content density. |
| **Search Console Integration** | Securely imports authorized Google Search Console metrics (clicks, impressions, CTR, position) to correlate ranking shifts with technical audits. |
| **SERP & Social Previews** | Previews live Google SERP snippet representations and Open Graph social sharing cards. |

---

## 4. Connected Domain Tools & Badging

Claiming domain control on Sonar provides access to cryptographic badging and verified organization workflows:

1. **Domain Verification**: Verify origin control by placing a token at `/.well-known/sonar-verification.txt`.
2. **Authority Badges**: Generates dynamically served SVG badges (compact `310x54` or full `270x156` cards) displaying verified CiteRank, Information Gain, and Resilience scores.
3. **Limited Security Inspections**: Owner-consented inspection of transport security, open security headers, and package dependency CVE lookups via OSV.

---

## 5. Export Formats & Workspaces

- **CSV / JSON Exports**: Export full page lists, link graphs, and technical findings for client reporting or internal ticketing.
- **Fix Briefs**: Generate markdown-formatted remediation briefs ready to paste into GitHub issues or Jira tickets.
- **Crawl History**: Access previously completed scans and compare performance over time.

[Return to Dashboard Guide](DASHBOARD.md) · [Scoring Methodology](METHODOLOGY.md) · [FAQ](FAQ.md)
