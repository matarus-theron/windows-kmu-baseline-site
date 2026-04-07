---
title: Windows KMU Baseline Pack
description: Lokal ausrollbares Hardening- und Policy-Paket für Windows 11 Pro in kleinen Umgebungen ohne Active Directory.
---

Produktisiertes Hardening- und Policy-Paket für **Windows 11 Pro** in **kleinen Workgroup-, Einzelgeräte- und KMU-Umgebungen ohne Active Directory**. Deployment erfolgt **lokal via LGPO.exe**.

{{< callout type="important" >}}
**B2B-Produkt für kleine Firmen / KMU in CH, DE und AT.**  
v1 fokussiert auf **Windows 11 Pro 25H2** als primären Zielstand. **24H2 bleibt weiterhin unterstützt**. Deployment erfolgt **lokal via LGPO.exe** und innerhalb eines **bewusst engen, supportbaren Scope**.
{{< /callout >}}

{{< callout type="warning" >}}
**Nicht gedacht für** Active Directory / Domain GPO, Intune / MDM / Autopilot, Windows Server, Zero-Touch-Rollout, Managed Services oder individuelle Architektur- und Compliance-Beratung.
{{< /callout >}}

## Schnellzugriff

{{< cards cols="2" >}}
  {{< card link="product" title="Produkt" subtitle="Zielgruppe, Scope und Kernumfang von v1" icon="cube" >}}
  {{< card link="docs/get-started" title="Get Started" subtitle="Womit anfangen und was vor dem Pilotgerät zu prüfen ist" icon="play" >}}
  {{< card link="docs/faq" title="FAQ" subtitle="Kurze Antworten auf die wichtigsten Produktfragen" icon="question-mark-circle" >}}
  {{< card link="buy" title="Pakete & Lieferung" subtitle="Varianten, Geräteumfang und Kaufrahmen" icon="credit-card" >}}
{{< /cards >}}

## Kernumfang von v1

- Defender Basis
- Firewall Basis
- Audit Basis
- UAC / LSA Basis
- Windows Update Basis

## Geeignet für

- kleine Firmen / KMU ohne eigene IT-Abteilung
- lokal administrierte Windows-11-Pro-Systeme
- Einzelgeräte und kleine Workgroup-Umgebungen
- Umgebungen, in denen eine **nachvollziehbare Baseline** wichtiger ist als maximale Komplexität
- konservative Rollouts mit Pilotgerät, Backup und klaren Supportgrenzen

## Bewusst nicht im Scope

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server 2022 / 2025
- Domain Controller / RDS / Terminalserver
- Microsoft 365 / Office Hardening
- Adobe / Acrobat Hardening
- produktionskritische Spezialumgebungen ohne separaten Test
- zentraler Zero-Touch-Rollout in produktive Flotten
- Managed Services oder Kundeneinsatz ohne separate Vereinbarung

## Variantenrahmen

Der zulässige Geräteumfang richtet sich nach der gekauften Variante:

- **Solo**: CHF 149, bis zu 3 Geräte
- **Team**: CHF 399, bis zu 10 Geräte
- **Business**: CHF 599, bis zu 25 Geräte

## Rollout-Grundsatz

Das Produkt ist auf **vorsichtige lokale Ausrollung** ausgelegt:

1. Zielsystem und Scope prüfen
2. Backup / Snapshot / Recovery sicherstellen
3. zuerst auf **Pilotgerät / Nicht-Produktivsystem**
4. danach kontrolliert auf weitere Geräte ausrollen

## Weiterführend

- [Dokumentation](docs)
- [Get Started](docs/get-started)
- [Pre-Deploy-Checkliste](docs/pre-deploy-checklist)
- [Support-Matrix](docs/support-matrix)
- [FAQ](docs/faq)
- [Pakete & Lieferung](buy)
- [Rechtliches](legal)
