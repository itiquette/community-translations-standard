---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: 2026 Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS; 2019-2024 The Foundation for Public Code <info@publiccode.net>, https://www.standardforpubliccode.org/AUTHORS
toc: false
---
# Vägledning för samarbete kring öppen källkod i offentlig sektor

Standarden för offentlig kod är en uppsättning kriterier som stödjer offentliga organisationer i att gemensamt utveckla och förvalta programvara och regelverk.

Standarden för offentlig kod ger vägledning till offentliga organisationer som vill samarbeta framgångsrikt kring lösningar med öppen källkod tillsammans med liknande organisationer på andra platser.
Den innehåller råd för beslutsfattare, chefer inom offentlig förvaltning, utvecklare och leverantörer.
Standarden för offentlig kod främjar gemensamt skapande av kodbaser som är användbara, öppna, läsbara, ansvarsutkrävbara, tillgängliga och hållbara.
Den är avsedd att vara tillämpbar på kodbaser för alla förvaltningsnivåer, från överstatlig till kommunal.

Standarden för offentlig kod definierar "[offentlig kod](glossary.md#offentlig-kod)" som programvara med öppen källkod utvecklad av offentliga organisationer, tillsammans med det regelverk och den vägledning som behövs för samarbete och återanvändning.

Kriterierna i standarden för offentlig kod är i linje med riktlinjer och bästa praxis för utveckling av programvara med öppen källkod.

{% for page in site.pages %}{% if page.dir == "/sv/" and page.name == "foreword.md" %}
Ytterligare sammanhang och bakgrund finns i [förordet](foreword.md).
{% endif%}{% endfor %}

## Innehåll

* [Läsanvisning: hur du tolkar standarden](readers-guide.md)
* [Ordlista](glossary.md)
* [Kriterier](criteria/){% assign sorted = site.pages | sort:"order" %}{% for page in sorted %}{% if page.dir == "/sv/criteria/" %}{% if page.name != "index.md" %}{% if page.title %}
  * [{{page.title}}]({{page.url | relative_url}}){% endif%}{% endif%}{% endif%}{% endfor %}
* [Upphovspersoner](AUTHORS.md)
* [Bidragsguide](CONTRIBUTING.md)
* [Uppförandekod](CODE_OF_CONDUCT.md)
* [Styrning](GOVERNANCE.md)
* [Versionshistorik](RELEASE_NOTES.md)
* [Licens](license.html)

## Gemenskapssamtal

Vi har vanligtvis ett gemenskapssamtal den sista torsdagen i månaden klockan 15:00 (CET/CEST).
Dagordningen samordnas på vårt [diskussionsforum](https://github.com/standard-for-public-code/standard-for-public-code/discussions/categories/community-calls) ungefär en vecka före samtalet.

## Övriga resurser

* Inofficiella [gemenskapsöversättningar av standarden](https://translations.standardforpubliccode.org/) till andra språk
* [Självutvärdering av efterlevnad av standarden](https://publiccodenet.github.io/assessment-eligibility/) för kodbaser med öppen källkod inom offentlig sektor
* [Granskningsmall för standardens kriterier](/docs/review-template.html) som används av Foundation for Public Codes förvaltare vid kodbasgranskning
* [Kompakt kravchecklista](https://github.com/standard-for-public-code/standard-for-public-code/releases/download/0.8.1/standard-checklist-0.8.1.pdf) för utskrift och diskussioner
* [Gemenskapsbyggd handledning](https://standard-for-public-code.github.io/community-implementation-guide-standard/) till standarden för offentlig kod
