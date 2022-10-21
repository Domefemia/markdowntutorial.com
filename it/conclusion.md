---
layout: default
title: Congratulazioni!
number: 8
locale: it
---

Hai completato tutte le lezioni!

Credici o no, abbiamo _appena iniziato_ a esplorare ciò che puoi realizzare
con Markdown. Ci sono molte implementazioni "estese" di Markdown che supportano
formati come tabelle, elenchi di definizioni, note a piè di pagina, e altro. Poiché
non sono standard, non sono essenziali per l'apprendimento delle basi, come le abbiamo
introdotte qui.

Se desideri saperne di più su queste implementazioni di Markdown, puoi
esplorare qualsiasi altra app e tutorial su Markdown. Eccone solo alcune:

{% for link in site.data.resources.links %}
* <{{ link }}>
{% endfor %}
