	Oslo Bysykkel API project 

Oslo Bysykkel har et åpent API som viser plasseringer og tilstand for sine sykkelstativer. 
Målet med denna project er å utvikle en applikasjon som visa føljende informasjoner:
- Ulike stasjonene.
- Tilgjengelige låser.
- Ledige sykler.

Appliksjonen utviklas med javaScript som en front-end løsning.
Vennligst følg instruksjoner nedan for å kjøre koden:

1. øppna filen: sykkelstativ.html
	- kopiera hela innehållet av filen.
2. Lim in (Paste) innehållet i en editor exp. Atom eller brackets osv.., spara som en html fil.
   (Hovedsaken er å koden sparas i en html fil).

3. Adda deres client identifier unique string på to stede i koden. Erstatte " unique string " med deres egna unique string som visas nedan.
   Husk det er to stede i koden som ska erstattes (ved linje 31 og linje 51).
   xhttp.setRequestHeader("Client-Identifier", " unique string ");

4. Før å denna appen skulle kunna fungera så må man modifiera nettlesern så å dess sikkerhetssystem (CORS) avaktiveras,
   på den måten så klara den til å kunna kommunicera med deres API. Denna configurasjon steg er nødvendig ettersom 
   serveren deres ikke håndterte "preflight request" og jeg hadde ikke tilgang på serveren til å fikse det.
   Denna tutorials er fokusert på Chrome nettlesern. 
   Gjør føljande:
   - Skapa en ny Chrome nettlesern snarvei på desktoppen.
   - Høyreklikk på Chrome snarveien og øppna egenskaper (properties).
   - Legg til kod linjen etter program adressen: --disable-web-security --user-data-dir="c:/chromedev"
     Exempel: "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="c:/chromedev"

5. Kjør appen (koden fra html filen) i denna Chrome nettlesern.

   
