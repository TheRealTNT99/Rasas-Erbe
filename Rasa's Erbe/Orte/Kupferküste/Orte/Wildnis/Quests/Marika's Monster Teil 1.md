# Hintergrund



# Hooks

- [[Marika]] hat von einer "Mystischen Stelle" gehört, welche sich irgendwo im Südwesten von [[Westrasa]] finden lassen soll.
- Der [[Eduardo Rasa|Bürgermeister]] schickt die Spieler zu [[Marika]].

# Der rote Faden

> [!cite]+ Zum Vorlesen
>  *Ich suche schon seit **langem** nach einem Golemstein, welcher als Kontrolleinheit eines jedem Golem fungiert.*
>  *Ich habe von einer alten **Mystischen Seite** gehört in der Nähe gehört, wo man in vergangenen Tagen Golems erschaffen hatte.*
>  *Wenn ihr mir so einen Golemstein bringen könntet, wäre ich euch zutiefst dankbar.*
>  *Natürlich würde ich euch auch reichlich belohnen!*
> [[Marika]]

## Der Weg zur Mystischen Seite

Der Weg bis zur Mystischen Seite dauert 5 Tage zu Fuß, 3 mit Kamelen.
Am 4. Tag (2. mit Kamelen) kommt der Gruppe [[Rodrig Redewend]], jetzt aber mit Kamelen anstelle seines Esel und Karren, entgegen.
> [!info]- Hinweise zu Interaktion mit ihm:
> ![[Rodrig Redewend#Notizen]]

## Die Mystische Seite... oder was davon übrig ist

> [!info]- Szene der Mystischen Seite
> ![[Mystische Seite.jpg|900]]

Was man hier finden kann:
- einen zerstörten Golem (kaputter Golemstein)
- magischer Zirkel, welcher **anscheinend** nichts macht
- unter einem der größeren Steinbrocken führt eine Treppe nach unten
	- die Treppe runter, unter dem magischen Zirkel, befindet sich ein beinah komplett zerstörter Golem
	- von dem Golem ist nur noch ein Teil des Torsos, der Kopf, ein Arm und der Golemstein vorhanden

Ziel ist es hier, den Zirkel zu reparieren, das Ritual zu starten und den dadurch entstehenden Golem zu besiegen, um an den Golemstein in seinem Torso zu kommen.
> [!info]- Magischer Zirkel, vorher & nachher
> ![[Magischer Zirkel beschädigt.png|400]]
> ![[Magischer Zirkel.png|400]]

> [!info]- Statblocks
> ```statblock
> name: Kaputter Sandstein Golem
> extends: Sandstone Golem
> ac: 14
> hp: 102
> hit_dice: 12d10+36
> speed: 20 ft.
> stats: [14,1,16,3,11,1]
> cr: 3
> damage_resistances: slashing, piercing from nonmagical attacks
> damage_immunities: poison, psychic
> damage_vulnerabilities: bludgening from magical attacks
> traits-:
>   - name: Magic Weapons
> actions:
>   - name: Slam
>     desc: Melee Attack Roll: +4, reach 5 ft. Hit: 6 (1d8 + 2) Bludgeoning damage
>   - name: Grab
>     desc: Golem attempts to grab the target (contested Grapple). If it succeeds, it begins crushing the target, doing 5 (1d4 + 2) Bludgening damage. Target may attempt to escape at the end of its turns.
> actions-:
>   - name: Multiattack
>   - name: Slow (Recharge 5-6)
> ```

```encounter

```


# Das Ende


# ToDo / Ideen

- Mystische Stelle designen
	- Dort ein Rätsel oder einen Kampf gestalten
		- Rätsel könnte ein magischer Zirkel sein, welcher durch Verfall beschädigt ist und repariert werden muss, um das Ritual zur Golemerschaffung fertig zu stellen.
- Für den Hin- oder Rückweg ein Ereignis gestalten
	- [[Rodrig Redewend]]?

- Portal Ruine
	- Steinportal, führt zu Mond
	- Dort wurden weitere Strukturen aufgebaut (*Astral Sorcery*)
		- evtl. haben Leute überlebt, oder haben Notizen oder Gegenstände hinterlassen. (Gegenstände können Rasa's Gegenstände sein)