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
| AI worker hours | 2.5h | 6.2h | 6.2h | 6.2h |
| AI concurrency hours | 7.2h | 22.6h | 44.2h | 44.2h |
| Interactive sessions | 24 | 58 | 64 | 64 |
| Worker sessions | 65 | 163 | 163 | 163 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,432 | 3K | 918K | 443.1M | $1,297.59 | $5,982.04 | $0.00 |
| claude-sonnet-4-6 | 1,817 | 2K | 370K | 117.8M | $73.98 | $318.19 | $163.68 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **4,644** | **1.8M** | **1.4M** | **590.7M** | **$1,388.92** | **$6,300.24** | **$244.83** |

_633.1M total tokens processed. 93.3% cache hit rate._

_$6,545.07 total saved ($6,300.24 caching + $244.83 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,731 | 4K | 1.5M | 915.4M | $1,492.86 | $12,358.15 | $0.00 |
| claude-sonnet-4-6 | 1,819 | 2K | 370K | 117.9M | $40.93 | $318.36 | $163.77 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,552** | **6K** | **1.9M** | **1,033.3M** | **$1,533.85** | **$12,676.98** | **$163.77** |

_1,171.1M total tokens processed. 92.6% cache hit rate._

_$12,840.75 total saved ($12,676.98 caching + $163.77 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-15 14:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
