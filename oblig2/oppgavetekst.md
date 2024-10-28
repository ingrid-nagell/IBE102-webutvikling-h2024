# Oppgave 5.

## Regne med to tall fra input-element

Hent "sum-to-tall.html" fra Filer. Når du kjører denne vises en linje med to inputfelt, en knapp som viser "a+b" og en resultattekst som viser at resultatet av addisjonen er 3, hvis de to inputfeltene var for eksempel 2 og 1.

I koden ser du en funksjon adder() som finner ut hva brukeren har skrevet inn og adderer disse, før resultatet legges inn i resultatfeltet.

Legg merke til relasjon mellom de to inputfeltene og koden.

sumtotall2.JPG

Ta en kopi til "beregn-to-tall.html".  Legg til 4 knapper for divisjon, subtraksjon, multiplikasjon og potensiering.  Resultatet skal bli omtrent slik, der brukeren har skrevet inn 3 og 1.5, og trykket på potensieringsknappen. Tredje linje viser resultatet av utregningen, altså 5.196152422706632.

beregntotall.JPG

I bildet ser vi de to inputfeltene øverst. På linjen under ligger fem knapper med ledetekst a+b, a-b, a*b, a/b og a opphøyd i b (hint: sup-element).  Resultatet kommer som før, i tredje linje.  Du må legge til fire funksjoner som er omtrent identisk i innhold, men må ha ulike navn.  Kall de for eksempel subtraher, divider, multipliser og potensier.

Valgfritt (indiker i koden hvilke av punkt A-E som eventuelt besvares):

A) Legg til to knapper for heltallsdivisjon med ledetekst a//b og a%b (ikke vist i bildet over).

B) Legg rosa bakgrunnsfarge på et inputfelt hvis det  inneholder ulovlige tegn (isNaN). Husk å sett tilbake til normal farge (hvit) så snart feltet igjen er ok. For å sjekke hver gang noe tastes i et element, kan en lytte på hendelsen (eventet) "inputLenker til en ekstern side.".

C) Endre de to inputelementene til type "numberLenker til en ekstern side." slik at de ikke godtar ikke-numerisk input.

D) Endre bakgrunnsfargen i trykket knapp slik at brukeren ser hvilken som ble sist trykket. Husk å sette den tilbake til opprinnelig farge når en annen knapp trykkes.

E) Legg til knapp "Bytt" som gjør at verdiene for a og b bytter plass
