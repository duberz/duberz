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
| User AI session hours | 3.4h | 7.0h | 13.8h | 13.8h |
| AI worker hours | 3.4h | 9.3h | 9.3h | 9.3h |
| AI concurrency hours | 9.1h | 23.6h | 39.0h | 39.0h |
| Interactive sessions | 6 | 61 | 67 | 67 |
| Worker sessions | 42 | 200 | 200 | 200 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,643 | 3K | 1.0M | 495.4M | $1,464.81 | $6,688.55 | $0.00 |
| claude-sonnet-4-6 | 2,512 | 2K | 512K | 161.0M | $98.53 | $434.78 | $224.04 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,550** | **1.8M** | **1.6M** | **686.2M** | **$1,580.69** | **$7,123.33** | **$305.19** |

_735.8M total tokens processed. 93.3% cache hit rate._

_$7,428.52 total saved ($7,123.33 caching + $305.19 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,942 | 5K | 1.6M | 967.7M | $1,578.42 | $13,064.65 | $0.00 |
| claude-sonnet-4-6 | 2,497 | 2K | 511K | 160.8M | $55.91 | $434.24 | $223.74 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **6,441** | **7K** | **2.2M** | **1,128.6M** | **$1,634.39** | **$13,499.37** | **$223.74** |

_1,272.6M total tokens processed. 92.7% cache hit rate._

_$13,723.11 total saved ($13,499.37 caching + $223.74 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-16 12:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
