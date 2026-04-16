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
| User AI session hours | 2.3h | 6.7h | 14.5h | 14.5h |
| AI worker hours | 3.4h | 10.1h | 10.1h | 10.1h |
| AI concurrency hours | 7.6h | 24.4h | 40.9h | 40.9h |
| Interactive sessions | 2 | 60 | 67 | 67 |
| Worker sessions | 34 | 206 | 206 | 206 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,705 | 3K | 1.0M | 502.3M | $1,508.19 | $6,782.12 | $0.00 |
| claude-sonnet-4-6 | 2,651 | 2K | 542K | 169.7M | $103.58 | $458.21 | $236.22 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,751** | **1.8M** | **1.6M** | **701.8M** | **$1,629.12** | **$7,240.33** | **$317.37** |

_753.6M total tokens processed. 93.1% cache hit rate._

_$7,557.70 total saved ($7,240.33 caching + $317.37 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,004 | 5K | 1.7M | 974.6M | $1,591.20 | $13,158.23 | $0.00 |
| claude-sonnet-4-6 | 2,633 | 2K | 541K | 169.5M | $58.96 | $457.67 | $235.92 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **6,639** | **8K** | **2.2M** | **1,144.2M** | **$1,650.22** | **$13,616.37** | **$235.92** |

_1,290.2M total tokens processed. 92.6% cache hit rate._

_$13,852.29 total saved ($13,616.37 caching + $235.92 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-16 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
