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
| AI worker hours | 2.3h | 2.7h | 2.7h | 2.7h |
| AI concurrency hours | 5.0h | 15.3h | 41.8h | 41.8h |
| Interactive sessions | 20 | 27 | 33 | 33 |
| Worker sessions | 60 | 70 | 70 | 70 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,195 | 2K | 824K | 401.5M | $1,163.01 | $5,421.28 | $0.00 |
| claude-sonnet-4-6 | 764 | 856 | 165K | 58.6M | $37.08 | $158.35 | $80.30 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **3,354** | **1.8M** | **1.1M** | **489.9M** | **$1,217.44** | **$5,579.63** | **$161.45** |

_524.3M total tokens processed. 93.4% cache hit rate._

_$5,741.08 total saved ($5,579.63 caching + $161.45 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,493 | 4K | 1.5M | 873.8M | $1,423.57 | $11,797.39 | $0.00 |
| claude-sonnet-4-6 | 764 | 856 | 165K | 58.6M | $20.06 | $158.35 | $80.30 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **4,259** | **5K** | **1.6M** | **932.5M** | **$1,443.69** | **$11,956.21** | **$80.30** |

_1,062.2M total tokens processed. 92.6% cache hit rate._

_$12,036.51 total saved ($11,956.21 caching + $80.30 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-14 05:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
