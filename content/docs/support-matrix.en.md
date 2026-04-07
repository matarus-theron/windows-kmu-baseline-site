---
title: Support Matrix
description: Officially supported, optional and unsupported deployment scenarios for v1.
---

This matrix describes the **binding scope of v1**. Everything outside of it is either **best effort / optional** or **deliberately unsupported**.

## Officially supported

- **Operating system:** Windows 11
- **Edition:** Pro
- **Release:** 24H2
- **Language:** de-DE and en-US
- **Deployment:** local via LGPO.exe
- **Environment:** workgroup / single-device / small environments
- **Core areas of v1:**
  - Defender baseline
  - Firewall baseline
  - Audit baseline
  - UAC / LSA baseline
  - Windows Update baseline

## Best effort / optional

- Windows 11 Enterprise
- Windows 11 25H2 after testing and approval
- browser hardening as a separate add-on
- conservative SMB / network hardening after environment review

## Not supported / not recommended

- Windows 11 Home
- Windows Server 2022 / 2025
- Active Directory / domain GPO
- domain controllers
- RDS / terminal servers
- Intune-, MDM- or Autopilot-managed devices
- Microsoft 365 / Office hardening
- Adobe / Acrobat hardening
- production-critical special environments without separate testing
- centralized zero-touch rollout into productive fleets

## Edition framework

- **Solo:** up to 5 devices
- **Team:** up to 25 devices

## Important

This matrix does **not** replace a pilot device, backup, recovery or function testing. It defines the product scope; responsibility for proper pre-checks and controlled use remains with the buyer.

## Next

- [Get Started](get-started)
- [Pre-Deployment Checklist](pre-deploy-checklist)
- [Product](../product)
