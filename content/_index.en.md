---
title: Windows KMU Baseline Pack
description: Locally deployable hardening and policy package for Windows 11 Pro in small environments without Active Directory.
---

Productized hardening and policy package for **Windows 11 Pro 24H2** in **small workgroup, single-device and SME environments without Active Directory**. Deployment is performed **locally via LGPO.exe**.

{{< callout type="important" >}}
**B2B product for small businesses in CH, DE and AT.**  
v1 focuses on **Windows 11 Pro 24H2**, **de-DE / en-US**, **local deployment via LGPO.exe**, and a **deliberately narrow, supportable scope**.
{{< /callout >}}

{{< callout type="warning" >}}
**Not intended for** Active Directory / domain GPO, Intune / MDM / Autopilot, Windows Server, zero-touch rollout, managed services, or individual architecture and compliance consulting.
{{< /callout >}}

## Quick access

{{< cards cols="2" >}}
  {{< card link="product" title="Product" subtitle="Target audience, scope and core coverage of v1" icon="cube" >}}
  {{< card link="docs/get-started" title="Get Started" subtitle="Where to begin and what to verify before the pilot device" icon="play" >}}
  {{< card link="docs/faq" title="FAQ" subtitle="Short answers to the most important product questions" icon="question-mark-circle" >}}
  {{< card link="legal" title="Legal" subtitle="Website summary of license and privacy topics" icon="scale" >}}
{{< /cards >}}

## Core coverage of v1

- Defender baseline
- Firewall baseline
- Audit baseline
- UAC / LSA baseline
- Windows Update baseline

## Suitable for

- small businesses without an internal IT department
- locally administered Windows 11 Pro systems
- single-device and small workgroup environments
- environments where a **traceable baseline** matters more than maximum complexity
- conservative rollouts with pilot device, backup and clear support boundaries

## Deliberately out of scope

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server 2022 / 2025
- domain controllers / RDS / terminal servers
- Microsoft 365 / Office hardening
- Adobe / Acrobat hardening
- production-critical special environments without separate testing
- centralized zero-touch rollout into productive fleets
- managed services or customer use without a separate agreement

## Edition framework

The permitted device count depends on the purchased edition:

- **Solo**: up to 5 devices
- **Team**: up to 25 devices

## Rollout principle

The product is designed for **careful local deployment**:

1. verify target system and scope
2. ensure backup / snapshot / recovery
3. start on a **pilot / non-production device**
4. then roll out in a controlled way to further devices

## Further reading

- [Documentation](docs)
- [Get Started](docs/get-started)
- [Pre-Deployment Checklist](docs/pre-deploy-checklist)
- [Support Matrix](docs/support-matrix)
- [FAQ](docs/faq)
- [Purchase & Delivery](buy)
- [Legal](legal)
