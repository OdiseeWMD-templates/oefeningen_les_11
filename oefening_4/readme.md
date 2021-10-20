# oefening
In deze oefeningen werk je rond een fantasie-klas.

## Deel 1

* Maak in het script een array aan die je __klas__ noemt.
* Maak een array die je __lettergrepen__ noemt en die je vult met 26 zelf te verzinnen strings die 2 tot 3 letters bevatten.
  * Als de string 3 letters lang is, doe je dat in het volgende formaat, waarbij 'k' een klinker is en 'm' een medeklinker
    * kmK
    * mkm
  * Als de string 2 letters lang is, is 1 letter een klinker en 1 een medeklinker
* Voeg 22 objecten toe aan __klas__
  * Ieder object heeft de eigenschappen __nummer__ en __naam__
  * __nummer__ heeft de vorm __NR-xx__ waarbij xx de volgorde nummer is (begin bij 1)
  * __naam__ stel je willekeurig samen op basis van lettergrepen
    * 2 lettergrepen voor de voornaam + een spatie + 3 lettergrepen voor de familienaam
* Als je alle studenten hebt gegenereerd, toon je de __klas__ in de console 
* Los alle opmerkingen die ESLint geeft op, valideer je HTML en commit naar Github

## Deel 2
Je bouwt verder op deel 1
* Maak een functie __maakKlas__ die een parameter __aantal__ heeft
  * maak een nieuw klas object aan.
  * genereer __aantal__ studenten met de logica van de vorige oefening
  * de functie returnt op het einde het nieuwe klas object
* Maak een variabele __klasAvond__ aan, met 10 studenten
* Maak een variabele __klasDag__ aan, met 20 studenten
* Toon zowel __klasAvond__ als __klasDag__ met de standaard console logger
* Los alle opmerkingen die ESLint geeft op, valideer je HTML en commit naar Github

## Deel 3
Je bouwt verder op deel 2 
* Pas de functie __maakKlas__ aan zodat je een extra parameter __moment__ toevoegt. De functie zal nu aan iedere student naast nummer en naam ook __moment__ toevoegen.
  * Pas de oproepen maakKlas() aan zodat je voor de klasAvond de parameter 'avond' meegeeft en voor klasDag 'dag'
* Maak een functie __toonStudent__ die je een parameter __nummer__ en __klas__ geeft
  * __toonStudent__ toont in de console de gegevens van de student met het gegeven __nummer__ in de gegeven __klas__
* Maak een functie __kiesStudent__ waaraan je een parameter __klas__ toewijst. Deze functie geeft een willekeurige nummer terug, gebaseerd op de lengte van de __klas__ die je aan __kiesStudent__ meegeeft.
* Maak een functie __toonWillekeurigeStudent__ waaraan je als parameter een __klas__ meegeeft.
  *  __toonWillekeurigeStudent__ zal toonstudent aanroepen met het resultaat van de functie kiesStudent
* Roep 10 keer de functie __toonWillekeurigeStudent__ aan op beide klassen die je aanmaakte (klasAvond
en klasDag)
Los alle opmerkingen die ESLint geeft op, valideer je HTML en commit naar Github