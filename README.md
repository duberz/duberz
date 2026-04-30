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
| Screen time (Linux) | 0.5h | 0.5h | 48.5h | ~3,398h* |
| User AI session hours | 2.4h | 6.8h | 15.3h | 15.3h |
| AI worker hours | 0.0h | 3.4h | 3.6h | 3.6h |
| AI concurrency hours | 3.5h | 13.6h | 25.5h | 25.5h |
| Interactive sessions | 2 | 2 | 3 | 3 |
| Worker sessions | 0 | 101 | 104 | 104 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,696 | 4K | 1.4M | 701.3M | $2,121.36 | $9,467.72 | $0.00 |
| claude-sonnet-4-6 | 4,094 | 4K | 858K | 261.6M | $177.80 | $706.45 | $365.55 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **8,185** | **1.8M** | **2.4M** | **992.7M** | **$2,316.51** | **$10,174.18** | **$446.69** |

_1,071.5M total tokens processed. 92.6% cache hit rate._

_$10,620.87 total saved ($10,174.18 caching + $446.69 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 5,184 | 6K | 2.1M | 1,186.9M | $1,945.12 | $16,023.93 | $0.00 |
| claude-sonnet-4-6 | 4,018 | 4K | 857K | 261.4M | $91.29 | $705.91 | $365.22 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **9,204** | **11K** | **3.0M** | **1,448.4M** | **$2,036.47** | **$16,730.31** | **$365.22** |

_1,618.3M total tokens processed. 92.6% cache hit rate._

_$17,095.53 total saved ($16,730.31 caching + $365.22 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-30 16:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
