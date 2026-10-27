# Your first Sonar audit

No installation or repository clone is required. Open [Sonar](https://sonar.pactuno.online/) in a modern browser.

## 1. Choose a useful starting point

Enter a public HTTPS website. Use a site you own or are authorized to review. Local hosts, private/IP targets, credentials in URLs and nonstandard ports are rejected.

Choose the scope shown in the live workspace:

- **Single page audit:** investigate one address.
- **Fast crawl · up to 50 pages:** begin with a smaller site sample.
- **Deep crawl · up to 100 pages:** examine a larger bounded sample.

Select **Analyze website**. Fewer pages can be fetched because of discovery, robots rules, failures or shared limits. Read the report notes.

## 2. Review evidence

Start with **Issues**, then open **Page explorer** for the affected URL. Distinguish fetch failures, intentional indexing choices and editorial improvements.

A crawl reads original HTML; it does not execute website JavaScript. A missing link in the sample is a candidate to investigate, not proof that no link exists anywhere.

## 3. Fix and recheck

Export the available CSV, JSON or fix brief. Make the change using your own website editor or codebase, deploy it, and run a comparable follow-up audit. Growth/recheck tools help review the change; Sonar does not automatically rewrite your site.

Keep the tab open while crawl steps run. Use Pause/Resume and **Crawl history** rather than repeatedly starting the same crawl.

## Optional: keep a workspace

Create an independent Sonar account with a username, email, password and confirmation. Password fields provide visibility controls and live rule/match feedback. Sign in with username or email and password; Sonar does not require a Pactuno account or MFA.

The current password rule is 12–128 characters with uppercase/lowercase letters, a number and a special character. Forgotten-password recovery uses a single-use expiring link. Business-domain features additionally require email verification and domain-control proof.

## Troubleshooting

| Situation | What to do |
| --- | --- |
| Crawl paused | Reopen the workspace/history and choose Resume where available. |
| Sample smaller than the selected limit | Read robots/discovery/error/limit notes; the limit is a maximum. |
| Speed result unavailable | Use the official PageSpeed workflow or supported report import. Missing provider evidence is not a passing result. |
| Search Console not ready | Follow the live setup guidance. Operator configuration and Google permissions are required; local export analysis is separate. |
| Domain already claimed | Contact your organization administrator or follow [reclaim](DOMAINS.md). |
| Verification file fails | Publish the exact generated file on the exact public origin; review the displayed requirements. |

Never put credentials, private customer records or secret verification files in public issues.

[Dashboard guide](DASHBOARD.md) · [Tool guide](TOOLS.md) · [FAQ](FAQ.md)
