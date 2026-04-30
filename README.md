# duberz

![Astro](https://img.shields.io/badge/-Astro-555555?style=flat-square)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 1.5h | 1.5h | 49.5h | ~3,398h* |
| User AI session hours | 3.0h | 7.2h | 16.0h | 16.0h |
| AI worker hours | 0.0h | 3.4h | 3.4h | 3.4h |
| AI concurrency hours | 4.6h | 14.4h | 26.7h | 26.7h |
| Interactive sessions | 2 | 2 | 3 | 3 |
| Worker sessions | 0 | 101 | 101 | 101 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,718 | 4K | 1.4M | 704.6M | $2,123.49 | $9,512.14 | $0.00 |
| claude-sonnet-4-6 | 4,095 | 4K | 858K | 261.6M | $178.06 | $706.45 | $365.55 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **8,208** | **1.8M** | **2.4M** | **995.9M** | **$2,318.90** | **$10,218.59** | **$446.70** |

_1,074.6M total tokens processed. 92.7% cache hit rate._

_$10,665.29 total saved ($10,218.59 caching + $446.70 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 5,301 | 6K | 2.2M | 1,202.0M | $1,970.70 | $16,227.04 | $0.00 |
| claude-sonnet-4-6 | 4,018 | 4K | 857K | 261.4M | $91.29 | $705.91 | $365.22 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **9,321** | **11K** | **3.0M** | **1,463.4M** | **$2,062.05** | **$16,933.43** | **$365.22** |

_1,633.6M total tokens processed. 92.7% cache hit rate._

_$17,298.65 total saved ($16,933.43 caching + $365.22 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-30 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
