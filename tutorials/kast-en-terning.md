# Kaste terning

## Intro
Lag et program som viser et tilfeldig tall mellom 1 og 6.

Se på fargene i teksten i denne øvelsen, som ``||basic:blå||`` eller ``||input:rosa||``.
Disse fargene viser hvor i menyen til venstre du finner blokkene du trenger.
Så hvis du trenger en ``||basic:blå blokk||`` så finner du den i menyen når du trykker på ``Basis``.

Trykk på lyspæren til høyre for å få et hint.

## Steg 1
Det som skal skje skjer når ``micro:bit``-en ristes. Sett inn en ``||input:når ristes||``.

Alt resten skal settes inn i denne blokken.

``` blocks
input.onGesture(Gesture.Shake, function(){

})
```

## Steg 2
Sett inn ``||basic:vis tall||``.

``` blocks
input.onGesture(Gesture.Shake, function(){
  basic.showNumber(0)
  })
```

## Steg 3
Finn ``||math:velg tilfeldig 0 til 10||``. Dra den ned til ``0``.

``` blocks
input.onGesture(Gesture.Shake, function(){
  basic.showNumber(randint(0, 10))
  })
```

## Steg 4
Når du kaster en terning får du et tall mellom en og seks. Bytt ut ``0`` og ``10`` med ``1`` og ``6``.

``` blocks
input.onGesture(Gesture.Shake, function(){
  basic.showNumber(randint(1, 6))
  })
```

## Avslutning @showdialog
**Når du har trykket på slutt:**
* Kan du endre så "terningen" har flere sider, for eksempel 20?
* Hva om man kaster to terninger samtidig? Kan du lage et program for det?
