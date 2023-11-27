---
title: Bluesky
layout: default
parent: Socialmedia
grand_parent: OSINT & ITS
---

# Übersicht
{: .no_toc }

## Inhaltsverzeichnis
{: .no_toc .text-delta }

1. TOC
{:toc}

# Bluesky

## Archivieren
Das generell Vorgehen zum archivieren wird bereits unter [socialmedia]({% link socialmedia.md %}) erklärt.

## Suchen und Analysieren
Der Großteil der Links stammt aus den folgenden drei GitHub repos:
- [fishttp/awesome-bluesky](https://github.com/fishttp/awesome-bluesky)
- [scrub-dev/bsky-index](https://github.com/scrub-dev/bsky-index/)
- [beeman/awesome-atproto](https://github.com/beeman/awesome-atproto)

Einiges davon habe ich auch mit Bildern in einem Post [auf Bluesky selbst](https://bsky.app/profile/genericzoomer.bsky.social/post/3kcsfq3bsri2r) zusammengefasst (dort sind auch ein paar Bilder vorhanden).
In den Repos finden sich auch noch viel mehr weitere Spielereien, die ich hier nicht gesondert erwähne.

Welche Daten öffentlich verfügbar sind und somit analysiert werden können:
- Beiträge und Likes sind öffentlich
- Sperrungen sind öffentlich
- Stummschaltungen sind privat, aber Mutelisten sind öffentliche Listen. Mutelisten-Abonnements sind privat.
- Zugehörige Metadaten

Daten, die nicht öffentlich sind:
- Einladungen und Einladungsbäume sind privat.

### Post Heatmap
Die Website [bluesky-heatmap.fly.dev](https://bluesky-heatmap.fly.dev/) generiert für einen beliebigen Account eine Heatmap an welchen Tagen wie viel gepostet wird, spannend für die Metadaten.

### Interaktionen

#### Mit anderen Nutzern
Um die Interaktionen eines Nutzers mit anderen Nutzern zu sehen kann die Seite [wolfgang.raios.xyz](https://wolfgang.raios.xyz/interactions) hilfreich sein.

#### Generelle Cluster
Um generelle Cluster zu erkunden bietet sich [bsky.jazco.dev](https://bsky.jazco.dev/atlas) an.
Generelle Statistiken und ein Threadvisualizer sind ebenfalls vorhanden.

### Parsing
Um einen Feed von einem User in andere Formate umzuwandeln kann unter anderem [bluestream.deno.dev](https://bluestream.deno.dev/) genutzt werden, damit lässt sich beispielsweise ein [RSS Feed](https://de.wikipedia.org/wiki/RSS_(Web-Feed)) erstellen.

### Feeds finden
Die Seite [goodfeeds.co](https://goodfeeds.co/) ermöglicht es Feeds zu durchsuchen oder auch beliebte oder neue Feeds zu finden.

### Generelle Statistiken
Die Seite [twexit.nl](https://twexit.nl) zeigt einige generelle Informationen zum Bluesky Netzwerk an, bietet aber auch noch weitere nützliche Tools.

### Weiteres
Alle Techniken die bei einer normalen Recherche zum Einsatz kommen funktionieren hier natürlich auch.
Profilbilder rückwärts suchen oder verlinkte Seiten ansehen beispielsweise. 

## Entwickeln
Es gibt eine [offizielle API](https://blueskyapi.io/docs/api) und ein schönes [GitHub Repo](https://github.com/beeman/awesome-atproto) mit ATProto Ressourcen.
Beides lohnt sich um möglicherweise eigene Tools zu entwickeln und Daten noch besser analysieren zu können.