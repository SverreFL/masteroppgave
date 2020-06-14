I oppgaven bruker jeg tre python script. 
##### Deskriptivt 
Nasjonale estimat, samt estimat for kommuner og økonomiske regioner
##### Pensjonsgivende
Estimat for IGE/rangkorrelasjon med ulike avgrensinger av inntekt til far og barn. Brukes kun til å lage figur A.3 og A.4 i appendiks
##### Flytting
Gjennomfører eksperimentet i flyttedelen

For hvert script er det en .txt fil med samme navn som viser eksempel på microdata-script. I praksis har jeg brukt litt ulike script ved å endre på parametre i python-scriptene. Dette gjelder spesielt i flyttedelen der jeg bruker ulike avgrensinger av utvalg og ulike mål på inntekt. 

Flyttedelen vil være komplisert å replikere. Scriptet må først brukes til å estimere rangmobilitet til permanente innbyggere og lagre dette i en tabell. Deretter må scriptet kjøres fra begynnelsen og estimatene fra tabellen brukes til å estimere forskjellen i gjennomsnittlig rangmobilitet på opprinnelse og destinasjon for barn med far i hver prosentil (delta).



