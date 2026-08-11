<p align="center">
  <h1 align="center">Randomized Tests for Subtle Decision Sabotage</h1>
  <p align="center"><strong>Run small randomized checks for whether models can bias decisions without obvious red flags.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Randomized Tests for Subtle Decision Sabotage**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Run small randomized checks for whether models can bias decisions without obvious red flags.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
