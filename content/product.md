---
title: Produkt
description: Scope, Zielgruppe und Kernumfang des Windows KMU Baseline Pack.
---

# Produkt

Das **Windows KMU Baseline Pack** ist ein produktisiertes Hardening- und Policy-Paket für **kleine Windows-11-Umgebungen ohne Active Directory**. Deployment erfolgt lokal über **LGPO.exe**. :contentReference[oaicite:1]{index=1}

{{< callout type="important" >}}
v1 ist bewusst **eng begrenzt**: Windows 11 Pro, 24H2, de-DE und en-US, kleine Workgroup-Umgebungen, lokale Anwendung. :contentReference[oaicite:2]{index=2}
{{< /callout >}}

## Für wen das Produkt gedacht ist

- kleine Unternehmen ohne eigene IT-Abteilung
- Einzelgeräte und kleine Workgroup-Umgebungen
- Windows-11-Setups ohne Active Directory
- konservative, dokumentierte lokale Baseline-Härtung

## Kernumfang von v1

- Defender
- Firewall
- UAC / LSA
- Windows Update :contentReference[oaicite:3]{index=3}

## Unterstützter Rahmen

- Windows 11 Pro
- Version 24H2
- de-DE
- en-US
- lokales Deployment via LGPO.exe :contentReference[oaicite:4]{index=4}

## Nicht im Scope von v1

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch-Rollout
- WDAC als Kernbestandteil
- Exploit Protection als Kernbestandteil :contentReference[oaicite:5]{index=5}

## Arbeitsweise

Das Produkt ist bewusst **modular**, **lokal anwendbar** und auf einen **klar begrenzten Support-Scope** ausgerichtet. Ziel ist ein verkaufbares Paket, nicht ein beratungsabhängiges Workshop-Modell. :contentReference[oaicite:6]{index=6}

## Weiter

- [Get Started](/de/docs/get-started)
- [Support-Matrix](/de/docs/support-matrix)
- [Pre-Deploy-Checkliste](/de/docs/pre-deploy-checklist)
- [FAQ](/de/docs/faq)
- [Kaufen](/de/buy)