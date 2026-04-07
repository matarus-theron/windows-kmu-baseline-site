---
title: Get Started
description: Einstieg in das Windows KMU Baseline Pack.
---

# Get Started

Diese Seite ist der empfohlene Einstieg für das **Windows KMU Baseline Pack**.

{{< callout type="important" >}}
Zuerst **nicht** breit ausrollen. Erst auf einem **Pilotgerät** prüfen, dann Resultate bewerten, dann gezielt ausrollen. :contentReference[oaicite:1]{index=1}
{{< /callout >}}

## Zielgruppe

Das Produkt ist für kleine Unternehmen ohne eigene IT-Abteilung gedacht, die eine lokale, klar dokumentierte Windows-11-Baseline benötigen. Deployment erfolgt lokal über **LGPO.exe**. :contentReference[oaicite:2]{index=2}

## Vor dem Start prüfen

{{< cards cols="2" >}}
  {{< card link="/de/docs/support-matrix" title="Support-Matrix" subtitle="Passt das Zielsystem überhaupt in den Scope?" icon="shield-check" >}}
  {{< card link="/de/docs/pre-deploy-checklist" title="Pre-Deploy-Checkliste" subtitle="Vorbereitung vor dem Test auf dem Pilotgerät" icon="check-circle" >}}
  {{< card link="/de/docs/faq" title="FAQ" subtitle="Kurze Antworten auf die häufigsten Fragen" icon="question-mark-circle" >}}
  {{< card link="https://github.com/matarus-theron/windows-kmu-baseline-pack" title="Produkt-Repository" subtitle="Technische Quelle und aktueller Stand" icon="github" >}}
{{< /cards >}}

## Empfohlene Reihenfolge

1. Scope anhand der Support-Matrix prüfen
2. Zielgerät vollständig aktualisieren
3. Neustart durchführen
4. Backup / Snapshot / Recovery sicherstellen
5. Erstes Pilotgerät auswählen
6. Deployment und Resultate dokumentieren

## Kernfokus von v1

- Defender
- Firewall
- UAC / LSA
- Windows Update :contentReference[oaicite:3]{index=3}

## Noch kein öffentlicher Rollout-Shortcut

Diese Seite ist bewusst konservativ gehalten. Sie ersetzt keine produktbegleitende Doku, keine Lizenzunterlagen und keinen kontrollierten Test auf einem Pilotgerät.

## Weiterführend

- [Support-Matrix](/de/docs/support-matrix)
- [Pre-Deploy-Checkliste](/de/docs/pre-deploy-checklist)
- [FAQ](/de/docs/faq)
- [Produkt](/de/product)