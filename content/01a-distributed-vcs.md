# Hajautettu versionhallintajärjestelmä

Se että versionhallintajärjestelmä on paikallinen, tarkoittaa mm.:

1. **Kopio koko historiasta paikallisesti:**

Jokainen kehittäjä, joka kloonaa Git-repositorion, saa täydellisen kopion koko projektin historiasta, ei pelkästään viimeisintä tilaa. Tämä sisältää kaikki tiedostot ja niiden muutokset sekä historiatiedot. Tämä tarkoittaa, että kaikki tiedot ovat saatavilla paikallisesti, jolloin voit tarkastella muutoksia, tehdä committeja ja nähdä projektin historian ilman, että sinun tarvitsee olla yhteydessä keskitettyyn palvelimeen.

2. **Ei keskitettyä palvelinta:**

Git ei tarvitse keskitettyä palvelinta toimiakseen. Vaikka usein käytetään palveluja kuten Github tai GitLab keskitettyinä varastoina, Git itse ei vaadi sitä. Kaikki toiminnot voidaan suorittaa paikallisesti ja synkronoida myöhemmin muiden kanssa.

Tämä tekee Gitistä erittäin joustavan ja luotettavan, koska työskentely ei pysähdy, vaikka yhteys keskitettyyn palvelimeen katkeaisi.

3. **Helppo haarautuminen ja yhdistäminen:**

Koska jokaisella kehittäjällä on täydellinen kopio projektista, haarautuminen (branching) ja yhdistäminen (merging) ovat erittäin tehokkaita ja nopeita. Haarautuminen luo uuden itsenäisen kehityslinjan, ja yhdistäminen tuo muutokset eri haaroista takaisin yhteen.

Tämä mahdollistaa tehokkaan tiimityöskentelyn, sillä eri kehittäjät voivat työskennellä eri ominaisuuksien tai bugikorjausten parissa omissa haaroissaan ja yhdistää muutokset takaisin pääprojektiin.

4. **Turvallisuus ja varmuuskopiot:**

Koska kaikki kehittäjät säilyttävät täydellisen kopion projektista, tietojen katoaminen on vähemmän todennäköistä. Jos keskitetty palvelin hajoaa, voit palauttaa tiedot mistä tahansa kehittäjän kopiosta. Tämä hajautettu rakenne tekee Gitistä luotettavan ja turvallisen työkalun versionhallintaan.

## Käytännön hyödyt

**Offline-työskentely:** Voit tehdä committeja ja katsella historiatietoja myös ilman internet-yhteyttä, koska kaikki tarvittava tieto on paikallisesti saatavilla.

**Nopea ja tehokas:** Useimmat toiminnot ovat nopeita, koska ne tapahtuvat paikallisesti ilman tarvetta kommunikoida palvelimen kanssa.

**Yhteistyö ja rinnakkaistyöskentely:** Useat kehittäjät voivat työskennellä rinnakkain eri ominaisuuksien parissa ilman, että häiritsevät toisiaan. Haarojen yhdistäminen myöhemmin on joustavaa ja tehokasta.

Git on suunniteltu moderniin ohjelmistokehitykseen, missä tiimit voivat työskennellä hajautetusti eri puolilla maailmaa ja silti ylläpitää korkeaa tehokkuutta ja turvallisuutta.
