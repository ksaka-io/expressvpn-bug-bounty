# ExpressVPN Bug Bounty — Responsible Disclosure

Responsible disclosure of a security vulnerability in ExpressVPN — rewarded with official bug bounty

**Researcher:** Territory (Karlos Saka)
**Severity:** High
**Status:** Resolved / Acknowledged
**Bounty:** $300

## Summary

Discovered an authentication vulnerability in the ExpressVPN client application 
that allowed unauthorized access using valid license keys obtained externally, 
bypassing password validation entirely. The flaw stemmed from insufficient 
server-side credential verification during the login flow.

## Impact

An attacker with a valid activation key could authenticate without knowing the 
account password, potentially accessing a paid account without authorization.

## Disclosure Timeline

- Vulnerability discovered and documented
- Reported directly to ExpressVPN security team
- Acknowledged and confirmed by ExpressVPN
- Bounty awarded: $300
- Issue resolved

## Notes

Disclosed responsibly. No user data was accessed during testing.
