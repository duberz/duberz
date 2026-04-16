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
| Screen time (Linux) | 0.4h | 24.4h | 24.4h | ~2,796h* |
| User AI session hours | 2.2h | 7.0h | 14.8h | 14.8h |
| AI worker hours | 3.2h | 10.1h | 10.1h | 10.1h |
| AI concurrency hours | 7.5h | 24.9h | 41.4h | 41.4h |
| Interactive sessions | 2 | 61 | 68 | 68 |
| Worker sessions | 29 | 206 | 206 | 206 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,748 | 3K | 1.0M | 508.7M | $1,531.22 | $6,868.18 | $0.00 |
| claude-sonnet-4-6 | 2,651 | 2K | 542K | 169.7M | $103.58 | $458.21 | $236.22 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,794** | **1.8M** | **1.7M** | **708.2M** | **$1,652.15** | **$7,326.39** | **$317.37** |

_760.6M total tokens processed. 93.1% cache hit rate._

_$7,643.76 total saved ($7,326.39 caching + $317.37 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,049 | 5K | 1.7M | 981.0M | $1,602.37 | $13,244.28 | $0.00 |
| claude-sonnet-4-6 | 2,633 | 2K | 541K | 169.5M | $58.96 | $457.67 | $235.92 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **6,684** | **8K** | **2.2M** | **1,150.5M** | **$1,661.39** | **$13,702.42** | **$235.92** |

_1,297.2M total tokens processed. 92.6% cache hit rate._

_$13,938.34 total saved ($13,702.42 caching + $235.92 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-16 19:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
