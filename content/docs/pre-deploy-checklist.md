---
title: Pre-Deploy-Checkliste
description: Prüfpunkte vor dem Deployment des Windows KMU Baseline Pack.
---

# Pre-Deploy-Checkliste

Vor dem Deployment sollte mindestens Folgendes geprüft werden:

## Umgebung

- Zielgerät ist Windows 11 Pro
- Zielversion ist 24H2
- Gerät ist nicht via Active Directory verwaltet
- Gerät ist nicht via Intune / MDM / Autopilot verwaltet
- Einsatzszenario entspricht Workgroup / Einzelgerät / kleiner Umgebung

## Vorbereitung

- Pilotgerät zuerst
- Backup / Snapshot / Recovery-Möglichkeit vorhanden
- lokale Administratorrechte vorhanden
- Gerät ist vollständig aktualisiert
- Neustart nach Updates durchgeführt

## Produkt-Fit

- Ziel ist lokale Baseline-Härtung via LGPO.exe
- Fokus liegt auf Defender, Firewall, UAC / LSA und Windows Update
- keine Abhängigkeit von Domain GPO
- keine Erwartung an Office-/Adobe-/Server-Hardening

## Empfehlung

Zuerst auf einem Pilotgerät testen und Resultate vor breiterem Rollout dokumentieren.