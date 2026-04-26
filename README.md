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
| AI worker hours | 0.9h | 0.9h | 11.1h | 11.1h |
| AI concurrency hours | 0.9h | 5.8h | 39.5h | 39.5h |
| Interactive sessions | 0 | 2 | 62 | 62 |
| Worker sessions | 29 | 29 | 235 | 235 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,486 | 4K | 1.3M | 636.3M | $1,921.49 | $8,590.79 | $0.00 |
| claude-sonnet-4-6 | 2,986 | 3K | 617K | 190.9M | $120.18 | $515.49 | $266.18 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **6,867** | **1.8M** | **2.1M** | **857.0M** | **$2,059.02** | **$9,106.27** | **$347.33** |

_921.6M total tokens processed. 93% cache hit rate._

_$9,453.60 total saved ($9,106.27 caching + $347.33 model routing vs all-Opus)._

_Model savings are modest because ~93% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,787 | 6K | 2.0M | 1,108.6M | $1,818.17 | $14,966.89 | $0.00 |
| claude-sonnet-4-6 | 2,954 | 3K | 616K | 190.7M | $66.45 | $514.94 | $265.87 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **7,743** | **9K** | **2.6M** | **1,299.4M** | **$1,884.68** | **$15,482.31** | **$265.87** |

_1,457.3M total tokens processed. 92.7% cache hit rate._

_$15,748.18 total saved ($15,482.31 caching + $265.87 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-26 21:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
