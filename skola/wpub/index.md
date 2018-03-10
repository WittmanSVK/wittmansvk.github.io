---
layout: default
title: Webové publikovanie
---
### Dokumentácia riešenia webového sídla

## Použité pluginy:
 - Plugin [Emoji for Jekyll](https://github.com/yihangho/emoji-for-jekyll)
 - Plugin [Liquid reading time](https://rubygems.org/gems/liquid_reading_time)

## Kolekcie:
 schoolProjects sú kolekcie riešených predmetov

## Premenné:
 Blogové články používajú premenné:
  - title
  - date
  - category
  - tags
  - author
  - description

  Ďalšie premenné sú použité v samotnom config súbore.

  V rámci jednotlivých stránok sú využíté aj globálne premenné page a site.

## Filtre a tagy:
#### Tagy:
  - if/elsif/else na stránke blogu
  - for cyklus na stránkach blogu, jednotivých príspevkov (post layout) a tagov (tag layout)
  - assign na priradenie hodnoty do premennej na vyjadrenie dĺžky na stránke blogu
  - capture na priradenie času potrebného na prečítanie stránky

#### Filtre:
  - filter size pre zistenie zistenie počtu blogov
  - filter truncate na zobrazenie prvých 20 znakov v projekte (škola-projekty)
  - filter date_to_string použitý pre zobrazenie dátumu v blogu
  - filter number_of_words na zistenie počtu slov v konkrétnom blogu (post layout)
