---
title: 🗄️ Baserow
---

[Baserow](https://baserow.io) is the software whose interface is operated by _Pino_, Scambi’s database. If the information on this page is not enough, before bothering the Silicon team, look for an answer on the [official forum](https://community.baserow.io).

## Access

In order to visualize only the data, follow the instructions provided at this link, whereas in order to access and modify data you will need to go on [pino.scambi.org](https://pino.scambi.org), by using an account with an authorized email

## Use

Baserow is like a Google Sheets with superpowers. All formatting functionalities such as colors, fonts, and so on, do not exist. On the contrary all the functionalities related to the management, the visualization and the analysis of large amounts of data are added.

The following video summarizes the essential functionalities

<iframe title='Baserow Tutorial' src='https://peertube.uno/videos/embed/d13b53db-e063-4890-8320-70e020657f78?title=0&amp;warningTitle=0&amp;peertubeLink=0' allowfullscreen='' sandbox="allow-same-origin allow-scripts allow-popups" frameborder='0'></iframe>

## Content

Many different tables exist on _Pino_. Each one of them has a specific role. In the previous tutorial the roles of the tables and the data entry criteria and cataloguing of data are not specified in details.

* in [_Relazioni_](https://baserow.io/database/22288/table/58822) all Scambi's interactions with people or external institutions are being written.
	* each type of relationship, even if not successful, should be put into this table .
	* if a relationship is renewed for more than just one edition, the **`stato`** field would refer to the **latest edition**.
* in _Programma `year_edition`_ (ex. [_Programma 2022_](https://baserow.io/database/22288/table/58806)) all the **confermed** activities for a specific edition are collected.
	* the name should not mislead: in Programma each type of collaboration related to edition at issue should be collected, not only things taking place physically.
* in _Programma `year_edition`_ (ex. [_Persone 2022_](https://baserow.io/database/22288/table/61708)) all the people taking part in the edition in question, no matter their role, are collected.
