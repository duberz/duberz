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
| User AI session hours | 0.6h | 5.6h | 21.5h | 21.5h |
| AI worker hours | 2.2h | 2.4h | 2.4h | 2.4h |
| AI concurrency hours | 4.9h | 15.0h | 41.7h | 41.7h |
| Interactive sessions | 20 | 24 | 31 | 31 |
| Worker sessions | 60 | 64 | 64 | 64 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,195 | 2K | 824K | 401.5M | $1,163.01 | $5,421.28 | $0.00 |
| claude-sonnet-4-6 | 659 | 742 | 144K | 52.6M | $33.53 | $142.10 | $71.83 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **3,249** | **1.8M** | **1.0M** | **483.9M** | **$1,213.89** | **$5,563.38** | **$152.97** |

_517.9M total tokens processed. 93.4% cache hit rate._

_$5,716.36 total saved ($5,563.38 caching + $152.97 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,493 | 4K | 1.5M | 873.8M | $1,423.57 | $11,797.39 | $0.00 |
| claude-sonnet-4-6 | 659 | 742 | 144K | 52.6M | $17.94 | $142.10 | $71.83 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **4,154** | **5K** | **1.6M** | **926.5M** | **$1,441.57** | **$11,939.96** | **$71.83** |

_1,055.8M total tokens processed. 92.6% cache hit rate._

_$12,011.79 total saved ($11,939.96 caching + $71.83 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-14 02:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
