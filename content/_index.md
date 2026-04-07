---
title: Windows KMU Baseline Pack
description: Produktisierte Windows-11-Baseline für kleine Unternehmen ohne eigene IT-Abteilung.
---

# Windows KMU Baseline Pack

Ein technisch sauberes, modular aufgebautes Hardening- und Policy-Paket für **Windows 11 Pro** in **kleinen Umgebungen ohne Active Directory**. Deployment erfolgt lokal über **LGPO.exe**. :contentReference[oaicite:1]{index=1}

{{< callout type="important" >}}
**v1-Fokus:** Windows 11 Pro, 24H2, de-DE und en-US, kleine Workgroup-Umgebungen, lokales Deployment via LGPO.exe. :contentReference[oaicite:2]{index=2}
{{< /callout >}}

## Schnell starten

{{< cards cols="2" >}}
  {{< card link="/de/product" title="Produkt" subtitle="Varianten, Kernumfang und Scope von v1" icon="cube" >}}
  {{< card link="/de/pricing" title="Pricing" subtitle="Solo und Team im Überblick" icon="scale" >}}
  {{< card link="/de/docs/get-started" title="Get Started" subtitle="Empfohlener Einstieg für Pilot und erste Prüfung" icon="play" >}}
  {{< card link="/de/buy" title="Kaufen" subtitle="Produktvarianten und Kaufvorbereitung" icon="credit-card" >}}
  {{< card link="/de/docs" title="Dokumentation" subtitle="Technischer Einstieg, Support-Scope und Orientierung" icon="book-open" >}}
{{< /cards >}}

## Kernmodule

{{< cards cols="2" >}}
  {{< card link="/de/product" title="Defender" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/product" title="Firewall" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/product" title="UAC / LSA" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/product" title="Windows Update" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
{{< /cards >}}

## Geeignet für

- kleine Unternehmen ohne eigene IT-Abteilung
- Einzelgeräte und kleine Workgroup-Umgebungen
- Windows-11-Setups ohne Active Directory
- konservative, dokumentierte lokale Baseline-Härtung

## Nicht im Scope von v1

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch-Rollout :contentReference[oaicite:3]{index=3}

{{< callout type="warning" >}}
Vor produktivem Einsatz: **erst Pilotgerät, dann prüfen, dann gezielt ausrollen**. Backup, Snapshot und Recovery sollten vor dem Deployment eingeplant werden. :contentReference[oaicite:4]{index=4}
{{< /callout >}}

## Wichtige Seiten

- [Produkt](/de/product)
- [Get Started](/de/docs/get-started)
- [Kaufen](/de/buy)
- [Support-Matrix](/de/docs/support-matrix)
- [Pre-Deploy-Checkliste](/de/docs/pre-deploy-checklist)
- [FAQ](/de/docs/faq)
- [Legal](/de/legal)

## Technische Quelle

Die technische Source of Truth ist das Produkt-Repository:

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)