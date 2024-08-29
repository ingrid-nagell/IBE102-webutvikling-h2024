#Øving 1: Kom igang med en rødlisteart
Dette er en øving. Du skal ikke levere den, men må gjerne spørre om hjelp, f.eks. i diskusjonen under.

Målet er å bli kjent med lærematerialet, og bli kjent med å skrive kode på tekstfil og teste koden i en nettleser.

Hvis du er helt ukjent med koding av web, bør du først gjenskape eksemplet i Getting Started, der vi ser Firefox-logoen og diverse tekst.  Aller helst bør du få til både HTML, CSS og Javascript.  Det holder at det virker på din maskin, vi skal ikke laste disse opp til noen server eller sky.

Dernest, når du føler at du fikk dette til, bør du forsøke å lage et nytt lokalt nettsted som presenterer en rødlistet dyreart.  Med "lokalt" menes at filene ligger på din PC. Innhold og assets kan hentes fra Wikipedia, for eksempel som denne om ærfuglen: https://no.wikipedia.org/wiki/%C3%86rfuglLenker til en ekstern side.

Lag et nytt sted (mappe) som du kaller "rødlisteart" der det ligger en "index.html".  Når en åpner index.html i nettleseren får en følgende brukeropplevelse:

## struktur og innhold
* det norske navnet på arten står som hovedoverskrift med h1
* bildet av dyret står under overskriften
bildet skal ligge i undermappa "images",
hent det gjerne fra Wikimedia der alle bilder er lisensiert for fri bruk
* under bildet står et avsnitt (p) med h2-overskrift som sier "Opplysninger"
i dette avsnittet med opplysninger vises en kulepunktliste (ul) med linje for
latinsk navn
utbredelse, hvor dyret finnes
antall individer
* i neste avsnitt skal det være en h2-overskrift om "Atferd"
innholdet limes inn fra Wikipedia
* struktur lagres som "index.html" i rotmappa for nettstedet
## utseende
* alle h1 skal sentreres
* alle avsnitt (p) skal ha gul bakgrunnsfarge
* alle bilder skal ha en 10 pixel bred heltrukken ramme
* stilfila skal hete "dyrestil.css" og ligge i "styles"-mappa
## interaktivitet
* når bildet trykkes med venstre musknapp (click event) skal bildet byttes til et annet, som i eksemplet fra Mozilla
* koden skal hete "dyreprogram.js" og ligge i "scripts"-mappa.
