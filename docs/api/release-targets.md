---
title: API Release Targets
---
## API Release Targets
These are the API targets for supported toffeeOS Dev Version releases (LTS/non-LTS). We recommend developers target the three most recent releases of toffeeOS, not including the LTS releases.

``NC`` = No API changes in this release

### x86 LTS (32-bit) [X]
x86 support has been removed in API level ``200``, making ``166X`` (1.6.8 LTS) the final release available for this platform. Please upgrade to x86_64 (64-bit). 

### x86_64 (64-bit) [Y] and ARM [A]

| toffeeOS Dev Version Release | Current Channel | API Level (Target) |
|-----------------|-----------------|--------------------|
| 2.0 LTS | Alpha | ``200`` |
| 1.8 for ARM | Stable | ``180A`` |
| 1.8 | Stable | ``180Y`` |

## Architecture Codes

These have been deprecated and are no longer in use, as API Level ``200`` is built for both out of the box. This is here for historical purposes.

| Architecture | Displayed as? |
|-----------------|-----------------|
| ARM (including M1, M2, M3) | ``A`` |
| 32-bit (x86) | ``X`` |
| 64-bit (x86_64) | ``Y`` |
