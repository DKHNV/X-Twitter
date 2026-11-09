# X-Twitter DNS Maintenance Report

Generated: `2026-11-09T22:48:50Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 32 |
| Pending | 0 |
| Suspect | 21 |
| Quarantine | 263 |
| Excluded | 0 |
| Expired | 142 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 26 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 6 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **32**
Average stability: **81.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| MULTIPLE | 1 |
| TIMEOUT | 5 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `mx3.twitter.com` | dead | `2026-08-21T12:31:52Z` | 289 | TIMEOUT | 199.59.148.207 | 0.0 | 38 |
| `mx4.twitter.com` | dead | `2026-08-21T12:31:52Z` | 289 | TIMEOUT | 199.16.156.115 | 0.0 | 38 |
| `r.twimg.com` | dead | `2026-08-21T09:44:03Z` | 290 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 38 |
| `syndication-o.twimg.com` | dead | `2026-08-21T09:44:03Z` | 290 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 38 |
| `syndication.twimg.com` | dead | `2026-08-21T09:44:03Z` | 290 | TIMEOUT | 104.244.42.136, 104.244.42.200, 104.244.42.72 | 0.0 | 38 |
| `www.t.co` | dead | `2026-08-21T09:44:03Z` | 290 | MULTIPLE | 151.101.194.146, 162.159.140.229 | 0.0 | 38 |

## Discovery

Discovery state updated: `2026-11-09T22:48:50Z`

## Notes

- Public active DNS file: `X-Twitter_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
