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
| User AI session hours | 0.6h | 5.6h | 21.4h | 21.4h |
| AI worker hours | 2.4h | 3.3h | 3.3h | 3.3h |
| AI concurrency hours | 5.1h | 16.0h | 42.5h | 42.5h |
| Interactive sessions | 20 | 32 | 38 | 38 |
| Worker sessions | 59 | 85 | 85 | 85 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,195 | 2K | 824K | 401.5M | $1,163.01 | $5,421.28 | $0.00 |
| claude-sonnet-4-6 | 943 | 1K | 199K | 68.7M | $43.09 | $185.60 | $94.50 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **3,533** | **1.8M** | **1.1M** | **500.0M** | **$1,223.45** | **$5,606.89** | **$175.64** |

_535.1M total tokens processed. 93.4% cache hit rate._

_$5,782.53 total saved ($5,606.89 caching + $175.64 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,493 | 4K | 1.5M | 873.8M | $1,423.57 | $11,797.39 | $0.00 |
| claude-sonnet-4-6 | 944 | 1K | 199K | 68.7M | $23.61 | $185.60 | $94.50 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **4,439** | **5K** | **1.7M** | **942.6M** | **$1,447.24** | **$11,983.46** | **$94.50** |

_1,073.0M total tokens processed. 92.6% cache hit rate._

_$12,077.96 total saved ($11,983.46 caching + $94.50 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-14 10:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
