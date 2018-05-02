---
layout: default
title: Webové publikovanie
---
### Dokumentácia zadania 3

## Štruktúra
Bol vytvorený XML súbor s prezentáciou (_prezentacia.xml_), ktorá má dĺžku 13 stránok vrátane úvodnej stránky. Štruktúra vytvoreného xml dokumentu je validovaná podľa schémy _schema.rng_ vytvorenej s použitím **RELAX NG**. Následne boli vytvorené dva XSL súbory a to _html-style.xsl_ a _style.xsl_. Html-style slúži na opis transformácií prevodu xml dokumentu na 13 html dokumentov. Je pri tom využitý príkaz **xsl:result-document**, ktorý pri každom výskyte elementu typu page alebo head (úvodná stránka) vytvorí nový HTML súbor, pričom sa využívajú CSS štýly. Style.xsl popisuje transformácie do XSL-FO, z čoho je potom vytvorený PDF dokument.

## Výsledok
Pri vytváraní zadania bolo dôležité, aby boli obe výsledné formy (pdf súbor aj html súbory) pri rovnakých parametroch rovnaké. To sa vo výsledku aj podarilo. Zároveň som sa snažil čo najviac používať _apply-template_ namiesto konštrukcií ako _xsl:for-each_ s cieľom ľahkej prispôsobiteľnosti vytváranej prezentácie a jej ľahkej modifikácie. Používateľ má na výber z troch parametrov a to: **pagenumbers** (vygenerovanie čísel strán), **navigation** (vygenerovanie orientačných šípok v html dokumente) a **titlepage** (naviazanie prvej stránky prezentácie na úvodnú stránku s informáciami o prezentácií pri html dokumente).
