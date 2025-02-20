# Bash-scripts
Oppgave 1: Passord-generator
Lag et bash-script som genererer et passord, med en lenge oppgitt av brukeren.
Krav:
Bruker skal oppgi lengde på passordet generert
○ En passende feilmelding burde oppgis om brukeren oppgir noe
annet enn et tall
Passordet skal være tilfeldig generert, og bestå av tall [0-9], småbokstaver
[a-z], storebokstaver [A-Z]
○ Bonus: tegn [@, $, %, etc]
Vis det genererte passordet i terminalen
Bonus funksjon:
Spør brukeren om passordet skal lagres til f
Om ja:
○ Krypter passordet med ccrypt og lagre det i et passord.txt.cpt
dokument
Om nei:
○ Skriv en passende melding som varsler brukeren at passordet ikke
er blitt lagret