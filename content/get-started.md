---
title: Get Started
---

# Get Started

## Vor jedem Rollout

- Backup oder Snapshot erstellen
- Pilotgeraet definieren
- Recovery-Weg kennen
- Drucker, NAS, Netzlaufwerke, RDP und Fachanwendungen pruefen
- sicherstellen, dass das Geraet nicht durch Intune/MDM verwaltet wird

## Empfohlene Kernbaseline

```powershell
.\0010-RC-Run-RecommendedSetup.ps1 -Mode Sections -Section Defender,Firewall,UAC_Lsa,WindowsUpdate -SkipPolicyDefinitions
```

## Hinweis

Das Produkt haertet Systeme und kann Funktionen beeinflussen. Immer zuerst auf einem Pilotgeraet testen.
