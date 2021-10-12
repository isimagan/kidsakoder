# Animasjon

## Steg 1
Når du starter et nytt program i micro:bit-appen er to blokker allerede fremme.

Vi skal bare bruke ``||basic:gjenta for alltid||``, så kast den andre ved å dra den tilbake til verktøykassa.

## Steg 2
Dra frem en ``||basic:vis bilde||``-blokk og sett den inni ``||basic:gjenta for alltid||``-blokken.

``` blocks
basic.forever(function(){
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
})
```
