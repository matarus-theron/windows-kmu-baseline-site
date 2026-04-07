---
title: FAQ
description: Häufige Fragen zum Windows KMU Baseline Pack v1.
---

## Für wen ist das Produkt gedacht?

Für kleine Firmen / KMU ohne eigene IT-Abteilung, die **Windows 11 Pro 24H2** lokal administrieren und eine nachvollziehbare Baseline für **Einzelgeräte oder kleine Workgroup-Umgebungen** suchen.

## Welche Windows-Version wird unterstützt?

Offiziell unterstützt ist **Windows 11 Pro 24H2** in **de-DE** und **en-US**.

## Wird Active Directory unterstützt?

Nein. v1 ist bewusst **nicht** für Active Directory / Domain GPO gebaut, sondern für **lokale Ausrollung via LGPO.exe**.

## Ist Intune oder MDM im Scope?

Nein. Intune-, MDM- und Autopilot-verwaltete Geräte sind **nicht Ziel von v1**.

## Welche Bereiche deckt die Kernbaseline ab?

v1 fokussiert auf:

- Defender Basis
- Firewall Basis
- Audit Basis
- UAC / LSA Basis
- Windows Update Basis

## Ist das ein Managed Service oder Beratungsprodukt?

Nein. Das Produkt ist als **digitales B2B-Paket** gedacht, nicht als Workshop, Managed Service oder individuelle Beratungsleistung.

## Ist MSP- oder Drittkundennutzung enthalten?

Nein. Eine Standardlizenz ist für die **interne Nutzung in der lizenzierten Organisation** gedacht. MSP-, Reseller- oder Drittkundennutzung benötigen eine **separate Vereinbarung**.

## Sollte direkt breit ausgerollt werden?

Nein. Immer zuerst auf **Pilotgerät / Nicht-Produktivsystem** testen, dann Funktion prüfen und erst danach kontrolliert weiter ausrollen.

## Ist Support automatisch enthalten?

Support richtet sich nach **gekaufter Variante**, **Produktbeschreibung** und **dokumentiertem Scope**. Es gibt keinen stillschweigenden Anspruch auf individuelle Hilfe außerhalb des beschriebenen Rahmens.

## Gibt es eine Zusage für Kompatibilität mit Drittsoftware?

Nein. Vor breiter Ausrollung sollten insbesondere Drucker, NAS, Netzlaufwerke, RDP und Fachanwendungen im Pilotbetrieb geprüft werden.

## Weiter

- [Get Started](get-started)
- [Pre-Deploy-Checkliste](pre-deploy-checklist)
- [Support-Matrix](support-matrix)
- [Produkt](../product)
- [Rechtliches](../legal)
