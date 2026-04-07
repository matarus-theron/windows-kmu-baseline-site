---
title: Windows KMU Baseline Pack
description: Productized Windows 11 baseline for small businesses without in-house IT.
---

# Windows KMU Baseline Pack

A technically clean, modular hardening and policy package for **Windows 11 Pro** in **small environments without Active Directory**.

{{< callout type="important" >}}
**v1 focus:** Windows 11 Pro, 24H2, de-DE and en-US, local deployment via LGPO.exe, small workgroup environments. :contentReference[oaicite:4]{index=4}
{{< /callout >}}

## Get started

{{< cards cols="2" >}}
  {{< card link="/en/product" title="Product" subtitle="Editions, core scope and boundaries of v1" icon="cube" >}}
  {{< card link="/en/buy" title="Buy" subtitle="Product editions and purchase preparation" icon="cube" >}}
  {{< card link="/en/docs" title="Documentation" subtitle="Technical entry point, scope and orientation" icon="book-open" >}}
  {{< card link="/en/docs/get-started" title="Get Started" subtitle="Recommended starting point for pilot and initial review" icon="play" >}}
  {{< card link="/en/docs/support-matrix" title="Support Matrix" subtitle="What is officially supported and what is not" icon="shield-check" >}}
  {{< card link="/en/docs/pre-deploy-checklist" title="Pre-Deployment Checklist" subtitle="Check the basics before the pilot device" icon="check-circle" >}}
  {{< card link="/en/docs/faq" title="FAQ" subtitle="Short answers to common questions" icon="question-mark-circle" >}}
{{< /cards >}}

## Core modules

{{< cards cols="2" >}}
  {{< card link="/en/docs/faq" title="Defender" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/docs/faq" title="Firewall" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/docs/faq" title="UAC / LSA" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
  {{< card link="/en/docs/faq" title="Windows Update" subtitle="Part of the v1 core baseline" tag="Core" tagColor="green" >}}
{{< /cards >}}

## Not in scope for v1

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 hardening
- Adobe / Acrobat hardening
- Zero-touch rollout

{{< callout type="warning" >}}
Before production use: **pilot device first, then review, then roll out selectively**. Backup, snapshot and recovery should be planned before deployment. :contentReference[oaicite:5]{index=5}
{{< /callout >}}

## Technical source

The technical source of truth is the product repository:

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)

## Legal

- [Legal](/en/legal)
- [License](/en/legal/license)
- [Privacy](/en/legal/privacy)