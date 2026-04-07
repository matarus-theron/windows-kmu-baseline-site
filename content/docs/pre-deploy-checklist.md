---
title: Pre-Deploy-Checkliste
description: Prüfpunkte vor dem ersten Rollout des Windows KMU Baseline Pack.
---

Diese Checkliste ist für den **ersten Test auf Pilotgerät** und für jeden späteren kontrollierten Rollout gedacht.

## Zielsystem und Scope

- Zielsystem ist **Windows 11 Pro**
- Zielrelease ist bevorzugt **25H2**; **24H2** bleibt zulässig
- System wird **lokal administriert**
- keine AD-, Domain-GPO-, Intune-, MDM- oder Autopilot-Verwaltung aktiv
- Einsatzszenario passt zu **Einzelgerät / Workgroup / kleiner Umgebung**
- Nutzung liegt innerhalb des dokumentierten **v1-Scope**

## Sicherheit und Recovery

- aktuelles Backup oder Snapshot vorhanden
- Wiederherstellung im Fehlerfall bekannt
- bei BitLocker: **Recovery Key** gesichert
- lokale Administratorrechte vorhanden
- Test beginnt auf **Nicht-Produktivsystem / Pilotgerät**

## Systemzustand

- Gerät ist vollständig aktualisiert
- Neustart nach Updates durchgeführt
- keine größeren offenen Systemfehler oder Admin-Probleme bekannt
- Netzwerk-, Internet- und Basisdienst-Verfügbarkeit vorab geprüft

## Produktive Abhängigkeiten mitdenken

- Drucker berücksichtigt
- NAS / Netzlaufwerke berücksichtigt
- RDP / Fernsupport berücksichtigt, falls benötigt
- Fachanwendungen und Geschäftsanwendungen berücksichtigt
- bekannte Legacy-Abhängigkeiten bei SMB / NTLM oder älteren Geräten berücksichtigt

## Rollout-Disziplin

- Dokumentation des Testlaufs geplant
- Ergebnisse am Pilotgerät werden geprüft, bevor weitere Systeme folgen
- kein breiter Rollout ohne sauberen Funktionstest
- Support- und Scope-Grenzen intern verstanden

## Weiter

- [Get Started](get-started)
- [Support-Matrix](support-matrix)
- [FAQ](faq)
