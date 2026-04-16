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
| Screen time (Linux) | 24h | 24h | 24h | ~2,796h* |
| User AI session hours | 3.4h | 7.0h | 13.8h | 13.8h |
| AI worker hours | 3.1h | 7.9h | 7.9h | 7.9h |
| AI concurrency hours | 8.9h | 22.2h | 37.6h | 37.6h |
| Interactive sessions | 17 | 61 | 67 | 67 |
| Worker sessions | 53 | 186 | 186 | 186 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,643 | 3K | 1.0M | 495.4M | $1,464.81 | $6,688.55 | $0.00 |
| claude-sonnet-4-6 | 2,205 | 2K | 452K | 141.7M | $87.34 | $382.85 | $197.31 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,243** | **1.8M** | **1.5M** | **666.9M** | **$1,569.50** | **$7,071.40** | **$278.46** |

_715.3M total tokens processed. 93.2% cache hit rate._

_$7,349.85 total saved ($7,071.40 caching + $278.46 model routing vs all-Opus)._

_Model savings are modest because ~93.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,942 | 5K | 1.6M | 967.7M | $1,578.42 | $13,064.65 | $0.00 |
| claude-sonnet-4-6 | 2,198 | 2K | 451K | 141.5M | $49.23 | $382.31 | $197.01 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **6,142** | **7K** | **2.1M** | **1,109.3M** | **$1,627.71** | **$13,447.43** | **$197.01** |

_1,252.6M total tokens processed. 92.6% cache hit rate._

_$13,644.45 total saved ($13,447.43 caching + $197.01 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-16 01:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
