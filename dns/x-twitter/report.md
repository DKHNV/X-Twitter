# X-Twitter DNS Maintenance Report

Generated: `2026-09-01T10:54:16Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 32 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 408 |
| Expired | 0 |

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
| TIMEOUT | 5 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `mx3.twitter.com` | dead | `2026-08-21T12:31:52Z` | 38 | TIMEOUT | 199.59.148.207 | 0.0 | 38 |
| `mx4.twitter.com` | dead | `2026-08-21T12:31:52Z` | 38 | TIMEOUT | 199.16.156.115 | 0.0 | 38 |
| `r.twimg.com` | dead | `2026-08-21T09:44:03Z` | 39 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 39 |
| `syndication-o.twimg.com` | dead | `2026-08-21T09:44:03Z` | 39 | TIMEOUT | 104.244.42.137, 104.244.42.201, 104.244.42.73 | 0.0 | 39 |
| `syndication.twimg.com` | dead | `2026-08-21T09:44:03Z` | 39 | TIMEOUT | 104.244.42.136, 104.244.42.72, 104.244.42.8 | 0.0 | 39 |
| `www.t.co` | dead | `2026-08-21T09:44:03Z` | 39 | TLS_ERROR | 162.159.140.229, 172.66.0.227 | 0.0 | 39 |

## Discovery

Discovery state updated: `2026-09-01T10:54:16Z`

## Notes

- Public active DNS file: `X-Twitter_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
