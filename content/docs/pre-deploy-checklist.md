---
title: Pre-Deploy-Checkliste
description: Prüfpunkte vor dem ersten Rollout des Windows KMU Baseline Pack.
---

Diese Checkliste ist für den **ersten Test auf Pilotgerät** und für jeden späteren kontrollierten Rollout gedacht.

## Zielsystem und Scope

- Zielsystem ist **Windows 11 Pro**
- Zielrelease ist **24H2**
- System wird **lokal** administriert
- keine AD-, Domain-GPO-, Intune-, MDM- oder Autopilot-Verwaltung aktiv
- Einsatzszenario entspricht **Einzelgerät / Workgroup / kleiner Umgebung**
- Nutzung liegt im dokumentierten **v1-Scope**

## Sicherheit und Wiederherstellung

- aktuelles Backup oder Snapshot vorhanden
- Wiederherstellung im Fehlerfall bekannt
- bei BitLocker: **Recovery Key** gesichert
- lokale Administratorrechte vorhanden
- Test erfolgt zuerst auf **Nicht-Produktivsystem / Pilotgerät**

## Systemzustand

- Gerät ist vollständig aktualisiert
- Neustart nach Updates wurde durchgeführt
- keine offenen größeren Systemfehler oder Admin-Probleme bekannt
- grundlegende Erreichbarkeit von Netzwerk, Internet und Diensten ist vorab geprüft

## Produktive Abhängigkeiten mitdenken

- Drucker berücksichtigt
- NAS / Netzlaufwerke berücksichtigt
- RDP / Fernsupport berücksichtigt, falls benötigt
- Fachanwendungen und Geschäftssoftware berücksichtigt
- bekannte Alt-Abhängigkeiten bei SMB / NTLM oder Legacy-Geräten bedacht

## Rollout-Disziplin

- Dokumentation des Testlaufs vorgesehen
- Ergebnisse auf Pilotgerät werden geprüft, bevor weitere Systeme folgen
- keine breite Ausrollung ohne sauberen Funktionstest
- Support- und Scope-Grenzen sind intern verstanden

## Weiter

- [Get Started](get-started)
- [Support-Matrix](support-matrix)
- [FAQ](faq)
