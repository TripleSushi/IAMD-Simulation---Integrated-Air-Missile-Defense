## IAMD Simulation v2.3.1

First formal release establishing a rollback baseline.

### What's included:
- Full IAMD simulation with interceptor engagement, Kalman filtering, and PN guidance
- v2.0 visual overhaul: particle explosions, radar sweep, gradient trails
- v2.1 bug fixes and survival extension
- v2.3 layered defense system (UPPER/MIDDLE/LOWER tiers)
- v2.3.1 automated bug fixes: 5 HIGH-severity PN guidance patches
- CI/CD pipeline: deploy.yml (GitHub Pages), test.yml, lint.yml
- Automated bug-hunter pipeline integration

### CI/CD Status at release:
- 72 consecutive green runs
- 97.6% overall success rate (83/85 runs)
- 100% deploy success rate (30/30)
