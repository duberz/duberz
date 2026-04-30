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
| Screen time (Linux) | 7.5h | 7.5h | 55.5h | ~3,398h* |
| User AI session hours | 1.6h | 8.1h | 8.8h | 8.8h |
| AI worker hours | 0.0h | 3.4h | 3.4h | 3.4h |
| AI concurrency hours | 3.1h | 16.1h | 17.3h | 17.3h |
| Interactive sessions | 1 | 2 | 2 | 2 |
| Worker sessions | 0 | 101 | 101 | 101 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,622 | 4K | 1.4M | 678.0M | $2,050.84 | $9,153.07 | $0.00 |
| claude-sonnet-4-6 | 4,185 | 4K | 877K | 267.3M | $183.67 | $721.73 | $373.50 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **8,202** | **1.8M** | **2.4M** | **975.0M** | **$2,251.86** | **$9,874.80** | **$454.65** |

_1,053.0M total tokens processed. 92.6% cache hit rate._

_$10,329.45 total saved ($9,874.80 caching + $454.65 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 5,468 | 7K | 2.2M | 1,224.3M | $2,008.46 | $16,528.99 | $0.00 |
| claude-sonnet-4-6 | 4,102 | 4K | 876K | 267.1M | $93.28 | $721.19 | $373.17 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **9,572** | **11K** | **3.1M** | **1,491.5M** | **$2,101.80** | **$17,250.66** | **$373.17** |

_1,663.1M total tokens processed. 92.7% cache hit rate._

_$17,623.82 total saved ($17,250.66 caching + $373.17 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-30 23:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
