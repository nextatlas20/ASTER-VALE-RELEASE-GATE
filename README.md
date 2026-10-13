# Aster Vale release operations

This repository publishes controlled release gates.

<!-- RELEASE-GATE:START -->
## March 2070 release gate
Components: 5 | Ready: 1 | Blocked: 4

| Component | Owner | Tests | Security | Blocker roots |
| --- | --- | --- | --- | --- |
| Gateway | Platform | pass | fail | CMP-API |
| Identity | Security | pass | pass | CMP-API |
| Runbook | Operations | pass | missing | CMP-OPS |
| Portal | Experience | pass | pending | CMP-API, CMP-WEB |

<!-- RELEASE-GATE:END -->

The marker comments are managed by automation.
