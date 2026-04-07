---
title: Dokumentation
description: Technische und produktbezogene Dokumentation zum Windows KMU Baseline Pack.
---

# Dokumentation

Diese Dokumentation beschreibt Scope, Einsatzbereich, Voraussetzungen und Grenzen des **Windows KMU Baseline Pack**.

{{< callout type="important" >}}
Diese Website ist die öffentliche Produkt- und Dokumentationsschicht. Die technische Source of Truth bleibt das Produkt-Repository. :contentReference[oaicite:1]{index=1}
{{< /callout >}}

## Womit anfangen?

{{< cards cols="2" >}}
  {{< card link="/de/docs/support-matrix" title="Support-Matrix" subtitle="Unterstützte und nicht unterstützte Plattformen und Szenarien" icon="shield-check" >}}
  {{< card link="/de/docs/pre-deploy-checklist" title="Pre-Deploy-Checkliste" subtitle="Vor dem Pilotgerät die Basis sauber prüfen" icon="check-circle" >}}
  {{< card link="/de/docs/faq" title="FAQ" subtitle="Kurze Antworten auf die häufigsten Fragen" icon="question-mark-circle" >}}
  {{< card link="https://github.com/matarus-theron/windows-kmu-baseline-pack" title="Produkt-Repository" subtitle="Technische Quelle und aktueller Stand" icon="github" >}}
{{< /cards >}}

## Ziel von v1

- Windows 11 Pro
- 24H2
- de-DE und en-US
- lokales Deployment via LGPO.exe
- kleine Workgroup-Umgebungen
- Fokus auf Defender, Firewall, UAC / LSA und Windows Update :contentReference[oaicite:2]{index=2}

## Nicht im Scope von v1

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch / zentraler Flotten-Rollout :contentReference[oaicite:3]{index=3}

{{< callout type="warning" >}}
Vor produktivem Einsatz immer zuerst auf einem **Pilotgerät** testen und **Backup / Snapshot / Recovery** einplanen. :contentReference[oaicite:4]{index=4}
{{< /callout >}}