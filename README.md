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
| User AI session hours | 1.5h | 6.9h | 19.6h | 19.6h |
| AI worker hours | 2.3h | 4.7h | 4.7h | 4.7h |
| AI concurrency hours | 7.5h | 20.1h | 41.7h | 41.7h |
| Interactive sessions | 22 | 44 | 50 | 50 |
| Worker sessions | 63 | 127 | 127 | 127 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,391 | 3K | 907K | 434.3M | $1,275.60 | $5,863.12 | $0.00 |
| claude-sonnet-4-6 | 1,377 | 1K | 284K | 92.6M | $58.02 | $250.12 | $128.25 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **4,163** | **1.8M** | **1.3M** | **556.6M** | **$1,350.97** | **$6,113.23** | **$209.39** |

_596.7M total tokens processed. 93.3% cache hit rate._

_$6,322.63 total saved ($6,113.23 caching + $209.39 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,690 | 4K | 1.5M | 906.6M | $1,478.86 | $12,239.22 | $0.00 |
| claude-sonnet-4-6 | 1,378 | 1K | 284K | 92.6M | $32.05 | $250.12 | $128.25 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,070** | **6K** | **1.8M** | **999.2M** | **$1,510.97** | **$12,489.81** | **$128.25** |

_1,134.6M total tokens processed. 92.6% cache hit rate._

_$12,618.06 total saved ($12,489.81 caching + $128.25 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-14 23:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
