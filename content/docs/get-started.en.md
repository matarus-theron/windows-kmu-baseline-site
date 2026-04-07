---
title: Get Started
description: Getting started with the Windows KMU Baseline Pack.
---

# Get Started

This page is the recommended entry point for the **Windows KMU Baseline Pack**.

{{< callout type="important" >}}
Do **not** roll out broadly first. Start with a **pilot device**, review the results, then roll out selectively. :contentReference[oaicite:4]{index=4}
{{< /callout >}}

## Target audience

This product is intended for small businesses without an internal IT department that need a local, clearly documented Windows 11 baseline. Deployment is done locally via **LGPO.exe**. :contentReference[oaicite:5]{index=5}

## Check before you start

{{< cards cols="2" >}}
  {{< card link="/en/docs/support-matrix" title="Support Matrix" subtitle="Does the target system fit the intended scope?" icon="shield-check" >}}
  {{< card link="/en/docs/pre-deploy-checklist" title="Pre-Deployment Checklist" subtitle="Preparation before testing on the pilot device" icon="check-circle" >}}
  {{< card link="/en/docs/faq" title="FAQ" subtitle="Short answers to common questions" icon="question-mark-circle" >}}
  {{< card link="https://github.com/matarus-theron/windows-kmu-baseline-pack" title="Product Repository" subtitle="Technical source and current state" icon="github" >}}
{{< /cards >}}

## Recommended order

1. Check scope against the support matrix
2. Fully update the target device
3. Reboot the system
4. Ensure backup / snapshot / recovery
5. Select a pilot device
6. Document deployment and results

## Core focus of v1

- Defender
- Firewall
- UAC / LSA
- Windows Update :contentReference[oaicite:6]{index=6}

## No public rollout shortcut yet

This page is deliberately conservative. It does not replace product documentation, license documents or controlled testing on a pilot device.