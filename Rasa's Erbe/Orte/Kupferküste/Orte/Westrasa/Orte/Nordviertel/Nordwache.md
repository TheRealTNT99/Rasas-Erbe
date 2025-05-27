```leaflet  
id: Nordwache  
### Lock pins so they can't be moved  
lock: false  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false
image: Wache.jpg  
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [967.44, 3058.43]]  
height: 90%  
width: 100%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 1529.22  
long: 483.72  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -1.5  
### Max zoom is 18.  
maxZoom: 2  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -1  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: Meter  
scale: 1  
darkMode: false  
```

# Beschreibung

- Die Wachgarrison im Nordviertel sieht nur selten Besuch
- Wachen sind gut ausgestattet, aber meist gelangweilt
- Zellen sind fast immer leer