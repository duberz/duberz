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
| Screen time (Linux) | 1.2h | 24h | 48h | ~3,048h* |
| User AI session hours | 0.6h | 10.7h | 15.1h | 15.1h |
| AI worker hours | 0.0h | 3.4h | 10.1h | 10.1h |
| AI concurrency hours | 1.0h | 19.2h | 36.0h | 36.0h |
| Interactive sessions | 1 | 3 | 61 | 61 |
| Worker sessions | 0 | 34 | 206 | 206 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,274 | 4K | 1.2M | 609.0M | $1,828.94 | $8,221.96 | $0.00 |
| claude-sonnet-4-6 | 2,651 | 2K | 542K | 169.7M | $103.58 | $458.21 | $236.22 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **6,320** | **1.8M** | **1.9M** | **808.4M** | **$1,949.87** | **$8,680.17** | **$317.37** |

_868.1M total tokens processed. 93.1% cache hit rate._

_$8,997.54 total saved ($8,680.17 caching + $317.37 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,575 | 5K | 1.9M | 1,081.3M | $1,770.10 | $14,598.06 | $0.00 |
| claude-sonnet-4-6 | 2,633 | 2K | 541K | 169.5M | $58.96 | $457.67 | $235.92 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **7,210** | **8K** | **2.5M** | **1,250.8M** | **$1,829.12** | **$15,056.20** | **$235.92** |

_1,404.7M total tokens processed. 92.7% cache hit rate._

_$15,292.12 total saved ($15,056.20 caching + $235.92 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-22 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
