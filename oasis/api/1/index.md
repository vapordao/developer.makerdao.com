---
layout: oasis/api
title: Oasis Markets API
description: Public rest endpoints for markets data
apiVersion: 1
---

### REST API v1

Public REST endpoints for Oasis markets data.

Notes:

- No rate limiting
- No API key required
- All times are UTC timestamps expressed as seconds (eg 1477409622)
- All public endpoints use GET requests

Freshness:

- Responses may be cached and shoult not be treated as live. Timestamps
  indicate the exact time at which the data should be considered valid.
