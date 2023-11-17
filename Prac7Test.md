# DAT120 Øving 2: Kontrollstrukturer

## Læringsmål
Du skal lære å bruke kontrollstrukturer som if, for og while. Du skal lære å formulere enkle algoritmer som bruker disse kontrollstrukturene.

## Oppgaver
a) Studieteknikk-kurs: For å få godkjent denne øvingen må du har gjort quiz-ene til studieteknikk-kurset og oppnådd minst 80% score på hver av dem. Merk at du kan gjøre quiz-ene flere ganger. Dette gjelder quiz-ene «QUIZ 1 – Studieteknikker», «QUIZ 2 – Arbeidsmetoder» og «QUIZ 3 – Gruppearbeid». Gå gjennom modulen «Hvordan lærer jeg best? - kurs i studieteknikk, arbeidsmetoder og gruppearbeid» så vil de tre quiz-ene dukke naturlig opp.

b) Repetisjon: Skriv et Python-script som regner ut den potensielle energien til et objekt i jordas tyngdefelt nært jordoverflata. Formelen for potensiell energi du skal bruke er E = m*g*h hvor m er massen til objektet, g er gravitasjonsakselerasjonen og h er høyden over overflata. Bruk g=9,81 m/s2 som gravitasjonsakselerasjon. Scriptet skal lese inn masse og høyde fra brukeren.

c) Enkel if-setning: Et script «elbil_lading_startkode.py» er lagt ved øvingen. Dette scriptet leser inn et antall kilometer og rekkevidden til el-bilen og regner ut hvor mange ladinger som trengs underveis for å kjøre denne distansen med en el-bil gitt at den starter fulladet. Bruk dette scriptet som basis for å løse følgende oppgaver:
	a. Modifiser scriptet slik at det skriver ut at du ikke trenger å lade hvis distansen er mindre enn 80% av maksdistansen. Du lader på 20% for å ha litt margin.
	b. Modifiser scriptet slik at du antar at du i hver lading starter å lade fra 20% og lader til 80%. Du lader til 80% heller enn 100% siden ladingen går mye tregere de siste 20 prosentene og det er ofte køer på ladestasjonene. Anta at du starter kjøreturen fulladet.

d) Serie med if-setninger: Lag et Python-script som regner om fra et stort antall sekunder til timer, minutter og sekunder. Scriptet skal lese inn antall sekunder fra brukeren og skrive ut resultatet. Scriptet skal bare skrive ut de tallene som er nødvendige. For eksempel hvis det er for få sekunder til å bli et minutt så skal hverken timer eller minutter skrives ut. For eksempel med 243 sekunder blir det 0 timer, 4 minutter og 3 sekunder. Da skal programmet bare skrive ut minutter og sekunder.

Frivillig, mengdetrening: Utvid programmet slik at det med mange nok sekunder også regner ut og skriver ut antall dager og år.

e) Basis while-løkke: Lag et program som konverterer en serie med beløp fra en valuta til en annen. Programmet skal starte med å lese inn navnene på de to valutaene og kursen mellom dem. Så skal programmet gå i ei løkke hvor det leser inn en verdi i den ene valutaen, konvertere den til den andre valutaen og skrive dette ut. Løkka skal avslutte når brukeren skriver inn tallet 0.
	
f) For-løkke: Skriv et script som beregner verdien av følgende sum:
s=∑_(n=1)^10▒n^2 
	
g) Frivillig: Skriv ut summen fra oppgave f) for alle n fra og med 1 til og med 10.
	
h) Frivillig, mengdetrening: Fortsett på eksemplet med måneder fra tema 07 video 06 boolske operatorer (maaned.py). Hvis tallet brukeren skriver inn er en gyldig måned, skriv ut hvilken årstid måneden er i (vinter, vår, sommer eller høst).

i) Frivillig: Lag et script som bruker Turtle Graphics til å tegne ut en mangekant. Les inn antall kanter fra brukeren, som må være minst 3. Er det lavere enn 3 skal scriptet skrive ut en feilmelding og avslutte. Ellers skal det tegne ut mangekanten gjennom å for hver kant tegne ei linje og så snu en vinkel lik 360/antall sider.
	
j) Frivillig, avansert, nøstet løkke: Start med å skrive et Python script som tegner fire sirkler som oppgitt i figur 1 under. Man kan gjøre dette ved å rotere skilpadda 90 grader mellom hver sirkel. Skriv deretter et script som tegner fire sirkler på denne måten flere ganger med større og større sirkler hver gang. Roter litt, for eksempel 10 grader, mellom hver gang. Eksperimenter med mønstrene du får med å bruke ulike rotasjonsvinkler og ulike antall sirkler av ulik størrelse. Du kan for eksempel få mønsteret oppgitt i figur 2 under.

## Praktisk
Oppgaven godkjennes av faglærer eller studentassistenter på øvingsrommet. Øvingen skal leveres individuelt av hver student. Deloppgave a) gjøres på Canvas. De resterende deloppgavene godkjennes ved at studenten demonstrerer sitt program for studentassistenten samt at studenten forklarer hvordan programmet virker for studentassistenten. Det siste er viktig siden poenget er at studenten har skjønt hva vedkommende har gjort.
