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
| Screen time (Linux) | 4.5h | 4.5h | 52.5h | ~3,398h* |
| User AI session hours | 1.6h | 8.1h | 8.8h | 8.8h |
| AI worker hours | 0.0h | 3.4h | 3.4h | 3.4h |
| AI concurrency hours | 2.9h | 15.9h | 17.1h | 17.1h |
| Interactive sessions | 2 | 2 | 2 | 2 |
| Worker sessions | 0 | 101 | 101 | 101 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,725 | 4K | 1.4M | 700.6M | $2,117.13 | $9,458.19 | $0.00 |
| claude-sonnet-4-6 | 4,122 | 4K | 864K | 263.2M | $180.01 | $710.71 | $367.79 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **8,242** | **1.8M** | **2.4M** | **993.5M** | **$2,314.49** | **$10,168.90** | **$448.93** |

_1,072.5M total tokens processed. 92.6% cache hit rate._

_$10,617.84 total saved ($10,168.90 caching + $448.93 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 5,438 | 7K | 2.2M | 1,219.3M | $2,000.08 | $16,461.28 | $0.00 |
| claude-sonnet-4-6 | 4,042 | 4K | 862K | 263.0M | $91.85 | $710.17 | $367.45 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **9,482** | **11K** | **3.1M** | **1,482.4M** | **$2,091.99** | **$17,171.92** | **$367.45** |

_1,653.6M total tokens processed. 92.7% cache hit rate._

_$17,539.37 total saved ($17,171.92 caching + $367.45 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-30 20:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
