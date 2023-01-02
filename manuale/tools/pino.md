---
title: 🌲 Pino
description: Cos’è, a cosa serve e come si usa il database che costituisce la spina dorsale di Scambi
---
Pino è il database che contiente tutti i dati riguardanti _qualunque cosa_ di Scambi.

## Come

Pino è gestito tramite un software specifico, chiamato [_Baserow_](baserow.md). Tutto ciò che serve sapere sul suo funzionamento è spiegato [qui](baserow.md).

## Cosa

Pino raccoglie prevalentemente dati sulle persone e gli enti che partecipano a Scambi.

In Pino esistono diverse **tabelle**, ciascuna con un ruolo specifico.

* in [_Relazioni_](https://baserow.io/database/22288/table/58822) sono raccolte <mark>tutte le interazioni</mark> che Scambi ha (o vuole avere) con persone o enti esterni.
	* ogni genere di relazione, anche se non andata a buon fine, va assolutamente inserita.
	* se una relazione si ripete per più di un’edizione, il campo **`stato`** si riferisce automaticamente all’**ultima edizione**.
* in _Programma `anno_edizione`_ (e.g. [_Programma 2022_](https://baserow.io/database/22288/table/58806)) sono raccolte tutte le attività **confermate** per una determinata edizione.
	* Che il nome non confonda: in Programma non devono essere presenti solo cose che fisicamente avverranno, ma **ogni sorta di collaborazione** relativa all’edizione in questione.
* in _Programma `anno_edizione`_ (e.g. [_Persone 2022_](https://baserow.io/database/22288/table/61708)) sono raccolte tutte le persone che, in qualunque ruolo, partecipano ad un’edizione. Questa tabella serve prevalentemente alle [Civette](../staff/teams/#civette) e alle [Tartarughe](../staff/teams/#civette), per comprendere tempistiche, disponibilità, vitto e alloggio.
