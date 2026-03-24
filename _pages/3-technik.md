---
title: Technische Umsetzung
author: HSD
date: 2024-01-03
category: Jekyll
layout: post
---

## STACK-Fragentyp

Die Aufgaben nutzen den Fragentyp [STACK](https://stack-assessment.org/) (System for Teaching and Assessment using a Computer algebra Kernel). STACK ermöglicht:

- **Randomisierte Aufgabenparameter** durch das Computeralgebrasystem Maxima
- **Automatische Bewertung** mathematischer Ausdrücke
- **Individuelles Feedback** basierend auf typischen Fehlern
- **Mehrteilige Aufgaben** mit abhängigen Teilfragen

## Technische Details

- **CAS-Engine:** Maxima
- **Format:** Moodle-XML, kompatibel mit Moodle 4.x
- **Versionierung:** Git-basiert mit [qbank_gitsync](https://github.com/maths/moodle-qbank_gitsync)

## Qualitätssicherung

Alle Aufgaben durchlaufen einen mehrstufigen Review-Prozess:

1. **Erstellung** -- Aufgabe wird entwickelt und getestet
2. **Prüfung** -- Fachliche und didaktische Begutachtung
3. **Freigabe** -- Aufnahme in die qualitätsgesicherte Sammlung
