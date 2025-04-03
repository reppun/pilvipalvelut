# Viikon 2 tehtävä
### Miten Jekyll sivustoa voisi automatisoida käyttäen GitHub Actions-toimintoja?
Kun VSCodesta tekee push commit toiminnon, build ja deployment menee Actionseissa päälle. Sieltä voi seurata buildiä, sen statusta ja myös deploymenttia. Kun deploy on ok ja vihreällä, näkyy commitatut muutokset sivulla. 

Sieltä näkee hyödyllistä metriikkaa, esim.
- deploymentin statuksen (queued, in progress, success) josta voi katsoa missä tilassa, onnistuiko, mikä meni pieleen
- total durationin (tässä tehtävän commitissa esimerkissä meni 38s) joka on tärkeää tietää, kun puhutaan livenä olevista web sovelluksista ja niiden päivittämisestä.

### Millaisilla kehitystyökaluilla ja -tekniikoilla saataisiin CI/CD-putkisto rakennettua web-sovellukselle?
Yksi parhaista työkaluista tähän on Jira, jossa saadaan taskejä (kortteja) siirrettyä inboxista in progressiin ja reviewiin ja doneksi etc. Jirassa pystyy assignaamaan kortit eri henkilöille ja tiimissä kaikilla on niihin pääsy. Siellä pystyy näppärästi myös lisäämään mahdollisia blockkeja ja linkata taskeja keskenään, jolloin sekavasta himmelistä muodostuu selkeämpi kartta. Se helpottaa paljon putkea, sillä yhdellä silmäyksellä näkee jo vähän sitä, missä vaiheessa projekti menee.

[Takaisin etusivulle](index.md)