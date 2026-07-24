# SLO Definitions — NestOps Infrastructure

| SLI | Target | Alert Threshold |
|-----|--------|-----------------|
| Availability | 99.9% uptime | Down > 1 minute |
| Memory | < 85% usage | Warning at 75% |
| Disk | < 80% usage | Warning at 70% |
| CPU | < 90% usage | Warning at 80% |

## Error Budget Policy
- Above 50% remaining → Normal operations
- 25–50% remaining → Increased testing
- Below 25% remaining → Freeze deployments
- Exhausted → Emergency reliability sprint
