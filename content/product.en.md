---
title: Product
description: Target audience, scope and core coverage of the Windows KMU Baseline Pack v1.
---

The **Windows KMU Baseline Pack v1** is a **locally deployable hardening and policy package** for **Windows 11 Pro** in **small environments without Active Directory**. It is designed as a **digital B2B product** — not as a workshop, managed service or consulting engagement.

{{< callout type="important" >}}
**Core statement:** v1 is deliberately **narrow**, **modular**, and **supportable**.  
**The primary target release is Windows 11 Pro 25H2. 24H2 remains supported.** Deployment is performed **locally via LGPO.exe**.
{{< /callout >}}

## Who this product is for

- small businesses without an internal IT department
- locally administered Windows 11 Pro systems
- single-device and small workgroup environments
- environments where a clean, traceable baseline matters more than maximum complexity
- buyers looking for a **clearly scoped B2B product**, not a workshop or consulting scope

## Core areas of v1

- Defender baseline
- Firewall baseline
- Audit baseline
- UAC / LSA baseline
- Windows Update baseline

## Officially supported framework

- **Operating system:** Windows 11
- **Edition:** Pro
- **Primary release target:** 25H2
- **Also supported:** 24H2
- **Language:** de-DE and en-US
- **Deployment:** local via LGPO.exe
- **Environment:** workgroup / single-device / small environments

## Best effort / optional

- Windows 11 Enterprise
- Browser hardening as a separate add-on
- conservative SMB / network hardening after environment review

## Deliberately not included

- Active Directory / domain GPO
- domain controllers
- RDS / terminal servers
- Intune / MDM / Autopilot
- Windows Server 2022 / 2025
- Microsoft 365 / Office hardening
- Adobe / Acrobat hardening
- centralized zero-touch rollout
- managed-service or MSP usage without a separate agreement
- individual architecture, risk or compliance consulting

## Editions and device scope

The purchased edition defines the allowed device count:

- **Solo**: CHF 149, up to 3 devices
- **Team**: CHF 399, up to 10 devices
- **Business**: CHF 599, up to 25 devices

## Support and operating boundaries

The product is built around a **conservative, documented scope**. This means:

- test on a **pilot / non-production device** first
- ensure backup / snapshot / recovery before deployment
- account for printers, NAS, network drives, RDP and line-of-business applications before broader rollout
- no implied promise of compatibility with third-party software, legacy printers, older NAS devices or old SMB / NTLM dependencies
- support depends on the **purchased edition**, **product description** and **documented scope**

## Next

- [Get Started](../docs/get-started)
- [Support Matrix](../docs/support-matrix)
- [Pre-Deployment Checklist](../docs/pre-deploy-checklist)
- [FAQ](../docs/faq)
- [Packages & Delivery](../buy)
- [Legal](../legal)
