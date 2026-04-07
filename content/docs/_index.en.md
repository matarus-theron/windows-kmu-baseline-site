---
title: Documentation
description: Technical and product documentation for Windows KMU Baseline Pack.
---

# Documentation

This documentation covers scope, target scenarios, prerequisites and boundaries of the **Windows KMU Baseline Pack**.

{{< callout type="important" >}}
This website is the public-facing product and documentation layer. The technical source of truth remains the product repository. :contentReference[oaicite:5]{index=5}
{{< /callout >}}

## Where to start

{{< cards cols="2" >}}
  {{< card link="/en/docs/support-matrix" title="Support Matrix" subtitle="Supported and unsupported platforms and scenarios" icon="shield-check" >}}
  {{< card link="/en/docs/get-started" title="Get Started" subtitle="Recommended entry point for testing and pilot rollout" icon="play" >}}
  {{< card link="/en/docs/pre-deploy-checklist" title="Pre-Deployment Checklist" subtitle="Check the basics before the pilot device" icon="check-circle" >}}
  {{< card link="/en/docs/faq" title="FAQ" subtitle="Short answers to common questions" icon="question-mark-circle" >}}
  {{< card link="https://github.com/matarus-theron/windows-kmu-baseline-pack" title="Product Repository" subtitle="Technical source and current state" icon="github" >}}
{{< /cards >}}

## Focus of v1

- Windows 11 Pro
- 24H2
- de-DE and en-US
- local deployment via LGPO.exe
- small workgroup environments
- focus on Defender, Firewall, UAC / LSA and Windows Update :contentReference[oaicite:6]{index=6}

## Not in scope for v1

- Active Directory / domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 hardening
- Adobe / Acrobat hardening
- zero-touch / centrally managed rollout :contentReference[oaicite:7]{index=7}

{{< callout type="warning" >}}
Before production use, always test on a **pilot device** first and plan for **backup / snapshot / recovery**. :contentReference[oaicite:8]{index=8}
{{< /callout >}}