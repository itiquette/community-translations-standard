# Att bidra till standarden

<!-- SPDX-License-Identifier: CC0-1.0 -->
<!-- SPDX-FileCopyrightText: 2026 Standard for Public Code Authors, https://www.standardforpubliccode.org/AUTHORS; 2019-2024 The Foundation for Public Code <info@publiccode.net>, https://www.standardforpubliccode.org/AUTHORS -->

Tack för att du bidrar!

Vi förstår att en standard som denna bara kan fastställas i samarbete med så många offentliga teknologer, beslutsfattare och intresserade personer som möjligt.
Därför uppskattar vi dina synpunkter, välkomnar återkoppling och förbättringar av projektet, och är mycket öppna för samarbete.

Vi välkomnar ärenden och ändringsbegäranden från alla.
Om du inte är bekväm med GitHub kan du skicka din återkoppling via e-post till <info@publiccode.net>.

## Problem, förslag och frågor i ärenden

En översikt på hög nivå av den utveckling vi redan har skisserat finns i [färdplanen](/docs/roadmap.md).
Hjälp gärna utvecklingen genom att rapportera problem, föreslå ändringar och ställa frågor.
För att göra detta kan du [skapa ett ärende på GitHub](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue) för projektet i [GitHub-ärenden för standarden för offentlig kod](https://github.com/standard-for-public-code/standard-for-public-code/issues).

Eller delta i [diskussionerna](https://github.com/standard-for-public-code/standard-for-public-code/discussions).

Du behöver inte ändra någon av vår kod eller dokumentation för att vara en bidragsgivare!

## Dokumentation och kod i ändringsbegäranden

Om du vill lägga till dokumentation eller kod i något av våra projekt bör du göra en ändringsbegäran.

Om du aldrig har använt GitHub, kom igång med [Understanding the GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow) eller följ en av de utmärkta kostnadsfria interaktiva kurserna i [GitHub Skills](https://skills.github.com/) om att arbeta med GitHub och Markdown, den syntax som projektets dokumentation är skriven i.

Projektet är licensierat under Creative Commons Zero v1.0 Universal, vilket i huvudsak innebär att projektet, tillsammans med dina bidrag, är i allmän egendom i alla jurisdiktioner där det är möjligt, och att alla kan göra vad de vill med det.

### 1. Gör dina ändringar

Bidrag bör [följa](docs/standard-for-public-code.html) de krav som anges i kriterierna i standarden för offentlig kod.
Granskare kommer också att säkerställa att bidrag är i linje med [offentlig kods värden](foreword.md#offentlig-kods-värden).
Vidare kommer de att granska att bidraget överensstämmer med [standarderna](#standarder-att-följa) och förblir sammanhängande med helheten.

Projektet använder [GitFlow-grenmodellen och arbetsflödet](https://nvie.com/posts/a-successful-git-branching-model/).
När du har förgrenat kodförrådet, se till att skapa en funktionsgren enligt GitFlow-modellen.

Lägg till dina ändringar i incheckningar [med ett meddelande som förklarar dem](https://thoughtbot.com/blog/5-useful-tips-for-a-better-commit-message).
Om mer än en typ av ändring behövs, gruppera logiskt sammanhörande ändringar i separata incheckningar.
Till exempel kan ändringar av blanksteg vara en separat incheckning från ändringar av textinnehåll.
När du lägger till nya filer, välj filformat som enkelt kan granskas i en skillnadsjämförelse — till exempel är `.svg` att föredra framför ett binärt bildformat.
Dokumentera val eller beslut du gör i incheckningsmeddelandet; detta gör det möjligt för alla att i framtiden ta del av dina val.

Om du lägger till kod, se till att du har lagt till och uppdaterat relevant dokumentation och tester innan du skickar in din ändringsbegäran.
Se till att skriva tester som visar beteendet hos den nyligen tillagda eller ändrade koden.

#### Tillämpligt regelverk

För närvarande genomför standarden för offentlig kod inget specifikt offentligt regelverk.

#### Stil

Standarden för offentlig kod strävar efter att [använda enkel engelska](criteria/use-plain-english.md) och vi har valt amerikansk engelska för stavning.
Textinnehåll bör normalt följa en rad per mening, utan radbrytning, för att göra skillnadsjämförelser enklare att granska.
Vi vill dock betona att det är viktigare att du gör ditt bidrag än att du oroar dig för stavning och typografi.
Vi hjälper dig att få det rätt i vår granskningsprocess och vi har också en separat kvalitetskontroll innan vi [gör en ny utgåva](docs/releasing.md).

#### Standarder att följa

Följande standarder används av standarden för offentlig kod.
Se till att dina bidrag är i linje med dem så att de kan sammanslås enklare.

* [IETF RFC 2119](https://tools.ietf.org/html/rfc2119) — för kravnivånyckelord
* [Web Content Accessibility Guidelines 2.1](https://www.w3.org/WAI/WCAG22/quickref/?showtechniques=315#reading-level) — för läsbarhet

### 2. Ändringsbegäran

När du skickar in ändringsbegäran, bifoga en beskrivning av problemet du försöker lösa och ärendenumret som ändringsbegäran åtgärdar.
Det föredras att varje ändringsbegäran hanterar ett enskilt ärende där det är möjligt.
I vissa fall kan en enda uppsättning ändringar lösa flera ärenden — i så fall, se till att lista alla åtgärdade ärendenummer.

### 3. Förbättra

Alla bidrag måste granskas av någon.
Foundation for Public Code har åtagit sig att se till att förvaltare finns tillgängliga för att granska bidrag med målet att ge återkoppling inom två arbetsdagar.

Det kan hända att ditt bidrag kan sammanslås direkt av en förvaltare.
Vanligtvis behöver dock en ny ändringsbegäran vissa förbättringar innan den kan sammanslås.
Andra bidragsgivare (eller hjälprobotar) kan ha återkoppling.
Om så är fallet hjälper den granskande förvaltaren dig att förbättra din dokumentation och kod.

Om din dokumentation och kod har godkänts i granskning sammanslås den.

### 4. Fira

Dina idéer, din dokumentation och din kod har blivit en integrerad del av projektet.
Du är den hjälte inom öppen källkod vi behöver!

Lägg gärna till ditt namn i [`AUTHORS`](AUTHORS.md)-filen genom en ändringsbegäran och få evig tillskrivning.

## Språk och översättningar

Det auktoritativa språket för standarden för offentlig kod är engelska.

Versioner på andra språk tillhandahålls av gemenskapen efter bästa förmåga.
Artighetsöversättningarna kanske inte är aktuella med den engelska versionen, eftersom saknade översättningar inte fördröjer utgåvor.
Vi bjuder in dig att hjälpa till att underhålla befintliga och lägga till nya [gemenskapsöversättningar av standarden](https://github.com/standard-for-public-code/community-translations-standard).

## Utgåvor

Vi har särskild dokumentation för att skapa [nya utgåvor](/docs/releasing.md) och [beställa tryckta standarder](/docs/printing.md).

För mer information om hur man använder och bidrar till projektet, läs [`README`](README.md).
