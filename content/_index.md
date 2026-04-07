---
title: Windows KMU Baseline Pack
description: Produktisierte Windows-11-Baseline für kleine Unternehmen ohne eigene IT-Abteilung.
---

# Windows KMU Baseline Pack

Ein technisch sauberes, modular aufgebautes Hardening- und Policy-Paket für **Windows 11 Pro** in **kleinen Umgebungen ohne Active Directory**. Deployment erfolgt lokal über **LGPO.exe**. :contentReference[oaicite:1]{index=1}

{{< callout type="important" >}}
**v1-Fokus:** Windows 11 Pro, 24H2, de-DE und en-US, lokales Deployment via LGPO.exe, kleine Workgroup-Umgebungen. :contentReference[oaicite:2]{index=2}
{{< /callout >}}

## Einstieg

{{< cards cols="2" >}}
  {{< card link="/de/docs" title="Dokumentation" subtitle="Technischer Einstieg, Scope und Orientierung" icon="book-open" >}}
  {{< card link="/de/docs/support-matrix" title="Support-Matrix" subtitle="Was offiziell unterstützt wird und was nicht" icon="shield-check" >}}
  {{< card link="/de/docs/pre-deploy-checklist" title="Pre-Deploy-Checkliste" subtitle="Vor dem Pilotgerät sauber prüfen" icon="check-circle" >}}
  {{< card link="/de/docs/faq" title="FAQ" subtitle="Kurze Antworten auf die häufigsten Fragen" icon="question-mark-circle" >}}
{{< /cards >}}

## Kernmodule

{{< cards cols="2" >}}
  {{< card link="/de/docs/faq" title="Defender" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/docs/faq" title="Firewall" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/docs/faq" title="UAC / LSA" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
  {{< card link="/de/docs/faq" title="Windows Update" subtitle="Teil der v1-Kernbaseline" tag="Core" tagColor="green" >}}
{{< /cards >}}

## Nicht im Scope von v1

- Active Directory / Domain GPO
- Intune / MDM / Autopilot
- Windows Server
- Office / M365 Hardening
- Adobe / Acrobat Hardening
- Zero-Touch-Rollout

{{< callout type="warning" >}}
Vor produktivem Einsatz: **erst Pilotgerät, dann prüfen, dann gezielt ausrollen**. Backup, Snapshot und Recovery-Möglichkeit sollten vor dem Deployment eingeplant werden. :contentReference[oaicite:3]{index=3}
{{< /callout >}}

## Technische Quelle

Die technische Source of Truth ist das Produkt-Repository:

- [windows-kmu-baseline-pack](https://github.com/matarus-theron/windows-kmu-baseline-pack)

## Rechtliches

- [Legal](/de/legal)
- [Lizenz](/de/legal/license)
- [Datenschutz](/de/legal/privacy)