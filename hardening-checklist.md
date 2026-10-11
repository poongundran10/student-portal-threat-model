# Prioritized Security Hardening Checklist

## Priority 1 — Critical access and account controls
- [ ] Enforce server-side authorization on every protected operation.
- [ ] Verify record ownership for student profile access and updates.
- [ ] Restrict administrator functions with server-side role checks.
- [ ] Store passwords using a modern password-hashing algorithm such as Argon2id.
- [ ] Use HTTPS and secure session cookies (`Secure`, `HttpOnly`, appropriate `SameSite`).
- [ ] Rotate session identifiers after login.

## Priority 2 — Abuse prevention
- [ ] Rate-limit login attempts.
- [ ] Use generic authentication and recovery error messages.
- [ ] Validate input on the server.
- [ ] Use parameterized database queries.
- [ ] Expire sessions and invalidate them at logout.

## Priority 3 — Monitoring and data protection
- [ ] Log important authentication, authorization, and account-change events.
- [ ] Never log passwords, session tokens, or API keys.
- [ ] Apply least privilege to database and log access.
- [ ] Monitor suspicious authentication patterns.
- [ ] Configure request/resource limits and alerting.

## Verification evidence
For each test, record: date, environment, test method, expected result, actual result, and evidence link. Do not mark tests as passed until they have actually been performed in an authorized environment.
