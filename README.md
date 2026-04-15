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
| User AI session hours | 3.7h | 7.8h | 13.5h | 13.5h |
| AI worker hours | 2.7h | 7.2h | 7.2h | 7.2h |
| AI concurrency hours | 8.7h | 22.7h | 35.9h | 35.9h |
| Interactive sessions | 21 | 61 | 67 | 67 |
| Worker sessions | 61 | 183 | 183 | 183 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,596 | 3K | 987K | 482.9M | $1,415.69 | $6,519.20 | $0.00 |
| claude-sonnet-4-6 | 2,074 | 2K | 423K | 132.8M | $82.96 | $358.62 | $184.85 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,065** | **1.8M** | **1.5M** | **645.4M** | **$1,516.00** | **$6,877.82** | **$266.00** |

_691.8M total tokens processed. 93.3% cache hit rate._

_$7,143.82 total saved ($6,877.82 caching + $266.00 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,896 | 4K | 1.6M | 955.2M | $1,557.73 | $12,895.31 | $0.00 |
| claude-sonnet-4-6 | 2,074 | 2K | 424K | 132.8M | $46.22 | $358.78 | $184.94 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,972** | **7K** | **2.0M** | **1,088.1M** | **$1,604.01** | **$13,254.56** | **$184.94** |

_1,229.6M total tokens processed. 92.6% cache hit rate._

_$13,439.50 total saved ($13,254.56 caching + $184.94 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-15 21:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
