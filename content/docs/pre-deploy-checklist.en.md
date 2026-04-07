---
title: Pre-Deployment Checklist
description: Checks to perform before deploying the Windows KMU Baseline Pack.
---

# Pre-Deployment Checklist

Before deployment, at least the following should be verified:

## Environment

- Target device is Windows 11 Pro
- Target version is 24H2
- Device is not managed via Active Directory
- Device is not managed via Intune / MDM / Autopilot
- Target scenario matches workgroup / single-device / small environment

## Preparation

- Pilot device first
- Backup / snapshot / recovery option available
- Local administrator rights available
- Device is fully updated
- Reboot after updates completed

## Product fit

- Goal is local baseline hardening via LGPO.exe
- Focus is on Defender, Firewall, UAC / LSA and Windows Update
- No dependency on domain GPO
- No expectation of Office / Adobe / server hardening

## Recommendation

Test on a pilot device first and document the results before wider rollout.