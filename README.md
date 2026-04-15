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
| User AI session hours | 2.4h | 7.6h | 12.2h | 12.2h |
| AI worker hours | 2.7h | 7.0h | 7.0h | 7.0h |
| AI concurrency hours | 6.6h | 22.3h | 33.6h | 33.6h |
| Interactive sessions | 23 | 61 | 67 | 67 |
| Worker sessions | 63 | 177 | 177 | 177 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,526 | 3K | 969K | 464.8M | $1,366.16 | $6,274.85 | $0.00 |
| claude-sonnet-4-6 | 2,009 | 2K | 409K | 129.0M | $80.55 | $348.51 | $179.52 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **4,930** | **1.8M** | **1.4M** | **623.6M** | **$1,464.06** | **$6,623.36** | **$260.66** |

_668.6M total tokens processed. 93.3% cache hit rate._

_$6,884.02 total saved ($6,623.36 caching + $260.66 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,825 | 4K | 1.6M | 937.1M | $1,529.24 | $12,650.95 | $0.00 |
| claude-sonnet-4-6 | 2,011 | 2K | 410K | 129.1M | $44.89 | $348.68 | $179.61 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,838** | **7K** | **2.0M** | **1,066.2M** | **$1,574.19** | **$13,000.10** | **$179.61** |

_1,206.4M total tokens processed. 92.6% cache hit rate._

_$13,179.71 total saved ($13,000.10 caching + $179.61 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-15 19:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
