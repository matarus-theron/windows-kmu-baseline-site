---
title: Windows KMU Baseline Pack
description: Lokal ausrollbares Hardening- und Policy-Paket für Windows 11 Pro in kleinen Umgebungen ohne Active Directory.
---

Produktisiertes Hardening- und Policy-Paket für **Windows 11 Pro 24H2** in **kleinen Workgroup-, Einzelgeräte- und KMU-Umgebungen ohne Active Directory**. Deployment erfolgt **lokal via LGPO.exe**.

{{< callout type="important" >}}
**B2B-Produkt für kleine Firmen / KMU in CH, DE und AT.**  
v1 fokussiert auf **Windows 11 Pro 24H2**, **de-DE / en-US**, **lokale Ausrollung via LGPO.exe** und einen **bewusst engen, supportbaren Scope**.
{{< /callout >}}

{{< callout type="warning" >}}
**Nicht gedacht für** Active Directory / Domain GPO, Intune / MDM / Autopilot, Windows Server, Zero-Touch-Rollout, Managed Services oder individuelle Architektur- und Compliance-Beratung.
{{< /callout >}}

## Schnellzugriff

{{< cards cols="2" >}}
  {{< card link="product" title="Produkt" subtitle="Zielgruppe, Scope und Kernumfang von v1" icon="cube" >}}
  {{< card link="docs/get-started" title="Get Started" subtitle="Womit anfangen und was vor dem Pilotgerät zu prüfen ist" icon="play" >}}
  {{< card link="docs/faq" title="FAQ" subtitle="Kurze Antworten auf die wichtigsten Produktfragen" icon="question-mark-circle" >}}
  {{< card link="legal" title="Rechtliches" subtitle="Lizenz- und Datenschutz-Kurzfassung für die Website" icon="scale" >}}
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

- **Solo**: bis zu 5 Geräte
- **Team**: bis zu 25 Geräte

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
- [Kauf & Lieferung](buy)
- [Rechtliches](legal)
