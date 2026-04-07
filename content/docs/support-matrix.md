---
title: Support-Matrix
description: Offiziell unterstützte, optionale und nicht unterstützte Einsatzszenarien für v1.
---

Diese Matrix beschreibt den **verbindlichen Scope von v1**. Alles außerhalb davon ist entweder **Best Effort / optional** oder **bewusst nicht unterstützt**.

## Offiziell unterstützt

- **Betriebssystem:** Windows 11
- **Edition:** Pro
- **Primärer Release-Stand:** 25H2
- **Zusätzlich unterstützt:** 24H2
- **Sprache:** de-DE und en-US
- **Deployment:** lokal via LGPO.exe
- **Umgebung:** Workgroup / Einzelgeräte / kleine Umgebungen
- **Kernbereiche v1:**
  - Defender Basis
  - Firewall Basis
  - Audit Basis
  - UAC / LSA Basis
  - Windows Update Basis

## Best Effort / optional

- Windows 11 Enterprise
- Browser-Hardening als separates Add-on
- konservative SMB-/Netzwerk-Härtung nach Umgebungsprüfung

## Nicht unterstützt / nicht empfohlen

- Windows 11 Home
- Windows Server 2022 / 2025
- Active Directory / Domain GPO
- Domain Controller
- RDS / Terminalserver
- Intune-, MDM- oder Autopilot-verwaltete Geräte
- Microsoft 365 / Office Hardening
- Adobe / Acrobat Hardening
- produktionskritische Spezialumgebungen ohne separaten Test
- zentraler Zero-Touch-Rollout in produktive Flotten

## Variantenrahmen

- **Solo:** CHF 149, bis zu 3 Geräte
- **Team:** CHF 399, bis zu 10 Geräte
- **Business:** CHF 599, bis zu 25 Geräte

## Wichtig

Diese Matrix ersetzt **nicht** Pilotgerät, Backup, Recovery und Funktionstest. Sie grenzt den Produkt-Scope ab; die Verantwortung für saubere Vorprüfung und kontrollierten Einsatz bleibt beim Käufer.

## Weiter

- [Get Started](get-started)
- [Pre-Deploy-Checkliste](pre-deploy-checklist)
- [Produkt](../product)
