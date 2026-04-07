---
title: Pre-Deployment Checklist
description: Checkpoints before the first rollout of the Windows KMU Baseline Pack.
---

This checklist is intended for the **first pilot-device test** and for every later controlled rollout.

## Target system and scope

- the target system is **Windows 11 Pro**
- the preferred release is **25H2**; **24H2** remains acceptable
- the system is administered **locally**
- no AD, domain GPO, Intune, MDM or Autopilot management is active
- deployment scenario matches **single-device / workgroup / small environment**
- usage is within the documented **v1 scope**

## Safety and recovery

- current backup or snapshot exists
- recovery in case of failure is known
- for BitLocker: **recovery key** is secured
- local administrator rights are available
- testing starts on a **non-production / pilot device**

## System condition

- device is fully updated
- reboot after updates has been completed
- no major open system failures or admin issues are known
- basic availability of network, internet and services is verified beforehand

## Consider productive dependencies

- printers considered
- NAS / network drives considered
- RDP / remote support considered, if needed
- line-of-business applications and business software considered
- known legacy dependencies on SMB / NTLM or older devices taken into account

## Rollout discipline

- documentation of the test run is planned
- pilot-device results are reviewed before additional systems follow
- no broad rollout without a clean function test
- support and scope boundaries are understood internally

## Next

- [Get Started](get-started)
- [Support Matrix](support-matrix)
- [FAQ](faq)
