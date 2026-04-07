---
title: Windows KMU Baseline Pack
description: Productized Windows 11 baseline for small businesses without in-house IT.
---

# Windows KMU Baseline Pack

A technically clean, modular hardening and policy package for **Windows 11 Pro** in **small environments without Active Directory**.

{{< callout type="important" >}}
**v1 focus:** Windows 11 Pro, 24H2, de-DE and en-US, small workgroup environments, local deployment via LGPO.exe. :contentReference[oaicite:5]{index=5}
{{< /callout >}}

## Quick start

{{< cards cols="2" >}}
  {{< card link="/en/product" title="Product" subtitle="Editions, core scope and boundaries of v1" icon="cube" >}}
  {{< card link="/en/docs/get-started" title="Get Started" subtitle="Recommended starting point for pilot and initial review" icon="play" >}}
  {{< card link="/en/buy" title="Buy" subtitle="Product editions and purchase preparation" icon="credit-card" >}}
  {{< card link="/en/docs" title="Documentation" subtitle="Technical entry point, support scope and orientation" icon="book-open" >}}
{{< /cards >}}

## Core modules

{{< cards cols="2" >}}
  {{< card link="/en/product" title="Defender" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/product" title="Firewall" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/product" title="UAC / LSA" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/product" title="Windows Update" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
{{< /cards >}}

## Suitable for

- small businesses without an internal IT department
- single-device and small workgroup environments
- Windows 11 setups without Active Directory
- conservative, documented local baseline hardening

## Not in scope for v1

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 hardening
- Adobe / Acrobat hardening
- zero-touch rollout :contentReference[oaicite:6]{index=6}

{{< callout type="warning" >}}
Before production use: **pilot device first, then review, then roll out selectively**. Backup, snapshot and recovery should be planned before deployment. :contentReference[oaicite:7]{index=7}
{{< /callout >}}

## Key pages

- [Product](/en/product)
- [Get Started](/en/docs/get-started)
- [Buy](/en/buy)
- [Support Matrix](/en/docs/support-matrix)
- [Pre-Deployment Checklist](/en/docs/pre-deploy-checklist)
- [FAQ](/en/docs/faq)
- [Legal](/en/legal)

## Technical source

The technical source of truth is the product repository:

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)