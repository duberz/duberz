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
| User AI session hours | 2.0h | 7.4h | 20.1h | 20.1h |
| AI worker hours | 2.5h | 4.9h | 4.9h | 4.9h |
| AI concurrency hours | 7.2h | 21.3h | 42.9h | 42.9h |
| Interactive sessions | 24 | 46 | 52 | 52 |
| Worker sessions | 69 | 133 | 133 | 133 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,432 | 3K | 918K | 443.1M | $1,297.59 | $5,982.04 | $0.00 |
| claude-sonnet-4-6 | 1,441 | 1K | 296K | 96.1M | $60.25 | $259.58 | $133.20 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **4,268** | **1.8M** | **1.3M** | **568.9M** | **$1,375.19** | **$6,241.63** | **$214.35** |

_609.7M total tokens processed. 93.3% cache hit rate._

_$6,455.97 total saved ($6,241.63 caching + $214.35 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,731 | 4K | 1.5M | 915.4M | $1,492.86 | $12,358.15 | $0.00 |
| claude-sonnet-4-6 | 1,442 | 1K | 296K | 96.1M | $33.29 | $259.58 | $133.20 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,175** | **6K** | **1.8M** | **1,011.5M** | **$1,526.21** | **$12,618.21** | **$133.20** |

_1,147.6M total tokens processed. 92.6% cache hit rate._

_$12,751.41 total saved ($12,618.21 caching + $133.20 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-15 01:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
