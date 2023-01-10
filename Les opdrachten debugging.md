# Opdrachten debugging

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
Uit de vorige les!
3. Maak een map `debugging`
4. Open de `debugging` folder in visual studio code

## code ophalen

1. download deze files:
![](https://github.com/progsen/jsopdrachtM2/tree/main/debugging)
2. zet deze in je debugging folder

## breakpoints zetten

1. zet een breakpoint op regel (16): `if(i % 2 == i2 % 2)`
2. herlaad (refresh) de pagina zodat de code nogmaals loopt
3. ga door de code totdat je in regel 18 ( `gfx ='#';` ) komt 
4. maak een screenshot van de waardes van i & i2
5. bewaar deze met filename `checkered.png`
6. haal je breakpoint nu weg en laat de code `doorlopen` met de resume knop


## room bekijken

1. zet een breakpoint op regel 31 ` this.room = new Room(10,10);`
2. gebruik de `step over` knop om de regel over te slaan.
3. bekijk nu `this.room` in het geheugen
4. maak een screenshot van de tiles van room. klap hiervoor de eerste regel open (tiles -> [0] ->[0])
5. bewaar deze met filename `tiles.png`

## callstack bekijken

1. zet een breakpoint op regel 47 (`console.log(rowString);`)
2. bekijk nu de callstack
3. maak een screenshot van de deze callstack. 
4. bewaar deze met filename `callstack.png`
5. ga nu in de callstack naar `runApplication` door erop te clicken
6. wat zie je nu gebeuren onder `scopes?`. wat voor geheugen/variabelen zie je nu?

7. maak een screenshot van de deze scope. 
8. bewaar deze met filename `callstack2.png`

## extra

1.  probeer nu tijdens het programma het geheugen aan te passen als je op een breakpoint staat

## klaar?

1. commit & push de screenshots naar github in de map `debugging`
