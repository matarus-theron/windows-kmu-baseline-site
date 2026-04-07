---
title: Get Started
description: Empfohlener Einstieg für Scope-Prüfung, Vorbereitung und Pilot-Rollout.
---

Der richtige Start für dieses Produkt ist **nicht** der schnelle Massenrollout, sondern eine **saubere Vorprüfung** und ein **kontrollierter Test auf Pilotgerät**.

{{< callout type="warning" >}}
Vor produktivem Einsatz immer zuerst auf **Pilotgerät / Nicht-Produktivsystem** testen und **Backup / Snapshot / Recovery** sicherstellen.
{{< /callout >}}

## 1. Scope zuerst prüfen

Bevor überhaupt an Rollout gedacht wird, sollte klar sein:

- Zielsystem ist **Windows 11 Pro**
- **25H2 ist der primäre Zielstand**, **24H2 bleibt weiterhin unterstützt**
- keine AD-, Domain-GPO-, Intune-, MDM- oder Autopilot-Verwaltung aktiv
- Einsatz erfolgt in einer **kleinen Workgroup- oder Einzelgeräte-Umgebung**
- die erwartete Nutzung liegt innerhalb des dokumentierten v1-Scope

## 2. Vor dem ersten Test prüfen

Mindestens sicherstellen:

- aktuelles Backup oder Snapshot vorhanden
- Wiederherstellung im Fehlerfall bekannt
- bei BitLocker: **Recovery Key** gesichert
- Ausführung mit **lokalen Administratorrechten**
- System vollständig aktualisiert
- Neustart nach Updates durchgeführt
- Drucker, NAS, Netzlaufwerke, RDP und Fachanwendungen berücksichtigt

## 3. Pilotgerät bewusst auswählen

Ein gutes Pilotgerät ist:

- repräsentativ für den späteren Zielbestand
- nicht sofort geschäftskritisch
- sauber dokumentierbar
- im Fehlerfall kontrolliert rücksetzbar

## 4. Nach dem Test prüfen

Nach der Anwendung sollte mindestens geprüft werden:

- Anmeldung funktioniert
- Netzwerkzugriff funktioniert
- Internetzugriff funktioniert
- Drucker funktionieren
- Netzlaufwerke / NAS funktionieren
- RDP / Fernsupport funktioniert, falls benötigt
- Fachanwendungen starten korrekt
- Windows-Sicherheitscenter zeigt keine neuen kritischen Warnungen
- Ereignisanzeige zeigt keine neuen Gruppenrichtlinienfehler

## 5. Erst dann weiter ausrollen

Wenn Pilotgerät und Funktionstest sauber laufen, kann der Rollout **kontrolliert** auf weitere Systeme ausgeweitet werden.

## Weiter

- [Support-Matrix](support-matrix)
- [Pre-Deploy-Checkliste](pre-deploy-checklist)
- [FAQ](faq)
- [Produkt](../product)
- [Pakete & Lieferung](../buy)
