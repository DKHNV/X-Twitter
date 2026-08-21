# X-Twitter DNS Maintenance Report

Generated: `2026-08-21T09:44:03Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 28 |
| Pending | 134 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 24 |
| Unknown | 4 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **28**
Average stability: **85.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `r.twimg.com` | unknown | `2026-08-21T09:44:03Z` | 1 | TIMEOUT | 104.244.42.137, 104.244.42.9 | 0.0 | 1 |
| `syndication-o.twimg.com` | unknown | `2026-08-21T09:44:03Z` | 1 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 1 |
| `syndication.twimg.com` | unknown | `2026-08-21T09:44:03Z` | 1 | TIMEOUT | 104.244.42.136, 104.244.42.72, 104.244.42.8 | 0.0 | 1 |
| `www.t.co` | unknown | `2026-08-21T09:44:03Z` | 1 | TLS_ERROR | 162.159.140.229, 172.66.0.227 | 0.0 | 1 |

## Discovery

Discovery state updated: `2026-08-21T09:44:03Z`

## Notes

- Public active DNS file: `X-Twitter_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
