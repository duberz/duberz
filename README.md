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
| Screen time (Linux) | 24h | 24h | 48h | ~3,398h* |
| User AI session hours | 0.3h | 2.4h | 17.0h | 17.0h |
| AI worker hours | 0.2h | 3.4h | 11.6h | 11.6h |
| AI concurrency hours | 0.6h | 7.3h | 40.4h | 40.4h |
| Interactive sessions | 1 | 2 | 45 | 45 |
| Worker sessions | 6 | 101 | 253 | 253 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,514 | 4K | 1.3M | 642.9M | $1,941.34 | $8,680.11 | $0.00 |
| claude-sonnet-4-6 | 3,755 | 4K | 787K | 240.6M | $156.40 | $649.76 | $336.07 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **7,664** | **1.8M** | **2.2M** | **913.3M** | **$2,115.09** | **$9,329.87** | **$417.22** |

_983.6M total tokens processed. 92.9% cache hit rate._

_$9,747.08 total saved ($9,329.87 caching + $417.22 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,815 | 6K | 2.0M | 1,115.2M | $1,828.44 | $15,056.21 | $0.00 |
| claude-sonnet-4-6 | 3,703 | 4K | 786K | 240.4M | $83.93 | $649.21 | $335.75 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **8,520** | **10K** | **2.8M** | **1,355.7M** | **$1,912.43** | **$15,705.90** | **$335.75** |

_1,517.9M total tokens processed. 92.7% cache hit rate._

_$16,041.65 total saved ($15,705.90 caching + $335.75 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-28 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
