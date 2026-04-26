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
| Screen time (Linux) | 24h | 24h | 48h | ~3,398h* |
| User AI session hours | 0.0h | 3.3h | 16.7h | 16.7h |
| AI worker hours | 0.7h | 0.7h | 10.8h | 10.8h |
| AI concurrency hours | 0.7h | 5.5h | 39.3h | 39.3h |
| Interactive sessions | 0 | 2 | 62 | 62 |
| Worker sessions | 21 | 21 | 227 | 227 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,486 | 4K | 1.3M | 636.3M | $1,921.49 | $8,590.79 | $0.00 |
| claude-sonnet-4-6 | 2,896 | 3K | 595K | 184.9M | $116.69 | $499.27 | $257.67 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **6,777** | **1.8M** | **2.0M** | **851.0M** | **$2,055.53** | **$9,090.06** | **$338.81** |

_915.2M total tokens processed. 93% cache hit rate._

_$9,428.87 total saved ($9,090.06 caching + $338.81 model routing vs all-Opus)._

_Model savings are modest because ~93% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,787 | 6K | 2.0M | 1,108.6M | $1,818.17 | $14,966.89 | $0.00 |
| claude-sonnet-4-6 | 2,858 | 3K | 592K | 184.3M | $64.18 | $497.65 | $256.79 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **7,647** | **9K** | **2.6M** | **1,293.0M** | **$1,882.41** | **$15,465.02** | **$256.79** |

_1,450.5M total tokens processed. 92.6% cache hit rate._

_$15,721.80 total saved ($15,465.02 caching + $256.79 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-26 19:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
