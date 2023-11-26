---
title: Twitter | X
layout: default
parent: OSINT & ITS
grand_parent: Home
nav_order: 1
---

# Übersicht
{: .no_toc }

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}

# Twitter

## Archivieren
Je nachdem ob die Informationen nur zur weiteren Suche gespeichert oder beispielsweise zum Melden einer Straftat genutzt werden sollen gibt es unterschiedliche Ansprüche.

### Für Analysezwecke:
- Bilder lassen sich einfach herunterladen.
- Videos können mit Tools wie weiter unten heruntergeladen werden.
- Screenshots können Beispielsweise über die [eingebaute Screenshot Funktion von Firefox](https://support.mozilla.org/en-US/kb/take-screenshots-firefox) aufgenommen werden, selbst Inhalte, die auf der Seite weiter unten außerhalb des Bildschirmbereichs sind.

### Zum Melden von Straftaten:
- Screenshots haben nur bedingte Aussagekraft, da der Inhalt der Website/Bilder einfach geändert werden kann.
Um Screenshots zu speichern eignet sich [Snipping Tool](https://support.microsoft.com/de-de/windows/aufnehmen-von-screenshots-mithilfe-des-snipping-tools-00246869-1843-655f-f220-97299b865f6b) und die Screenshot [Funktion über die "Druck" Taste](https://www.dell.com/support/kbdoc/de-de/000147539/anleitung-zur-verwendung-der-drucktaste-in-microsoft-windows-betriebssystemen).
- Zusätzlich zum Inhalt sollten Uhrzeit, URL und Kontext ersichtlich sein.
- Den Nutzernamen und die ID des Tweet zu speichern ist ebenfalls empfehlenswert.
Die ID wird in der Adresszeile des Browser angezeigt. Um einen Tweet einzeln zu öffnen beispielsweise auf die Uhrzeit klicken.
- Die Plattform [Netzbeweis](https://www.netzbeweis.com/web/) kann dabei helfen Inhalte zu Sichern.
Dafür die URL einfügen und die eigene Email angeben, dann kann ein Report mit Bildern und den wichtigen Informationen kurze Zeit später heruntergeladen werden.

### Videos herunterladen
Mit [twdown.net](https://twdown.net/index.php) lassen sich einfach Videos aus einem Status herunterladen.

## Suchen und Analysieren

### Suchoperatoren
Angelehnt an [A Guide To Twitter Search Operators: OSINT](https://roddytech.medium.com/a-guide-to-twitters-search-operators-osint-%EF%B8%8F-%EF%B8%8F-b617bb7c59a)
Mit diesen hilfreichen Operatoren kann man besser nach Inhalten suchen.

- **""**\
Sucht nach dem genauen Text in Anführungszeichen z.B. "Katzen"\
- **OR**\
Sucht nach einer Sache oder der anderen z.B. "Katzen" OR "Hunde"\
- **-search term**\
Schließt einen Begriff aus z.B. "Hunde" -"Katzen"\
- **#hashtag**\
Sucht nach einem Hashtag z.B. #Katzen\
- **from:handle**\
Sucht alle Nachrichten von einem Account z.B. from:@hund\
- **to:handle**\
Sucht alle Nachrichten an einen Account z.B. to:katze\
- **@handle**\
Sucht alle Nachrichten die @handle erwähnen z.B. @Hund\
- **since:YYYY-MM-DD**\
Sucht alle Nachrichten ab dem Zeitpunkt z.B. Hunde since:2019–3–24\
- **until:YYYY-MM-DD**\
Sucht alle Nachrichten bis zu dem Zeitpunk z.B. Hunde until:2019–3–24\
- **filter:media**\
Sucht nur Nachrichten mit Medieninhalt z.B. from:@hund filter:media\
- **filter:images**\
Sucht nur Nachrichten mit Bikldern z.B. hunde filter:images\
- **filter:videos**\
Sucht nur Nachrichten mit Videos z.B. katzen filter:videos\
- **url:**\
Sucht nach Nachrichten mit einer URL die den Text enthält z.B. "Angebote" url:ebay\
- **lang:**\
Sucht nach Nachrichten in einer spezifischen Sprache (nutzt Ländercodes) z.B lang:de\
- **near:**\
Sucht Nachrichten in der Nähe eines Ortes z.B. Protest near:berlin\
- **within:**\
Sucht Nachrichten in einem Radius z.B. Protest near:Berlin within:10km\
- **geocode:Latitude,Longitude,Radius**\
Sucht nach Nachrichten zu gegebenen Koordinaten und Radius z.B. geocode:52.5200,13.4050,20km\

Der Suchterm

> geocode:38.889943,-77.011244,.5km since:2021–01–05 until:2021–01–07

findet beispielsweise alle Tweets vom 05.01.2021 bis zum 07.01.2021 in einem Umkreis von 500 Metern um das US-Kapitol.
Zu dem Zeitpunkt fand der [Sturm auf das Kapitol in Washington 2021](https://de.wikipedia.org/wiki/Sturm_auf_das_Kapitol_in_Washington_2021) statt.

### Die erweiterte Suche
Unter [https://twitter.com/search-advanced](https://twitter.com/search-advanced) findet sich die erweiterte Twitter Suche.
Damit können Nachrichten von beispielsweise einem spezifischen Account durchsucht werden.
Es lässt sich auch nach einem Zeitraum oder Keywords filtern.
Im Grunde einfach nur eine grafische Eingabemaske für die Suchoperatoren.

### Inhalte
Unter Einstellungen -> Datenschutz und Sicherheit -> Inhalte, die du siehst lassen sich einige interessante Einstellungen festlegen um besser/alle Inhalte zu finden.
Generell lohnt es sich jede der gelisteten Einstellungen zu prüfen, nicht nur für die Suche sondern beispielsweise auch für die eigene Auffindbarkeit oder ähnliches.
Unter dem Punkt Mitteilungen findet sich ebenfalls noch eine Filtereinstellung.

### Metadaten
Für Twitter wären Metadaten beispielsweise Tweets mit Geoinformationen hinterlegt, Orte von denen Bilder gepostet werden, die Sprache, die Uhrzeit, Personen mit denen interagiert wird und so weiter.
Ein Beispiel dazu wie das ganze bezüglich Zeiten aussehen kann findet sich in diesem [GitHub repo](https://github.com/x0rz/tweets_analyzer).
Weiter unten ist ein Bild mit den Aktivitäten nach Tag und Stunde.
Am Beispiel lässt sich deutlich erkennen wann die Person normalwerweise schläft und wann sie Freizeit hat, sowie an welchen Tagen sie möglicherweise arbeitet.
Ob das Projekt noch funktioniert habe ich noch nicht getestet, ich gehe jedoch nicht davon aus.
Generell gilt hier alles was auch normalerweise bei Metadatenanalyse zum Einsatz kommt.

### Tweetmap
Auf [https://www.heavy.ai/demos/tweetmap](https://www.heavy.ai/demos/tweetmap) lassen sich Tweets zu Orten verfolgen.
Man kann einfach nach einem Ort schauen und dann werden Tweets zu diesem Ort angezeigt.
Ähnliche Funktionen bietet [https://onemilliontweetmap.com/](https://onemilliontweetmap.com/).

### Trends
Die Trends können ja nach Ort aufschluss zu wichtigen Ereignissen geben.
Es kann zudem interessant sein die Entwicklung von Trends zu verfolgen.
Mögliche Seiten dafür sind beispielsweise [https://trends24.in/germany/](https://trends24.in/germany/), die [Twitter Trends](https://twitter.com/i/trends) selbst oder auch Seiten wie [https://getdaytrends.com/de/germany/](https://getdaytrends.com/de/germany/) und [https://www.twitter-trending.com/germany/de](https://www.twitter-trending.com/germany/de).
Entsprechend durch Auswahl auch für andere Länder verfügbar.

### IP
Auch hier ist es natürlich möglich eine eigene Website zu basteln die einen IP-logger eingebaut hat (im Grunde jeder Webhoster bei dem man auf die Logfiles zugreifen kann bietet dies von Haus aus).
Wenn man jemanden den Link zusendet und dieser angeklickt wird, hat man, falls keine VPN genutzt wird die IP des Nutzers.
Dies kann sowohl für die Geoinformationen als auch für Strafverfolgung interessant sein.

### Weiteres
Alle Techniken die bei einer normalen Recherche zum Einsatz kommen funktionieren hier natürlich auch.
Profilbilder rückwärts suchen oder verlinkte Seiten ansehen beispielsweise. 

Um zu sehen was beispielsweise noch alles möglich ist gibt es auch eine Spannende Abhandlung von Austin P. Logan von der [US Air University](https://www.airuniversity.af.edu/) mit dem Titel [Analysis of Twitter Networks to Aid Open Source Intelligence Capabilities: A Multilayer Network Approach](https://scholar.afit.edu/cgi/viewcontent.cgi?article=6350&context=etd).

## Nitter
[Nitter](https://nitter.net/) - ein alternatives Frontend für Twitter.
Es ist etwas schneller und minimalistischer als das von Twitter bereitgestellte Frontend und bietet mehr Privacy.
Zudem ist es möglich Inhalte zu lesen ohne mit einem Account angemeldet zu sein.
