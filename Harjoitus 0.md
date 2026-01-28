# Harjoitus 0

#### Kurssin Windows-palvelimet-ICI001AS2A-3017 ensimmäisessä harjoituksessa otettiin käyttöön Azure-labsin DevTest Labs -pilvialustan virtuaaliharjoitusympäristö, sekä luotiin ensimmäinen virtuaalikone. Lopuksi otettiin yhteys luotuun virtuaalikoneeseen käyttäen RDP-asiakasohjelmaa.


Aloitin harjoituksen kirjautumalla opiskelutunnuksillani Azuren DevTestLabs-labraympäristöön, joka on Microsoftin pilvipalvelualusta. Kirjauduttuani sisään valitsin Azuren palveluista Resource Groupin, jonka sisältä löysin opintojakson nimellä toimivan labran. Loin labran sisällä uuden virtuaalikoneen hyödyntäen valmista pohjaa, käyttäen nimeä "bgx164Partanen". Virtuaalikonetta luodessani muutin myös käyttöjärjestelmän kiintolevyn standardi HDD -> standardi SSD, mikä antaa virtuaalikoneelle oletettavasti lisää nopeutta. Tarkistin konetta luodessa myös, että verkkoasetukset vastasivat ohjeen mukaisesti opintojaksototeutusta. Valitsin seuraavaksi myös IP-osoite -> Shared ja Make this machine claimable -> No.

<br>
<br>

<img width="700" height="388" alt="Screenshot 2026-01-21 102458" src="https://github.com/user-attachments/assets/2f1756d8-3d56-4af6-8883-b2c924c582a9" />
  
 
 > Kuvassa labra, jossa luomani uusi virtuaalikone.

<br>
<br>

Koneen luomisesa meni muutama minuutti. Saatuani ilmoituksen onnistuneesta koneen luonnista otin siihen yhteyden käyttäen RDP-asiakasohjelmaa (Remote Desktop Protocol). Kirjauduttuani sisään ohjeen mukaisilla tunnuksilla, muutin virtuaalikoneen salasanan omakseni asetuksista. Lopuksi valitsin virtuaalikoneen käynnistysvalikosta "Disconnect" ja suljin virtuaalikoneen Azuren puolella, jotta se ei käytä resursseja tarpeettomasti.
