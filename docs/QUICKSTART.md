# First audit

1. Visit https://sonar.pactuno.online/.
2. Paste a public HTTPS URL. Private IPs, local hosts, credential-bearing URLs and nonstandard ports are rejected.
3. Choose **Single page audit** for one URL, or **Site crawl · up to 25 pages**.
4. Leave the page open while resumable steps run. Closing the tab pauses work; this is not an unattended crawler.
5. Inspect **Issues**, expand a finding, then use **Page explorer** for its page evidence.
6. Download CSV/JSON or a fix brief. Apply changes in your site's own publishing workflow.
7. Open **Growth & recheck** for a fresh single-page comparison.

## Sign in
Use your verified Pactuno account. Accounts with authenticator MFA must complete that challenge. Passwords and codes are not saved by Sonar. Anonymous reports in the current browser session move to the verified account after successful sign-in.

## Common problems
- **Crawl paused:** keep the tab open and resume from history.
- **Fewer than 25 pages:** robots rules, discovery, errors or the safe report budget can stop the sample earlier. Read its notes.
- **Speed data unavailable:** PageSpeed has its own quotas. An unavailable request is not a passing speed result.
- **Domain already claimed:** contact the company administrator, or use the documented reclaim workflow.
- **Verification failed:** publish the exact generated file on the exact origin, reachable publicly without a redirect to another host.

Do not put passwords, customer records or private keys into any import.
