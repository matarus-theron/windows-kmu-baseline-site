---
title: Produkt
description: Zielgruppe, Scope und Kernumfang des Windows KMU Baseline Pack v1.
---

Das **Windows KMU Baseline Pack v1** ist ein **lokal ausrollbares Hardening- und Policy-Paket** für **Windows 11 Pro** in **kleinen Umgebungen ohne Active Directory**. Es ist als **digitales B2B-Produkt** gedacht – nicht als Workshop, Managed Service oder Beratungsprojekt.

{{< callout type="important" >}}
**Kernaussage:** v1 ist bewusst **eng begrenzt**, **modular** und **supportbar**.  
**Primärer Zielstand ist Windows 11 Pro 25H2. 24H2 bleibt weiterhin unterstützt.** Deployment erfolgt **lokal via LGPO.exe**.
{{< /callout >}}

## Für wen das Produkt gedacht ist

- kleine Firmen / KMU ohne eigene IT-Abteilung
- lokal administrierte Windows-11-Pro-Systeme
- Einzelgeräte und kleine Arbeitsgruppen
- Umgebungen, in denen eine saubere, nachvollziehbare Baseline wichtiger ist als maximale Komplexität
- Käufer, die ein **klar abgegrenztes B2B-Produkt** suchen und keinen Beratungs- oder Workshop-Scope

## Kernbereiche von v1

- Defender Basis
- Firewall Basis
- Audit Basis
- UAC / LSA Basis
- Windows Update Basis

## Offiziell unterstützter Rahmen

- **Betriebssystem:** Windows 11
- **Edition:** Pro
- **Primärer Release-Stand:** 25H2
- **Zusätzlich unterstützt:** 24H2
- **Sprache:** de-DE und en-US
- **Deployment:** lokal via LGPO.exe
- **Umgebung:** Workgroup / Einzelgeräte / kleine Umgebungen

## Best Effort / optional

- Windows 11 Enterprise
- Browser-Hardening als separates Add-on
- konservative SMB-/Netzwerk-Härtung nach Umgebungsprüfung

## Bewusst nicht enthalten

- Active Directory / Domain GPO
- Domain Controller
- RDS / Terminalserver
- Intune / MDM / Autopilot
- Windows Server 2022 / 2025
- Microsoft 365 / Office Hardening
- Adobe / Acrobat Hardening
- zentraler Zero-Touch-Rollout
- Managed-Service- oder MSP-Nutzung ohne separate Vereinbarung
- individuelle Architektur-, Risiko- oder Compliance-Beratung

## Varianten und Geräteumfang

Die gekaufte Variante bestimmt den zulässigen Geräteumfang:

- **Solo**: CHF 149, bis zu 3 Geräte
- **Team**: CHF 399, bis zu 10 Geräte
- **Business**: CHF 599, bis zu 25 Geräte

## Support- und Betriebsgrenzen

Das Produkt ist auf einen **konservativen, dokumentierten Scope** ausgelegt. Daraus folgt:

- zuerst auf **Pilotgerät / Nicht-Produktivsystem** testen
- Backup / Snapshot / Recovery vor Einsatz sicherstellen
- Drucker, NAS, Netzlaufwerke, RDP und Fachanwendungen vor breiter Ausrollung mitdenken
- keine stillschweigende Zusage für Kompatibilität mit Drittsoftware, Legacy-Druckern, alten NAS- oder SMB-/NTLM-Abhängigkeiten
- Support richtet sich nach **gekaufter Variante**, **Produktbeschreibung** und **dokumentiertem Scope**

## Weiter

- [Get Started](../docs/get-started)
- [Support-Matrix](../docs/support-matrix)
- [Pre-Deploy-Checkliste](../docs/pre-deploy-checklist)
- [FAQ](../docs/faq)
- [Pakete & Lieferung](../buy)
- [Rechtliches](../legal)
