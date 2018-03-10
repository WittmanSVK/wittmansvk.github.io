---
layout: projects
title: "Databázová aplikácia"
image_path: https://images.g2crowd.com/uploads/product/image/large_detail/large_detail_1489695931/postgresql.png
---

V rámci zadania som vytváral aplikáciu, ktorá zabezpečovala prácu s databázou v doméne správy vojenského múzea. Aplikácia bola vytvorená v programovacom jazyku Java, pričom na ukladanie dát som využíval [PostgreSQL](https://www.postgresql.org/). Hlavná funkcionalita spočívala v zobrazovaní záznamov, ktoré boli stránkované na obrazovku (dôležitá bola práve rýchlosť odozvy a optimalizácia tvorby dopytov). Používateľ mohol zároveň používať viaceré preddefinované filtre s možnosťou kombinácie ich výstupu. Medzi ďalšie činnosti patrilo pridávanie záznamov, úprava záznamov, vymazanie záznamov a zobrazenie konkrétneho záznamu (detaily všetkých jeho atribútov). Pri zmene dát boli využívané transakcie a zároveň boli splnené aj požiadavky na súčasnú prácu s viacerými tabuľkami. Ako už bolo spomenuté, aplikácia mala používateľské rozhranie využitím Java Swing.
