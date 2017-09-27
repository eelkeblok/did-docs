Installeer Drupal op je computer
================================
Dit is de installatiehandleiding voor de Acquia Dev Desktop op een mac. Heb je 
Windows, dan kan je [hier]() terecht. De installatie verloopt in drie stappen:

1. Er moeten een webserver en databaseserver op je systeem geïnstalleerd worden.
2. De Drupal 8 bestanden moeten geïnstalleerd worden.
3. Drupal 8 moet zijn eigen database installeren.

We werken bij *Drupal in a Day* met de Acquia Dev Desktop. Deze kun je 
downloaden op de [download-pagina van het Acquia Developer 
Center](https://dev.acquia.com/downloads).

Kies voor *Mac Download* en wacht tot het bestand is gedownload. Dubbelklik het
dan om de disk image te openen.

Web server en database installeren
--------------------
Eerst gaan we de Dev Desktop op je computer installeren zodat de webserver en de 
databaseserver op je systeem komen te staan. Nadat je de disk image geopend hebt
kun je de Installer starten (dubbelklik op het blauwe icoontje genaamd 
*Acquia Dev Desktop Installer*):

![Finder-venster met de inhoud van het Acquia Dev Desktop disk 
image.](../_static/images/devenv/installation-manual/image12.png)

Het kan zijn dat je daarop een foutmelding te zien krijgt omdat het bestand
afkomstig is van een onbekende ontwikkelaar. Dit is een veiligheidsmaatregel van 
Apple.
 
![Popup die aangeeft dat de installer geblokkeerd 
is.](../_static/images/devenv/installation-manual/image8.png)

Krijg je deze foutmelding te zien, dan open je eerst *Systeemvoorkeuren* 
(*System Preferences*). Hier kies je voor *Veiligheid & Privacy* (*Security & 
Privacy*). Daar vind je je onder het tabje *Algemeen* (*General*) een tekst 
die aangeeft dat Acquia Dev Desktop geblokkeerd is. Ernaast staat een 
knop om de installer alsnog te starten. Klik op die knop.

![Veiligheid & Privacy systeemvoorkeuren met melding dat Dev Desktop is 
geblokkeerd.](../_static/images/devenv/installation-manual/image3.png)

De Installer zal nu openen.

![Openingscherm van Dev Desktop 
Installer.](../_static/images/devenv/installation-manual/image19.png)

Klik op *Next* om de installatie te starten.

![Overzicht van software die Dev Desktop zal 
installeren.](../_static/images/devenv/installation-manual/image17.png)

Je krijgt een samenvatting te zien van de software die op je computer 
geïnstalleerd gaat worden. Ga verder door op *Next* te klikken.

![Scherm met algemene voorwaarden.](../_static/images/devenv/installation-manual/image6.png)

De installer toont de algemene voorwaarden en geeft je de keuze om wel of niet 
data omtrend het gebruik van de Dev Desktop te delen met Acquia. Die keuze is 
aan jou! Als je gekozen hebt, kan je *Next* klikken om verder te gaan.

![Scherm met keuze van locaties voor programmabestanden en sites 
map.](../_static/images/devenv/installation-manual//image5.png)

Hier kan je aangeven waar dat de installer de files moet plaatsen op je 
computer. Indien gewenst (en je weet wat je doet) dan kun je die aanpassen. Kies 
daarna weer voor *Next* om 
verder te gaan.
 
![Scherm voor instellen poorten voor HTTP, HTTPS en MySQL.](../_static/images/devenv/installation-manual/image2.png)

Vervolgens wordt je gevraagd welke poorten er gebruikt mogen worden voor de 
webserver en de database. Deze staan goed ingevuld, maar als weet wat je 
doet dan mogen ze hier aangepast worden. Klik op *Next* om verder te gaan. 

![Controlescherm voor keuze poorten.](../_static/images/devenv/installation-manual/image10.png)

De Dev Desktop toont nogmaals de poorten. Als ze goed staan kan je op *Next* 
klikken om verder te gaan.

![Scherm dat aangeeft dat de installatie begonnen kan 
worden.](../_static/images/devenv/installation-manual/image11.png)

De Dev Desktop installer is nu helemaal klaar om te gaan installeren. Klik op 
*Next* om het installeren te starten.

![Voortgangsscherm tijdens installatie.](../_static/images/devenv/installation-manual/image18.png)

Pak iets te drinken terwijl je computer druk bezig is met installeren.

![Laatste scherm installatie Dev 
Desktop.](../_static/images/devenv/installation-manual/image15.png)

Het is zover! De Dev Desktop is op je computer geïnstalleerd. Klik op *Finish*
om de Dev Desktop op te starten en ga door met het tweede deel van de 
installatiehandleiding om je eigen Drupal 8 site te installeren.

Drupal-distributie kiezen
-----------------------
Nu de webserver en database op je systeem geïnstalleerd zijnis, volgen de 
stappen om een Drupal 8 website te installeren op je systeem. Als je de 
Dev Desktop nog niet opgestart had, doe dat dan nu. Je krijgt het volgende 
scherm te zien:

![Scherm voor eerste keer starten Dev 
Desktop.](../_static/images/devenv/installation-manual/image16.png)

Omdat we nog geen Drupal 8 website hebben, kiezen we hier voor de eerste optie 
om deze te installeren.

![](../_static/images/devenv/installation-manual/image7.png)

In de lijst die je vervolgens te zien krijgt, kies je *Drupal 8* en klik je op 
*install*. 

Het kan zijn de de versie bij jou anders is dan hier afgebeeld, dat is niet erg.

![](../_static/images/devenv/installation-manual/image20.png)

Geef je nieuwe Drupal website een naam. Je kan 'drupal-8-2-6' laten staan, maar 
kan hier ook je eigen site naam opgeven. (Dit mag je ook voor de database doen, 
maar let op dat je alleen gewone tekens gebruikt en geen spaties). Klik op 
*Finish* als je klaar bent om verder te gaan.

![](../_static/images/devenv/installation-manual/image14.png)

Yes! Het is gelukt! De website staat klaar voor jou om ermee aan de slag te 
gaan. Klik op het linkje bij *Local site* om aan het laatste onderdeel van de 
installatie te beginnen&hellip;

De installatie - deel 3
-----------------------
De Drupal 8 bestanden staan nu op je computer. Het laatste wat moet gebeuren is 
dat Drupal zichzelf installeert. Dat gaan we nu doen. Als je de link in de Dev 
Desktop hebt aangeklikt opent je webbrowser zich en verschijnt de Drupal 
installatie pagina.

![](../_static/images/devenv/installation-manual/image4.png)

Kies hier jouw taal en klik op *Save and Continue*.

**Belangrijk**: als je een andere taal kiest, moet je zorgen dat jouw systeem 
een actieve internet verbinden heeft zodat het de juiste vertaling kan 
downloaden.

![](../_static/images/devenv/installation-manual/image1.png)

Drupal gaat aan de slag om zichzelf te installeren&hellip;
 
![](../_static/images/devenv/installation-manual/image9.png)

De laatste stap voor je aan de slag kan. Vul hier alle gegevens voor je website 
in. In de cursus leggen we uit hoe je deze informatie later kan aanpassen.

Klik op *Finish* om af te ronden en je eigen Drupal website te zien.

![](../_static/images/devenv/installation-manual/image13.png)

Et Voila! Drupal 8 is geïnstalleerd. Je kan aan de slag. Ga naar [stap 1 van de
basiscursus]() om aan de slag te gaan!
