---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: 2026 Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS; 2019-2024 The Foundation for Public Code <info@publiccode.net>, https://www.standardforpubliccode.org/AUTHORS
order: 15
title: "Använd en enhetlig stil"
redirect_from:
  - criteria/style
---
# Använd en enhetlig stil

Att följa en konsekvent och enhetlig stil gör det möjligt för bidragsgivare i olika miljöer att arbeta tillsammans.
Att ena terminologin minskar friktionen i kommunikationen mellan bidragsgivare.

## Krav

* [Kodbasen](../glossary.md#kodbas) MÅSTE använda en stil- eller skrivguide för kod, antingen kodbasgemenskapens egen eller en befintlig som hänvisas till i kodbasen.
* Bidrag BÖR klara automatiserade stiltest.
* Stilguiden BÖR innehålla förväntningar på kommentarer i koden och dokumentation för icke-triviala avsnitt.
* Att ta med förväntningar på [begriplig engelska](use-plain-english.md) i stilguiden är VALFRITT.

## Hur du testar

* Bekräfta att bidrag är i linje med de stilguider som anges i dokumentationen.
* Kontrollera om det finns automatiserade stiltest.

## Offentliga beslutsfattare: detta behöver ni göra

* Skapa, följ och förbättra kontinuerligt en stilguide för [regelverk](../glossary.md#regelverk) och dokumentation och dokumentera detta i kodbasen, till exempel i `CONTRIBUTING`- eller `README`-filen.

## Chefer: detta behöver ni göra

* Ta med standarder för skriftspråk, källkod, tester och regelverk i er organisations definition av kvalitet.

## Utvecklare och formgivare: detta behöver ni göra

Om kodbasen inte redan har tekniska riktlinjer eller annan vägledning för bidragsgivare, börja med att lägga till dokumentation i [kodförrådet](../glossary.md#kodförråd) som beskriver hur det görs nu, till exempel i `CONTRIBUTING`- eller `README`-filen.
Ett viktigt syfte med filen är att kommunicera designval, namngivningskonventioner och andra aspekter som maskiner inte enkelt kan kontrollera.
Vägledningen bör innefatta vad som förväntas av [källkods](../glossary.md#källkod)bidrag för att de ska sammanslås av förvaltarna, inbegripet källkod, tester och dokumentation.
Förbättra och utöka denna dokumentation fortlöpande med målet att den ska utvecklas till tekniska riktlinjer.

Dessutom:

* Använd en stilgranskare.
* Lägg till konfigurationer för stilgranskaren i kodbasen.

## Vidare läsning

* [Programming style](https://en.wikipedia.org/wiki/Programming_style) på Wikipedia.
