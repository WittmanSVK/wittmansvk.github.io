---
layout: default
title: Webové publikovanie
---
### Dokumentácia zadania 2

## Štruktúra dokumentu
Pri vypracovaní zadania 2 bola použitá šablóna zo stránky predmetu. Zvyšné elementy boli vytvorené podľa online dokumentácie k Docbooku. Text dokumentu je členený nasledovne: na začiatku je abstrakt s informáciami o dokumente. Nasledujú kapitoly, ktoré sú ďalej členené na sekcie a tie ešte znova na ďalšie sekcie. Na konci dokumentu sa nachádzajú dve prílohy. Na začiatku sa nachádza vygenerovaný obsah, zoznam obrázkov a zoznam tabuliek.

## Index a literatúra

Za hlavným obsahom dokumentu je umiestnený register pojmov (index), v xml jeho pozíciu označuje tag _&lt;index/&gt;_. Tam, kde to bolo vhodné, sú pojmy usporiadané hierarchicky do dvoch úrovní (napríklad "Vývojové dosky, Arduino", "Vývojové dosky, Nanode", "Vývojové dosky, Raspberry" alebo "Protokol, HTTPS", "Protokol, IPsec", "Protokol, SSL" atď.). Na konci dokumentu má svoje miesto použitá literatúra. Tá je vo formáte _&lt;bibliolist&gt;_ skladajúceho sa z jednotlivých položiek _&lt;biblioentry&gt;_. Každý záznam obsahuje zoznam autorov, názov dokumentu, jeho url adresu a dátum, kedy bol citovaný. V dokumente je na zdroje odkazované pomocou skratky (_&lt;abbrev&gt;_) daného zdroja v tagu _&lt;citation&gt;_.

## Zvýraznenie slov, prepojenia, obrázky, tabuľky

V dokumente je použité zvýraznenie slov tučným fontom a kurzívou (_&lt;emphasis&gt;_). Text je na viacerých miestach členený číslovaným zoznamom (_&lt;orderedlist&gt;_). V časti Arduino Uno, Raspberry Pi a Nanode Classic sú použité aj prepojenia na sekcie vlastného dokumentu (_&lt;link linkend='id'&gt;_). V celom dokumente sú používané aj poznámky pod čiarou odkazujúce na webové stránky. Nachádza sa tu jeden obrázok vývojovej dosky arduino, logo FIIT použité na prvej strane dokumentu a dve vytvorené tabuľky. Na obrázok aj na tabuľky sú pridané odkazy v texte pomocou (_&lt;link linkend='id'&gt;_).

## Úprava XSL šablón

Pri tvorbe boli modifikované aj XSL súbory: thesis.xsl - do generate.toc boli pridané položky figure,table na generovanie zoznamu obrázkov a tabuliek a thesis-tp-fo.xsl - najmä úprava veľkosti písma, fontov a podobne, aby bol vygenerovaný dokument čo najviac podobný s pôvodným dokumentom.
