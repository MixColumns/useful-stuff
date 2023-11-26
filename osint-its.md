---
title: OSINT & ITS
layout: default
parent: Home
nav_order: 2
has_children: true
---

# Übersicht
{: .no_toc }

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}

# OSINT

Das Bundesamt für Verfassungsschutz beschreibt [auf seiner Website](https://www.verfassungsschutz.de/SharedDocs/glosaareintraege/DE/O/osint.html) ganz gut, was OSINT ist:

> Open Source Intelligence (OSINT) bezeichnet die Informationsgewinnung aus offenen Quellen. OSINT-Maßnahmen sind das Monitoring von Internetseiten, aber auch die gezielte Recherche nach sämtlichen öffentlich zugänglichen Informationen zu einer Zielperson. Offen zugängliche Informationen stehen auch für Nachrichtendienste meist am Anfang ihrer Informationsbeschaffung. 

Der Übergang zur IT-Sicherheit und der näheren Analyse gewisser Dinge beispielsweise dem Quellcode einer Website ist dabei fließend.
Daher habe ich hier beide Themen ein wenig vermischt. 
Ich vermische ebenfalls bewusst Open Source Investigations und Open Source Inteligence - einfach weil ich keine Lust habe mich mit der genauen Trennung zu befassen.
Ein schönes Beispiel aus neuerer Zeit ist die Nutzung von OSINT [bezüglich](https://en.wikipedia.org/wiki/Open-source_intelligence_in_the_Russian_invasion_of_Ukraine) der Invasion der Ukraine.

Die Informationen können vielfältig genutzt werden und die Motivationen können sehr unterschiedlich sein.
Beispielsweise können entsprechende Informationen helfen einen wirtschaftlichen Vorteil zu erlangen, politisches Geschehen besser zu beurteilen oder Straftaten aufzudecken, aber auch Spionage ist denkbar.
Die Möglichkeiten die erlangten Informationen zu nutzen sind genauso vielfältig wie die Motivation für OSINT selbst.

Informationen sammeln und zusammenstellen kann prinzipiell jeder, wobei die Individuellen Fähigkeiten die Möglichkeiten beschränken aber auch erweitern.
Daher ist es gerade in Bereichen wie [Citizen journalism](https://en.wikipedia.org/wiki/Citizen_journalism) in Kombination mit [Crowdsourcing](https://de.wikipedia.org/wiki/Crowdsourcing) interessant, wenn beispielsweise auf Twitter gemeinsam OSINT betrieben wird um politische Ereignisse zu analysieren.

<b>Es ist vollkommen legal, auf öffentlich zugängliche Daten zuzugreifen, sie zu analysieren und zu verteilen.</b>
Im Graubereich zwischen legal und illegal (z.B. durch hacking) erworbene Daten sollte man zumindest vorsichtig sein.

## Grundlagen

Eine etwas veraltete Quelle ist das [NATO OSINT Handbook V 1.2](https://archive.org/details/NATOOSINTHandbookV1.2/mode/2up) aus dem ich abgewandelt ein paar Punkte übernehme.

### Folgendes Wissen hilft dabei eine Problemstellung zu analysieren:
- Wissen, wer Bescheid weiß
- Wissen, was was ist
- Wissen, was wichtig ist
- Wissen, wer wer ist

### Wobei es sich lohnt einen der folgenden Ansätze zu verfolgen:
- <b>Analystengesteuert</b> Basierend auf der Kenntnis von Problemen und konkreten Informationen
- <b>Ereignisgesteuert</b> Als Reaktion auf zeitkritische relevante Ereignisse
- <b>Geplant Regelmäßige Aktivitäten</b> Zur Dokumentation und Aktualisierung der Informationen

Desweiteren sollten Informationen, wenn angemssen (also z.B. weil möglicherweise relevant), <b>sofort Archiviert werden</b>.

## Mögliche Quellen
(Übernommen aus der Englischen Wikipedia)
Um etwas Inpsiration zu geben, was mögliche Quellen sind:

### Medien
Zeitungen, Magazine, Radio, TV, usw.

### Internet
E-Books o.ä., Blogs, Diskussionsgruppen und Foren, citizen media, social media usw.
Oftmals sind Informationen hier besonders schnell verfügbar.

### Öffentliche Regierungsdaten
Berichte, Budgets, Anhörungen, Telefonlisten, Pressekonferenzen, Websiten, Reden, Open-Data, Gerichtsdokumente usw.

### Professionelle und Akademische Daten
Journals und wissenschaftliche Paper, Konferenzen, Dissertationen und Abschlussarbeiten, usw.

### Kommerzielle Daten
Datenbanken, (Satteliten-)bilder usw. - hier eher uninteressant, da oftmals teuer.

### Geschäftliche Daten
Geschäftsberichte und Dokumente, Handelsregister, Stellenanzeigen usw.

### Grey literature
Technische Berichte, Preprints, Patente, Newsletter, unveröffentlichte Arbeiten usw.

## Sicherheitsmaßnahmen
Die nötigen Sicherheitsmaßnahmen hängen sehr davon ab was man macht.
Zum einen fällt viel in den Bereich IT-Sicherheit und Selbstschutz, beispielsweise keine unbekannten Downloads zu öffnen oder eine virtuelle Maschine dafür zu nutzen.
Zum anderen fällt viel in den Bereich OPSEC (operational security) - welche Aktionen könnten bemerkt werden und könnten diese anschließend weitere Nachforschungen erschweren oder zu Gegenaktionen führen.
Hier kann man keine wirkliche einfache Zusammenfassung geben, jedoch darauf Hinweisen diese beiden Punkte im Kopf zu behalten.

## Metadaten
Metadaten können sehr hilfreich sein. 
Eine Analyse wann posts erstellt werden kann beispielsweise Rückschlüsse darauf zulassen, wann jemand normalerweise schläft.
Mit dieser Information kann man beispielweise versuchen die Zeitzone herauszufinden.
In Kombination mit Bildern kann man dann den Ort weiter eingrenzen, ebenso durch lokale Dialekte oder besonderheiten in der Sprache.
Es lohnt sich immer auf solche Details zu schauen - welche weiteren Informationen bietet mir beispielsweise ein Post in sozialen Netzwerken?
Das ganze kann man unter dem Begriff Geosocial Footprint zusammenfassen.
Was man damit so alles anstellen kann wird unter anderem in diesem unterhaltsamen Video gezeigt:
<iframe width="560" height="315" src="https://www.youtube.com/embed/-YpwsdRKt8Q?si=ypp74agD2GBg25oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

[//]: <> ## Websites
[//]: <> Hierfür greife ich unter anderem auf den Artikel [Into the Jungle: Best Practices for Open-Source Researchers](https://cset.georgetown.edu/article/into-the-jungle-best-practices-for-open-source-researchers/) von CSET zurück.
[//]: <> Cached
[//]: <> Live
[//]: <> Archivieren
[//]: <> Online
[//]: <> Lokal

## Weitere Ressourcen
* [SunCalc](https://www.suncalc.org) - Calculate shadows for a given time and place to compare with a given picture
* [Internetrecherche 2.0](https://start.me/p/ek2p4x/internetrecherche-2-0) - Useful Ressources for OSINT research 
* [beautifier.io](https://beautifier.io/) - Tool to make obfuscated javascript quite readable. Works insanely good
* [SSL Test](https://www.ssllabs.com/ssltest/) - Tool to test the security of an SSL setup for a given website
* [DNS dumpster](https://dnsdumpster.com/) - Discover hosts related to a domain
* [CyberChef](https://gchq.github.io/CyberChef/) - A simple, intuitive web app for carrying out all manner of "cyber" operations within a web browser
* [MX Toolbox](https://mxtoolbox.com/SuperTool.aspx) - All of your MX record, DNS, blacklist and SMTP diagnostics in one integrated tool
* [Hardenize](https://www.hardenize.com/) - Automated Discovery and Monitoring of Your Entire Network Perimeter
* [OSINT Framework](https://osintframework.com/) - Different OSINT tools
* [Platforms Hunting](https://cheatsheet.haax.fr/open-source-intelligence-osint/platforms-hunting/) - Some Plattform research stuff
* [OSINT Chine](https://start.me/p/7kLY9R/osint-chine)