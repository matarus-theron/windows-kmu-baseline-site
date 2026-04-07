---
title: Product
description: Product overview and editions of the Windows KMU Baseline Pack.
---

# Product

The **Windows KMU Baseline Pack** is a productized hardening and policy package for **small Windows 11 environments without Active Directory**. Deployment is performed locally via **LGPO.exe**. :contentReference[oaicite:6]{index=6}

{{< callout type="important" >}}
v1 is deliberately **narrowly scoped**: Windows 11 Pro, 24H2, de-DE and en-US, small workgroup environments, local deployment. :contentReference[oaicite:7]{index=7}
{{< /callout >}}

## Editions

{{< cards cols="2" >}}
  {{< card title="Solo" subtitle="For small setups up to 5 devices" tag="v1" tagColor="green" >}}
  {{< card title="Team" subtitle="For small environments up to 25 devices" tag="v1" tagColor="green" >}}
{{< /cards >}}

## Core scope of v1

- Defender
- Firewall
- UAC / LSA
- Windows Update :contentReference[oaicite:8]{index=8}

## Suitable for

- small businesses without an internal IT department
- single-device and small workgroup environments
- environments without Active Directory
- conservative, documented local baseline hardening

## Not included

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 hardening
- Adobe / Acrobat hardening
- zero-touch rollout
- WDAC as a core component
- Exploit Protection as a core component :contentReference[oaicite:9]{index=9}

## Before use

- check the target system against the support matrix
- review the pre-deployment checklist
- start with a pilot device
- ensure backup / snapshot / recovery :contentReference[oaicite:10]{index=10}

## Next

- [Get Started](/en/docs/get-started)
- [Support Matrix](/en/docs/support-matrix)
- [Pre-Deployment Checklist](/en/docs/pre-deploy-checklist)
- [FAQ](/en/docs/faq)