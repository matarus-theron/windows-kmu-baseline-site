---
title: Get Started
---

# Get Started

## Before every rollout

- create a backup or snapshot
- define a pilot device
- know your recovery path
- test printers, NAS, network shares, RDP and line-of-business apps
- make sure the device is not managed through Intune / MDM

## Recommended core baseline

```powershell
.\0010-RC-Run-RecommendedSetup.ps1 -Mode Sections -Section Defender,Firewall,UAC_Lsa,WindowsUpdate -SkipPolicyDefinitions
```

## Note

This product hardens systems and can affect functionality. Always test on a pilot device first.
