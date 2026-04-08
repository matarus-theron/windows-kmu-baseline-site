---
title: HardenLab Local Pack for Windows 11
---

**Baseline hardening for Windows 11 without Active Directory**

HardenLab Local Pack is the current v1 product for small local Windows environments without AD.

## Officially supported

- Windows 11 Pro and Enterprise
- 25H2 as primary target, 24H2 still supported
- de-DE and en-US
- standalone, workgroup and other small local environments

## Core baseline v1

- Defender
- Firewall
- UAC / LSA
- Windows Update

## Optional / later

- conservative SMB / network hardening
- Audit as a separate module / add-on
- browser hardening as a separate add-on
- later: HardenLab Domain Pack for AD environments

## Out of scope

- domain GPO / Active Directory
- Intune / MDM / Autopilot
- Windows Home
- Windows Server
- Office / Adobe hardening
- zero-touch fleet rollout
