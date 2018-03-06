---
layout: projects
title: "Komunikácia s využitím UDP protokolu"
image_path: https://images.g2crowd.com/uploads/product/image/large_detail/large_detail_1489695931/postgresql.png
---
Náplňou projektu bolo vytvorenie programu, ktorý umožňoval komunikáciu účastníkov v sieti Ethernet využitím protokolu UDP (User Datagram Protocol) transportnej vrstvy sieťového modelu TCP/IP. Počas jeho vypracovania bol navrhnutý vlastný protokol, ktorý slúžil na inicializáciu spojenia, prenos správ a ich identifikáciu, overenie správnosti prenosu využitím CRC a nakoniec aj ukončenia spojenia. Na implementáciu bol využitý programovací jazyk Java, súčasťou bolo aj používateľské rozhranie pre klientsku aj pre serverovú časť aplikácie. To využívalo Java Swing. Program umožňoval používateľovi nastaviť si veľkosť fragmentu, adresu i port. Okrem prenosu správ bolo možné prenášať aj súbory uložené na disku a zvoliť, kde na cieľovom zariadení sa budú ukladať. Zároveň bol využitý koncept viacerých súčasne bežiacich vlákien (multithreading).
