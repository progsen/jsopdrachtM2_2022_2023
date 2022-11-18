# Opdrachten modules

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
Uit de vorige les!
3. Maak een map `modules`
4. Open de `modules` folder in visual studio code


## files opzetten

1. Kopieer files van het `canvashuis` naar 
 `modules`

 * `index.html`
 * `app.js`

2. open de directory `modules` in visual studio code

## javascript 


we gaan nu ons `huis render code` de `boom render code` naar `aparte` files verhuizen

1. open app.js
2. controlleer of je `functions` hebt gemaakt voor `tekenHuis` en `tekenBoom`. Zo nee? moet je die maken (zie de les opdrachten van `functions`)
3. maak met visual studio code 2 nieuwe files aan:

* HuisRenderer.js, maak hierin een nieuwe class HuisRenderer
* BoomRenderer.js, maak hierin een nieuwe class BoomRenderer

4. verhuis nu de `tekenHuis` en `tekenBoom` naar de renderers.

5. nu werkt je app niet meer. Want we moeten importeren:
* import {WAT} from "./WELKEFILE.js"
6. importeer beide render classes
7. gebruik nu je render classes waar je `tekenHuis` en `tekenBoom` gebruikt

TIP! vergeet niet een `variable` te maken en de `new App()` constructie te gebruiken bv
`let huisRenderer = new HuisRenderer();`

## Extra:

heb je nog meer dingen in je kerst dorp gezet? Bv een slee, kerstman of een sneeuwpop
maak daar ook renderers voor!

## klaar?

1. commit & push je werk naar github
