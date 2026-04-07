---
title: Windows KMU Baseline Pack
description: Produktisierte Windows-11-Baseline für kleine Unternehmen ohne eigene IT-Abteilung.
---

# Windows KMU Baseline Pack

Produktisierte lokale Baseline-Härtung für **Windows 11 Pro** in **kleinen Umgebungen ohne Active Directory**.

{{< callout type="important" >}}
**v1-Fokus:** Windows 11 Pro, 24H2, de-DE und en-US, Deployment via LGPO.exe, kleine Workgroup-Umgebungen.
{{< /callout >}}

## Schnellstart

{{< cards cols="2" >}}
  {{< card link="/de/product" title="Produkt" subtitle="Scope, Zielgruppe und Kernumfang" icon="cube" >}}
  {{< card link="/de/pricing" title="Pricing" subtitle="Solo und Team im Überblick" icon="cube" >}}
  {{< card link="/de/docs/get-started" title="Get Started" subtitle="Empfohlener Einstieg für Pilot und erste Prüfung" icon="play" >}}
  {{< card link="/de/buy" title="Kaufen" subtitle="Kaufvorbereitung und geplanter Ablauf" icon="credit-card" >}}
{{< /cards >}}

## Kernumfang von v1

- Defender
- Firewall
- UAC / LSA
- Windows Update

## Geeignet für

- kleine Unternehmen ohne eigene IT-Abteilung
- Einzelgeräte und kleine Workgroup-Umgebungen
- Windows-11-Setups ohne Active Directory

## Nicht im Scope

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch-Rollout

{{< callout type="warning" >}}
Vor produktivem Einsatz: **erst Pilotgerät, dann prüfen, dann gezielt ausrollen**. Backup, Snapshot und Recovery sollten vor dem Deployment eingeplant werden.
{{< /callout >}}

## Weiterführend

- [Dokumentation](/de/docs)
- [Support-Matrix](/de/docs/support-matrix)
- [Pre-Deploy-Checkliste](/de/docs/pre-deploy-checklist)
- [FAQ](/de/docs/faq)
- [Lieferrahmen](/de/delivery)
- [Legal](/de/legal)

## Technische Quelle

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)