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
| User AI session hours | 3.1h | 7.3h | 12.8h | 12.8h |
| AI worker hours | 2.7h | 7.1h | 7.1h | 7.1h |
| AI concurrency hours | 7.7h | 22.2h | 34.7h | 34.7h |
| Interactive sessions | 22 | 61 | 67 | 67 |
| Worker sessions | 61 | 179 | 179 | 179 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 2,565 | 3K | 980K | 474.8M | $1,392.61 | $6,410.29 | $0.00 |
| claude-sonnet-4-6 | 2,035 | 2K | 416K | 130.5M | $81.60 | $352.58 | $181.69 |
| big-pickle | 395 | 1.8M | 112K | 29.7M | $17.35 | $0.00 | $81.15 |
| **Total** | **4,995** | **1.8M** | **1.5M** | **635.1M** | **$1,491.56** | **$6,762.87** | **$262.84** |

_680.8M total tokens processed. 93.3% cache hit rate._

_$7,025.71 total saved ($6,762.87 caching + $262.84 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,865 | 4K | 1.6M | 947.1M | $1,545.17 | $12,786.39 | $0.00 |
| claude-sonnet-4-6 | 2,036 | 2K | 416K | 130.6M | $45.43 | $352.74 | $181.78 |
| claude-opus-4-5 | 2 | 2 | 182 | 35K | $0.06 | $0.47 | $0.00 |
| **Total** | **5,903** | **7K** | **2.0M** | **1,077.8M** | **$1,590.66** | **$13,139.61** | **$181.78** |

_1,218.6M total tokens processed. 92.6% cache hit rate._

_$13,321.39 total saved ($13,139.61 caching + $181.78 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[bracket-builder](https://github.com/duberz/bracket-builder)** -- Embeddable tournament bracket builder for NCAA, NFL, NBA, NHL. FanDuel Research branded, Vercel-deployed.
- **[derekiwasiuk](https://github.com/duberz/derekiwasiuk)** -- personal website
## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/duberz)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-15 20:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
