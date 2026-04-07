---
title: FAQ
description: Häufige Fragen zum Windows KMU Baseline Pack.
---

# FAQ

## Für wen ist das Produkt gedacht?

Für kleine Unternehmen ohne eigene IT-Abteilung und ohne Active Directory, die eine saubere lokale Windows-11-Baseline benötigen.

## Welche Windows-Version wird unterstützt?

Offiziell unterstützt wird Windows 11 Pro 24H2 in de-DE und en-US.

## Wird Active Directory unterstützt?

Nein. v1 ist bewusst auf lokale Anwendung via LGPO.exe in Workgroup-Umgebungen ausgelegt.

## Ist Intune oder MDM im Scope?

Nein. Intune-, MDM- und Autopilot-verwaltete Geräte sind nicht Ziel von v1.

## Welche Bereiche deckt die Kernbaseline ab?

- Defender
- Firewall
- UAC / LSA
- Windows Update

## Gehören WDAC oder Exploit Protection zur Kernbaseline?

Nein, nicht zur v1-Kernbaseline.

## Sollte direkt breit ausgerollt werden?

Nein. Erst Pilotgerät, dann prüfen, dann gezielt ausrollen.

## Ist das ein Beratungsprodukt?

Nein. Ziel ist ein klar abgegrenztes, produktisiertes Paket.