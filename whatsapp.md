---
title: Whatsapp
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

## Suchen und Analysieren

### Prüfen ob eine Nummer Whatsapp nutzt
Einfach die Telefonnummer als Kontakt speichern und schauen, ob es die Möglchkeit gibt der Person zu schreiben, oder ob angezeigt wird "Person zu Whatsapp einladen".

### Chats via Dorks finden
Durch [Dorks](https://en.wikipedia.org/wiki/Google_hacking) für verschiedene Suchmaschinen lassen sich Einladungen zu privaten Chatgruppen finden.
Ein Beispiel für Google wäre:

> [site:chat.whatsapp.com](https://www.google.com/search?q=++++++site%3Achat.whatsapp.com+)

Es kann sich lohnen auf allen möglichen Suchmaschinen mit Dorks nach entsprechenden Suchbegriffen im Zusammenhang mit chat.whatsapp.com zu suchen.
Im Beispiel oben entsprechend mit der Option "Suche unter Einbeziehung der übersprungenen Ergebnisse wiederholen.".

### Metadaten
Es kann auch hier wieder interessant sein, wann ein Nutzer online ist.
Das ganze konstant zu überwachen setzt etwas mehr technisches können vorraus.
Auf GitHub gibt es dazu einige Projekte und scheinbar gibt es auch einige kommerzielle Anbieter die sich dem Thema gewidmet haben.

### IP
Auch hier ist es natürlich möglich eine eigene Website zu basteln die einen IP-logger eingebaut hat (im Grunde jeder Webhoster bei dem man auf die Logfiles zugreifen kann bietet dies von Haus aus).
Wenn man jemanden den Link zusendet und dieser angeklickt wird, hat man, falls keine VPN genutzt wird die IP des Nutzers.
Dies kann sowohl für die Geoinformationen als auch für Strafverfolgung interessant sein.