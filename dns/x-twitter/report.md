# X-Twitter DNS Maintenance Report

Generated: `2026-08-28T08:21:44Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 32 |
| Pending | 0 |
| Suspect | 408 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 26 |
| Unknown | 0 |
| Suspect | 6 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **32**
Average stability: **81.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 5 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `mx3.twitter.com` | suspect | `2026-08-21T12:31:52Z` | 25 | TIMEOUT | 199.59.148.207 | 0.0 | 25 |
| `mx4.twitter.com` | suspect | `2026-08-21T12:31:52Z` | 25 | TIMEOUT | 199.16.156.115 | 0.0 | 25 |
| `r.twimg.com` | suspect | `2026-08-21T09:44:03Z` | 26 | TIMEOUT | 104.244.42.73, 104.244.42.9 | 0.0 | 26 |
| `syndication-o.twimg.com` | suspect | `2026-08-21T09:44:03Z` | 26 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 26 |
| `syndication.twimg.com` | suspect | `2026-08-21T09:44:03Z` | 26 | TIMEOUT | 104.244.42.136, 104.244.42.200, 104.244.42.72 | 0.0 | 26 |
| `www.t.co` | suspect | `2026-08-21T09:44:03Z` | 26 | TLS_ERROR | 162.159.140.229, 172.66.0.227 | 0.0 | 26 |

## Discovery

Discovery state updated: `2026-08-28T08:21:44Z`

## Notes

- Public active DNS file: `X-Twitter_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
