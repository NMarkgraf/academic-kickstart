---
title: GitHub Webhook eingebaut!
author: Norman Markgraf
date: '2017-12-18'
slug: github-webhook-eingebaut
categories:
  - Information
tags:
  - Technisches
  - GitHub
  - GitHub Webhook
header:
  caption: ''
  image: ''
---

GitHub bietet die Möglichkeit an, bei Interaktion mit dem Server automatisch einen Webhook zu aktivieren. Dahinter versteckt sich ein Aufruf einer URL mit einem sogenannten POST-Request. Wertet man diesen aus, so kann man z.B. nach jedem *push* automatisch ein *fetch* auf dem Webserver starten. 

Ich nutze das gerade um meinen Blog immer dann zu aktualisieren, wenn ich auf dem GitHub eine Änderung vorgenommen habe.

Damit sollte ich nie wieder vergessen alles auch auf dem Server zu aktualisieren!

Wir warten ab. ;-)

Okay, alle Verzeichnisse sollten den richtigen Besitzer haben ;-)

**NACHTRAG:** (vom 01.01.2018)

Leider schaffe ich es nicht auf PHP heraus auch nur ein Skript auszuführen. Daher wird z.Z. alles via `crontab` ausgeführt. Nicht optimal, aber es läuft erstmal.