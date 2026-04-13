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
| User AI session hours | 0.0h | 6.0h | 21.3h | 21.3h |
| AI worker hours | 0.6h | 0.6h | 0.6h | 0.6h |
| AI concurrency hours | 0.6h | 13.4h | 38.3h | 38.3h |
| Interactive sessions | 6 | 9 | 18 | 18 |
| Worker sessions | 18 | 18 | 18 | 18 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,071 | 2K | 781K | 386.1M | $1,081.36 | $5,213.59 | $0.00 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| claude-sonnet-4-6 | 171 | 195 | 38K | 14.2M | $9.61 | $38.35 | $19.34 |
| **Total** | **2,637** | **1.8M** | **932K** | **430.1M** | **$1,108.32** | **$5,251.95** | **$100.48** |

_458.1M total tokens processed. 93.9% cache hit rate._

_$5,352.43 total saved ($5,251.95 caching + $100.48 model routing vs all-Opus)._

_Model savings are modest because ~93.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,369 | 4K | 1.4M | 858.4M | $1,397.24 | $11,589.70 | $0.00 |
| claude-sonnet-4-6 | 171 | 195 | 38K | 14.2M | $4.83 | $38.35 | $19.34 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **3,542** | **4K** | **1.4M** | **872.7M** | **$1,402.13** | **$11,628.53** | **$19.34** |

_996.0M total tokens processed. 92.7% cache hit rate._

_$11,647.86 total saved ($11,628.53 caching + $19.34 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-13 07:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
