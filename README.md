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
| User AI session hours | 1.0h | 5.9h | 18.4h | 18.4h |
| AI worker hours | 2.4h | 4.0h | 4.0h | 4.0h |
| AI concurrency hours | 6.5h | 18.1h | 38.7h | 38.7h |
| Interactive sessions | 21 | 38 | 43 | 43 |
| Worker sessions | 63 | 105 | 105 | 105 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,221 | 2K | 835K | 404.0M | $1,195.19 | $5,454.46 | $0.00 |
| claude-sonnet-4-6 | 1,155 | 1K | 241K | 80.4M | $50.20 | $217.15 | $110.99 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **3,771** | **1.8M** | **1.1M** | **514.2M** | **$1,262.74** | **$5,671.60** | **$192.14** |

_551.6M total tokens processed. 93.2% cache hit rate._

_$5,863.74 total saved ($5,671.60 caching + $192.14 model routing vs all-Opus)._

_Model savings are modest because ~93.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,521 | 4K | 1.5M | 876.3M | $1,428.02 | $11,830.56 | $0.00 |
| claude-sonnet-4-6 | 1,156 | 1K | 241K | 80.4M | $27.73 | $217.15 | $110.99 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **4,679** | **5K** | **1.7M** | **956.7M** | **$1,455.81** | **$12,048.18** | **$110.99** |

_1,089.4M total tokens processed. 92.5% cache hit rate._

_$12,159.17 total saved ($12,048.18 caching + $110.99 model routing vs all-Opus)._

_Model savings are modest because ~92.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-14 16:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
