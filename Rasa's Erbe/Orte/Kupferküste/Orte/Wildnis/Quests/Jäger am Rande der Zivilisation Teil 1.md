# Hintergrund

> [!cite]+ Zum Vorlesen
> Ein Kurier namens Odysseus ist mitsamt seiner Lieferung verschollen gegangen zwischen hier und [[Eladrhain]]
Euer Job ist es, ihn und das Paket wieder zu finden und sicher nach [[Westrasa]] zurück zu bringen.
> Der [[Eduardo Rasa|Bürgermeister]] 

# Hooks

Der [[Eduardo Rasa|Bürgermeister]] schickt die Spieler auf die Suche nach einer verlorenen Lieferung, die irgendwo zwischen [[Westrasa]] und [[Eladrhain]] verschollen gegangen ist.
Die Lieferung ist eine [[Malae|unbekannte Kreatur (Malae)]], die der [[Eduardo Rasa|Bürgermeister]] erforschen lassen wollte.

# Der rote Faden

[[Eduardo Rasa]] ließ sich ein [[Malae]] schicken, um es zu untersuchen, berichtete jedoch dem Kurier nicht, was seine Lieferung genau ist.
Odysseus wurde im Wald auf dem Weg zwischen [[Eladrhain]] und [[Westrasa]] von einem *Cave Bear* angegriffen, musste jedoch versuchen zu fliehen, als das [[Malae]] aus der Kiste ausbrach und den *Cave Bear* infizierte.

Die Spieler müssen keine *Checks* machen, um dem Weg durch den Wald zu folgen. Mindestens ein Spieler jedoch sollte regelmäßige *Survival Checks (**DC 14**)* machen, um die Stelle zu erkennen, wo der Kurier vom Weg abgekommen (angegriffen) worden ist.

Die Spieler treffen unterwegs auf [[Rodrig Redewend]].
![[Rodrig Redewend]]

Wurde erfolgreich die gesuchte Stelle gefunden, ist es auch nicht schwer, den Kampfspuren zu folgen; etwas weg vom Weg hinein in den Wald, wo die Spieler dann den [[Malae]]-infizierten *Cave Bear* und den Kurier finden.

- Was der Kurier über [[Malae]] weiß:
	- Malae sind Kreaturen aus dem Void. Sie passen sich jeden Moment mehr an ihren Gegner an. Wenn sie etwas lebendiges berühren, wird dieses etwas zum Wirt und der Mala zum Parasit.
	- Infizierte Kreaturen greifen unnachgiebig alles an was sie wahrnehmen und haben alle natürlichen Fähigkeiten des originalen Wirtes und je nach Ursprung auch die übernatürlichen Fähigkeiten. Sobald ein Malae Wirt eine andere Kreatur berührt, wird diese auch Wirt eines Malae.
	- Malae können nicht durch normalen Schaden sterben, sondern nur durch folgende Mittel:
		- schneller Wechsel ihres Aggregatzustandes (verbrennen, einfrieren, etc...)
		- Tod ihres Wirtes

> [!info]- Statblocks
> ```statblock
> creature: Cave Bear
> extends: Malae-infested
> name: Malae-infested Cave Bear
> cr: 3
> ```
> ```statblock
> creature: Malae
> ```

> [!info]- Encounter
> ```encounter
> name: Encounter
> players:
>   - Toovir
>   - Zoey
>   - Dandelion
>   - Owen
>   - Frey
> creatures:
>   - "1": Malae
> ```


Sollte der *Cave Bear* besiegt werden, ohne zu sterben oder sollte der Mala extrahiert werden (dadurch dass der Bär ohnmächtig wird), hat man die Wahl den Mala wieder einzufangen oder ihn entgültig zu töten.
Sollte der Mala getötet werden, hinterlässt er eine [[Void Extrakt (Vial)|ölige, schattenartige Substanz]], welche man ohne Konsequenz in einem Fläschchen o.ä. aufsammeln kann.

# Das Ende

Die Quest endet damit, dass man dem [[Eduardo Rasa|Bürgermeister]] Bericht erstattet.
- Hat man ihm erfolgreich das [[Malae]] zurückgebracht, ist der Bürgermeister glücklich und stattet die Spieler etwas für die nächste Quest aus:
	- ``dice: 1d4`` [[Potion of Healing]]
	- **1** [[Potion of Water Breathing]] pro Person
	- **120 gp** pro Person
- Ist das [[Malae]] gestorben oder entkommen, ist der Bürgermeister verärgert und stattet die Spieler nicht für die nächste Quest aus.
	- **70 gp** pro Person

## Nächste Quest

[[Jäger am Rande der Zivilisation Teil 2]]
