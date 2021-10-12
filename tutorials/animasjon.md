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

## Steg 3 @showhint
Trykk på de av de 25 ledlysene som skal være aktive og lyse. Trykk igjen for å fjerne lyset.

``` blocks
basic.forever(function(){
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . # . .
    `)
  })
```

## Steg 4
Legg til enda en ``||basic:vis bilde||``-blokk og legg den under den første.

``` blocks
basic.forever(function(){
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . # . .
    `)
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
  })
```

## Steg 5 @showhint
Trykk på punktene som skal lyse her også.

``` blocks
basic.forever(function(){
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . # . .
    `)
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . # . # .
    . . # . .
    `)
  })
```

## Steg 6
Dra frem flere ``||basic:vis bilde||``-blokker til du har en hel animasjon. Her formes et hjerte.

``` blocks
basic.forever(function(){
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . # . .
    `)
  basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . # . # .
    . . # . .
    `)
  basic.showLeds(`
    . . . . .
    . . . . .
    # . . . #
    . # . # .
    . . # . .
    `)
  basic.showLeds(`
    . . . . .
    # . . . #
    # . . . #
    . # . # .
    . . # . .
    `)
  basic.showLeds(`
    . # . # .
    # . . . #
    # . . . #
    . # . # .
    . . # . .
    `)
  basic.showLeds(`
    . # . # .
    # . # . #
    # . . . #
    . # . # .
    . . # . .
    `)
  })
```

## Avslutning @showdialog
**Når du har trykket på slutt:**
* Kan du legge til tall eller tekst til bildene?
* Undersøk de rosa ``||input:Inndata||``-blokkene. Kan du få noe til å skje når man trykker på ``knapp A``?

``` blocks
input.onButtonPressed(Button.A, function(){})
```
