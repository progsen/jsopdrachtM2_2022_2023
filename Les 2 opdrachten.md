# Les 1 opdrachten

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`”`
Uit de vorige les!
3. Maak een map `canvashuis`”`
4. Open de `canvashuis`”` folder in visual studio code


## files opzetten

1. Kopieer files van de vorige les naar 
 `canvashuis`

 * `index.html`
 * `app.js`

2. open de directory `canvashuis` in visual studio code

## html aanpassen
1. open index.html
2. zet een canvas tag in je body:

![appjs.PNG](img/l2/canvastag.PNG)

## javascript 

1. open app.js
2. maak een `variable` met de naam `canvas` (tip: `let eenVariableNaam = ...;`)

3. op de `...` gaan we nu met `document` aan de slag.
4. gebruik de `document.getElementById("...")` om het canvas uit de html te selecteren

5. kijk goed naar welke `id` je op de `...` moet invullen!

6. `console.log(canvas)` en kijk wat je ziet in de developer tools


##  canvas gebruiken:

Om te kunnen tekenen moeten we eerst een teken object vragen
dat doen we door `let g = canvas.getContext("2d");` in onze code te zetten

1. zet onder je `let canvas` de code van `getContext`
2. nu kunnen we tekenen: `g.fillRect(0,0,10,10);`
3. controlleer of je nu een zwart vierkant op je webpagina hebt


## paden tekenen:

plaatjes van `sjo`

![](img/l2/pathline.PNG)
1. maak deze code na en kijk of je een lijn krijgt:


![](img/l2/linecode.PNG)


### handige canvas links
* voor als je vast zit
* als je wil weten HOE je iets moet doen

[canvas javascript reference](https://www.w3schools.com/jsref/dom_obj_canvas.asp)
[canvas tag reference](https://www.w3schools.com/tags/tag_canvas.asp)
[canvas](https://www.w3schools.com/html/html5_canvas.asp)
[canvas intro](https://www.w3schools.com/graphics/canvas_intro.asp)