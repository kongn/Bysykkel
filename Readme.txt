	Oslo Bysykkel API project 

Oslo Bysykkel har et �pent API som viser plasseringer og tilstand for sine sykkelstativer. 
M�let med denna project er � utvikle en applikasjon som visa f�ljende informasjoner:
- Ulike stasjonene.
- Tilgjengelige l�ser.
- Ledige sykler.

Appliksjonen utviklas med javaScript som en front-end l�sning.
Vennligst f�lg instruksjoner nedan for � kj�re koden:

1. �ppna filen: sykkelstativ.html
	- kopiera hela inneh�llet av filen.
2. Lim in (Paste) inneh�llet i en editor exp. Atom eller brackets osv.., spara som en html fil.
   (Hovsaken er � koden sparas i en html fil)

3. F�r � denna appen skulle kunna fungera s� m� man modifiera nettlesern s� � dess sikkerhetssystem (CORS) avaktiveras,
   p� den m�ten s� klara den til � kunna kommunicera med deres API. Denna configurasjon steg er n�dvendig ettersom 
   serveren deres ikke h�ndterte "preflight request" og jeg hadde ikke tilgang p� serveren til � fikse det.
   Denna tutorials er fokusert p� Chrome nettlesern. 
   Gj�r f�ljande:
   - Skapa en ny Chrome nettlesern snarvei p� desktoppen.
   - H�yreklikk p� Chrome snarveien og �ppna egenskaper (properties).
   - Legg til kod linjen etter program adressen: --disable-web-security --user-data-dir="c:/chromedev"
     Exempel: "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="c:/chromedev"
   - Kj�r appen (koden fra html filen) i denna Chrome nettlesern.

   
