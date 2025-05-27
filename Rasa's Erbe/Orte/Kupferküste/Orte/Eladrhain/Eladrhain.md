# Eladrhain

> [!cite]- Wie die Spieler die Stadt zum ersten Mal vorgestellt bekommen:
> Eladrhain glänzt als Beispiel einer wohlhabenden und kulturell diversen Hafenstadt. 
> Die unterschiedlichsten Waren kommen über Land und Meer zusammen an diesem Knotenpunkt des Handels.
> Auch ein Knotenpunkt der Völker stellt diese Stadt dar, mit weitverbreiteten Völkern wie Elfen, Zwergen und natürlich den Menschen, aber auch nicht so oft vertretene Völker wie Halblinge, Gnome, Drachenblüter und sogar Tieflinge sind hier in verschiedenen Bezirken zu finden.
> Die Bezirke der Stadt sind viele, doch vor allem sind die 4 größten bekannt, geprägt durch die 4 Mitglieder des Stadtrats, genannt **Sommerzeit, Winterzeit, Frühlingslenz und Herbstwind**.
> - Sommerzeit, mit seinen vielen Festlichkeiten und sämtlichen Annämlichkeiten, die Abenteurer wie ihr begehren könntet.
> - Herbstwind, bekannt sowohl für sämtliche Agrarerträge innerhalb der Stadt als auch für manch exotischere Waren im weiteren Königreich.
> - Winterzeit, als ein Zentrum der Bildung und der Arkanen und natürlichen Wissenschaft.
> - Frühlingslenz, ein Zirkus aus der lokalen Fauna, von Zuchtvieh zu Haustieren, und exotischen Bestien, wie Greife, Eulenbären und ab und an auch ein Wyfern.
> 
> Eladrhain wird durch einen Stadtrat und daher dessen 4 Mitglieder regiert, nämlich 
> - **Vera Prima**: Herrin des Frühlings, 
> - **Verano Éstano**: Herr des Sommers, 
> - **Akina Aurum**: Dame des Herbst und 
> - **Vin T'Arga**: Meister des Winters.
> 
> Rundum, das Juwel des Westens, wie die Stadt im Königreich genannt wird, vermag sicherlich eines jedem Traum zu erfüllen, *nicht wahr?*

## Gezeitenbogen

Einer der 3 Außenbereiche, zusammen mit [[Eladrhain#Herbstwind|Herbstwind]] und [[Eladrhain#Frühlingslenz|Frühlingslenz]].

## Sommerzeit

Größtes Innengebiet, Bezirk für alle Feste und für alles, was Abenteurer und Reisende brauchen könnten, wie z.B.:
- Schmieden
- Bibliotheken
- Gemischtwarenhandel
- Juweliere
- Arkanisten und Alchemisten
- Schneider
- Magische Tattoos
- etc... (siehe [[D&D Shop Catalog]])

## Winterzeit

Kleineres Innengebiet, Zentrum für Ausbildung und sämtlicher Wissenschaft, arkaner oder natürlicher, z.B.:
- Schule der Gewerbe
- Hochschule Winterfels
- Universität Arkania

## Das Grüne

Grünfläche und Parkbereich.
Oft ein Platz für die größeren Feste.

## Eladrin

Sitz des Rats, hier treffen sich die Führer der Stadt: [[Vera Prima]](Frühling), [[Verano Éstano]](Sommer), [[Akina Auros]](Herbst), [[Vin T'Arga]](Winter).

## Taganlage

Hafen- und Handelsbezirk, zusammen mit [[Eladrhain#Nachtanlage|Nachtanlage]].
Wurde ursprünglich nur tagsüber genutzt, doch wird diese Regel schon lange nicht mehr durchgesetzt.

## Nachtanlage

Hafen- und Handelsbezirk, zusammen mit [[Eladrhain#Taganlage|Taganlage]].
Wurde ursprünglich nur nachtsüber genutzt, doch wird diese Regel schon lange nicht mehr durchgesetzt.

## Frühlingslenz

Einer der 3 Außenbereiche, zusammen mit [[Eladrhain#Gezeitenbogen|Gezeitenbogen]] und [[Eladrhain#Herbstwind|Herbstwind]].
Alles zum Thema Fauna ist hier zu finden, z.B.:
- Reit- und Frachttiere
- Zirkus der Tiere!
- Tiere zum Zähmen
- Ankauf für den Ertrag wilder Kreaturen
Siehe [[D&D Shop Catalog]].

## Herbstwind

Einer der 3 Außenbereiche, zusammen mit [[Eladrhain#Gezeitenbogen|Gezeitenbogen]] und [[Eladrhain#Frühlingslenz|Frühlingslenz]].
Alles zum Thema Flora ist hier zu finden, z.B.:
- Felder
- Gewächshäuser

## Hafen

Aufgeteilt auf [[Eladrhain#Taganlage|Taganlage]] und [[Eladrhain#Nachtanlage|Nachtanlage]]; beinhaltet Hafenstege, einige Kneipen und Vorratslager.

# Map

```leaflet  
id: westrasa_city  
### Lock pins so they can't be moved  
lock: false  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false
image: eladrhain.png  
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [572.544, 826.896]]  
height: 90%  
width: 100%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 429.54  
long: 303.80  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: 1  
### Max zoom is 18.  
maxZoom: 4  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: 1  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: Meter  
scale: 125  
darkMode: false

```
https://watabou.github.io/city-generator?size=47&seed=406360092&name=Eladrhain&greens=1&citadel=1&urban_castle=1&plaza=1&temple=1&walls=1&shantytown=1&coast=1&river=0&gates=3&sea=0.7

