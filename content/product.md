---
title: Produkt
description: Produktübersicht und Varianten des Windows KMU Baseline Pack.
---

# Produkt

Das **Windows KMU Baseline Pack** ist ein produktisiertes Hardening- und Policy-Paket für **kleine Windows-11-Umgebungen ohne Active Directory**. Deployment erfolgt lokal über **LGPO.exe**. :contentReference[oaicite:1]{index=1}

{{< callout type="important" >}}
v1 ist bewusst **eng begrenzt**: Windows 11 Pro, 24H2, de-DE und en-US, kleine Workgroup-Umgebungen, lokale Anwendung. :contentReference[oaicite:2]{index=2}
{{< /callout >}}

## Varianten

{{< cards cols="2" >}}
  {{< card title="Solo" subtitle="Für kleine Setups bis 5 Geräte" tag="v1" tagColor="green" >}}
  {{< card title="Team" subtitle="Für kleine Umgebungen bis 25 Geräte" tag="v1" tagColor="green" >}}
{{< /cards >}}

## Kernumfang von v1

- Defender
- Firewall
- UAC / LSA
- Windows Update :contentReference[oaicite:3]{index=3}

## Geeignet für

- kleine Unternehmen ohne eigene IT-Abteilung
- Einzelgeräte und kleine Workgroup-Umgebungen
- Umgebungen ohne Active Directory
- konservative, dokumentierte lokale Baseline-Härtung

## Nicht enthalten

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch-Rollout
- WDAC als Kernbestandteil
- Exploit Protection als Kernbestandteil :contentReference[oaicite:4]{index=4}

## Vor dem Einsatz

- Zielsystem gegen die Support-Matrix prüfen
- Pre-Deploy-Checkliste durchgehen
- Pilotgerät zuerst
- Backup / Snapshot / Recovery sicherstellen :contentReference[oaicite:5]{index=5}

## Weiter

- [Get Started](/de/docs/get-started)
- [Support-Matrix](/de/docs/support-matrix)
- [Pre-Deploy-Checkliste](/de/docs/pre-deploy-checklist)
- [FAQ](/de/docs/faq)