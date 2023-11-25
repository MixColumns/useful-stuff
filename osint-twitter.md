---
title: Twitter
layout: default
parent: OSINT & ITS
grand_parent: Home
nav_order: 1
---

# Twitter
## Sicherheit
Anderen Nutzern ist unbekannt wonach man sucht oder welche Aktionen man durchführt.
Sofern nicht mit anderen Tweets interagiert wird gibt es wenig zu beachten.
Im Grunde kann man nach belieben Tweets suchen und analysieren, ohne dass jemand anderes es bemerkt.
Bei verweisen auf externe Ressourcen sollte man jedoch vorsichtiger sein was beispielsweise Downloads angeht.

## Suchoperatoren
Angelehnt an [A Guide To Twitter Search Operators: OSINT](https://roddytech.medium.com/a-guide-to-twitters-search-operators-osint-%EF%B8%8F-%EF%B8%8F-b617bb7c59a)


**""**\
Sucht nach dem genauen Text in Anführungszeichen z.B. "Katzen"\
**OR**\
Sucht nach einer Sache oder der anderen z.B. "Katzen" OR "Hunde"\
**-search term**\
Schließt einen Begriff aus z.B. "Hunde" -"Katzen"\
**#hashtag**\
Sucht nach einem Hashtag z.B. #Katzen\
**from:handle**\
Sucht alle Nachrichten von einem Account z.B. from:@hund\
**to:handle**\
Sucht alle Nachrichten an einen Account z.B. to:katze\
**@handle**\
Sucht alle Nachrichten die @handle erwähnen z.B. @Hund\
**since:YYYY-MM-DD**\
Sucht alle Nachrichten ab dem Zeitpunkt z.B. Hunde since:2019–3–24\
**until:YYYY-MM-DD**\
Sucht alle Nachrichten bis zu dem Zeitpunk z.B. Hunde until:2019–3–24\
**filter:media**\
Sucht nur Nachrichten mit Medieninhalt z.B. from:@hund filter:media\
**filter:images**\
Sucht nur Nachrichten mit Bikldern z.B. hunde filter:images\
**filter:videos**\
Sucht nur Nachrichten mit Videos z.B. katzen filter:videos\
**url:**\
Sucht nach Nachrichten mit einer URL die den Text enthält z.B. "Angebote" url:ebay\
**lang:**\
Sucht nach Nachrichten in einer spezifischen Sprache (nutzt Ländercodes) z.B lang:de\
**near:**\
Sucht Nachrichten in der Nähe eines Ortes z.B. Protest near:berlin\
**within:**\
Sucht Nachrichten in einem Radius z.B. Protest near:Berlin within:10km\
**geocode:Latitude,Longitude,Radius**\
Sucht nach Nachrichten zu gegebenen Koordinaten und Radius z.B. geocode:52.5200,13.4050,20km\

Der Suchterm

> geocode:38.889943,-77.011244,.5km since:2021–01–05 until:2021–01–07

findet beispielsweise alle Tweets vom 05.01.2021 bis zum 07.01.2021 in einem Umkreis von 500 Metern um das US-Kapitol.
Zu dem Zeitpunkt fand der [Sturm auf das Kapitol in Washington 2021](https://de.wikipedia.org/wiki/Sturm_auf_das_Kapitol_in_Washington_2021) statt.

## Die erweiterte Suche
Unter [https://twitter.com/search-advanced](https://twitter.com/search-advanced) findet sich die erweiterte Twitter Suche.
Damit können Nachrichten von beispielsweise einem spezifischen Account durchsucht werden.
Es lässt sich auch nach einem Zeitraum oder Keywords filtern.
Im Grunde einfach nur eine grafische Eingabemaske für die Suchoperatoren.


[//]: <> ## twint
[//]: <> ToDo
[//]: <> https://osintfr.com/en/ukraine-twitter-analysis-twint-gephi-tutorial/

[//]: <> ## twosint
[//]: <> ToDo

[//]: <> ## Trends




[//]: <> https://onemilliontweetmap.com/?center=25.505,-0.09&zoom=2&search=&timeStep=0&timeSelector=0&hashtag1=&hashtag2=sad&sidebar=yes&hashtagBattle=0&timeRange=0&timeRange=25&heatmap=0&sun=0&cluster=1