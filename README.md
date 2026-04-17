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
| Screen time (Linux) | 14.4h | 38.4h | 38.4h | ~3,048h* |
| User AI session hours | 3.5h | 9.5h | 17.3h | 17.3h |
| AI worker hours | 1.0h | 10.1h | 10.1h | 10.1h |
| AI concurrency hours | 5.5h | 27.8h | 44.3h | 44.3h |
| Interactive sessions | 2 | 61 | 68 | 68 |
| Worker sessions | 8 | 206 | 206 | 206 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,828 | 3K | 1.1M | 519.4M | $1,563.59 | $7,012.88 | $0.00 |
| claude-sonnet-4-6 | 2,651 | 2K | 542K | 169.7M | $103.58 | $458.21 | $236.22 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **5,874** | **1.8M** | **1.7M** | **718.9M** | **$1,684.52** | **$7,471.09** | **$317.37** |

_772.1M total tokens processed. 93.1% cache hit rate._

_$7,788.46 total saved ($7,471.09 caching + $317.37 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,129 | 5K | 1.7M | 991.7M | $1,621.13 | $13,388.98 | $0.00 |
| claude-sonnet-4-6 | 2,633 | 2K | 541K | 169.5M | $58.96 | $457.67 | $235.92 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **6,764** | **8K** | **2.3M** | **1,161.3M** | **$1,680.15** | **$13,847.12** | **$235.92** |

_1,308.7M total tokens processed. 92.6% cache hit rate._

_$14,083.04 total saved ($13,847.12 caching + $235.92 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-17 09:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
