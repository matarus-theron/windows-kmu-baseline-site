---
title: Windows KMU Baseline Pack
description: Productized Windows 11 baseline for small businesses without in-house IT.
---

# Windows KMU Baseline Pack

Productized local baseline hardening for **Windows 11 Pro** in **small environments without Active Directory**.

{{< callout type="important" >}}
**v1 focus:** Windows 11 Pro, 24H2, de-DE and en-US, deployment via LGPO.exe, small workgroup environments.
{{< /callout >}}

## Quick start

{{< cards cols="2" >}}
  {{< card link="/en/product" title="Product" subtitle="Scope, target audience and core coverage" icon="cube" >}}
  {{< card link="/en/pricing" title="Pricing" subtitle="Solo and Team at a glance" icon="cube" >}}
  {{< card link="/en/docs/get-started" title="Get Started" subtitle="Recommended starting point for pilot and initial review" icon="play" >}}
  {{< card link="/en/buy" title="Buy" subtitle="Purchase preparation and planned process" icon="credit-card" >}}
{{< /cards >}}

## Core coverage of v1

- Defender
- Firewall
- UAC / LSA
- Windows Update

## Suitable for

- small businesses without an internal IT department
- single-device and small workgroup environments
- Windows 11 setups without Active Directory

## Not in scope

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 hardening
- Adobe / Acrobat hardening
- zero-touch rollout

{{< callout type="warning" >}}
Before production use: **pilot device first, then review, then roll out selectively**. Backup, snapshot and recovery should be planned before deployment.
{{< /callout >}}

## Further reading

- [Documentation](/en/docs)
- [Support Matrix](/en/docs/support-matrix)
- [Pre-Deployment Checklist](/en/docs/pre-deploy-checklist)
- [FAQ](/en/docs/faq)
- [Delivery](/en/delivery)
- [Legal](/en/legal)

## Technical source

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)