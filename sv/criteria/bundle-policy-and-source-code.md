---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: 2026 Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS; 2019-2024 The Foundation for Public Code <info@publiccode.net>, https://www.standardforpubliccode.org/AUTHORS
order: 2
title: "Paketera regelverk och källkod"
redirect_from:
  - criteria/bundle-policy-and-code
---
# Paketera regelverk och källkod

Tillgång till både [källkod](../glossary.md#källkod) och dokumentation av [regelverk](../glossary.md#regelverk) ger byggstenar för vem som helst att genomföra kodbasen i sitt lokala sammanhang eller bidra till [kodbasens](../glossary.md#kodbas) fortsatta utveckling.

Att förstå domänen och regelverken inom den domänen är grundläggande för att förstå vilka problem en kodbas försöker lösa och hur den gör det.

För att kunna bedöma om en kodbas ska genomföras i ett nytt sammanhang behöver en organisation förstå vilka processförändringar den måste välja att göra eller hur den kan bidra med ytterligare konfigurerbarhet till den befintliga lösningen för att anpassa den till det nya sammanhanget.

## Krav

* Kodbasen MÅSTE innehålla det regelverk som källkoden bygger på.
* Om ett regelverk bygger på källkod MÅSTE den källkoden ingå i kodbasen, såvida den inte används för att upptäcka bedrägerier.
* Regelverk BÖR tillhandahållas i maskinläsbara och entydiga format.
* Tester för [kontinuerlig integrering](../glossary.md#kontinuerlig-integrering) BÖR verifiera att källkoden och regelverket verkställs på ett sammanhängande sätt.

## Hur du testar

* Bekräfta med en tjänsteperson att allt regelverk som källkoden bygger på finns innefattat.
* Bekräfta med en tjänsteperson att all källkod som regelverket bygger på finns innefattad.
* Kontrollera om regelverket kan tolkas av en maskin.
* Kontrollera att testerna för kontinuerlig integrering för sammanhängande verkställande av källkod och regelverk godkänns.

## Offentliga beslutsfattare: vad ni behöver göra

* Samarbeta med utvecklare och formgivare för att säkerställa att det inte finns någon diskrepans mellan regelverkskod och källkod.
* Tillhandahåll relevanta regelverkstexter för medtagning i [kodförrådet](../glossary.md#kodförråd); om texten inte finns tillgänglig på engelska, tillhandahåll även en engelsk sammanfattning. Se till att ta med standarder som er organisation har valt att följa och alla organisatoriska processer som påverkar utvecklingen eller driftsättningssammanhanget för kodbasen i er organisation.
* Tillhandahåll hänvisningar och länkar till texter som stödjer regelverken.
* Dokumentera regelverk i format som är entydiga och maskinläsbara, såsom de som publicerats av [Object Management Group](https://www.omg.org/spec/).
* Följ regelverk med [samma versionshantering](maintain-version-control.md) och dokumentation som används för att följa källkod.
* Stäm av regelbundet för att förstå hur källkoden i kodbasen har förändrats och om den fortfarande överensstämmer med [regelverkets intentioner](document-codebase-objectives.md).
* Ta med relevanta regelverk som påverkar gemenskapen, kodbasen och utvecklingen, inbegripet rättsliga skyldigheter som [dataskyddsförordningen](https://eur-lex.europa.eu/eli/reg/2016/679/oj) eller [EU:s tillgänglighetsdirektiv för webben](https://ec.europa.eu/digital-single-market/en/web-accessibility), eller rättighetsregelverk, som en offentlig organisations åtagande om lika möjligheter.

## Chefer: vad ni behöver göra

* Håll beslutsfattare, utvecklare och formgivare delaktiga och sammankopplade genom hela utvecklingsprocessen.
* Säkerställ att beslutsfattare, utvecklare och formgivare arbetar mot samma mål.

## Utvecklare och formgivare: vad ni behöver göra

* Sätt er in i och lär er använda den processmodelleringsnotation som beslutsfattarna i er organisation använder.
* Arbeta tillsammans med beslutsfattare för att säkerställa att det inte finns någon diskrepans mellan regelverkskod och källkod.
* Ge återkoppling om hur dokumentationen av regelverk kan göras tydligare.

## Vidare läsning

* [Business Process Model and Notation](https://en.wikipedia.org/wiki/Business_Process_Model_and_Notation) på Wikipedia.
* [BPMN Quick Guide](https://www.bpmnquickguide.com/view-bpmn-quick-guide/) av Trisotech.
* [Decision Model and Notation](https://en.wikipedia.org/wiki/Decision_Model_and_Notation) på Wikipedia.
* [Case Management Model Notation](https://en.wikipedia.org/wiki/CMMN) på Wikipedia.
