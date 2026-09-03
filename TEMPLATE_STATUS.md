# Template Status & Verification

**Classification:** Configurable n8n template asset — not a verified production deployment.

The workflow export and documentation are inspectable template evidence. They do not prove a configured production X/Twitter scheduler, engagement result, SLA, ROI, or client outcome.

## Verification gate
1. Parse/import into a clean current n8n instance.
2. Inspect schedule/wait behavior, posting actions, engagement logic, branches, expressions, and Code nodes.
3. Replace placeholder platform credentials, user/account IDs, schedules, URLs, webhooks, and resource references.
4. Confirm current X/Twitter API access tier, posting endpoints, rate limits, and automation policies.
5. Run scheduled-post, invalid-content, auth-expiry, rate-limit, replay, and provider-failure cases.
6. Verify no duplicate posts and record configured test date/result.

## Security
Never commit platform tokens, OAuth secrets, private account data, draft content credentials, or production webhooks. Use controlled test credentials where permitted.

## Change record
- **2026-09-03:** Added repository verification/security/status control. No provider-policy validation or runtime pass is implied.
