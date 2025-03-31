# Git-repositorion luominen ja kloonaus

Tässä osiossa tavoitteena on oppia, miten luodaan uusi Git-repositorio paikallisesti sekä miten kloonataan olemassa oleva Git-repositorio Githubista.

## Repositoryn luominen

Versionhallinnan käyttäminen alkaa uuden Git-repositorion luomisella. Tämä antaa mahdollisuuden seurata kaikkia muutoksia, tallentaa eri versioita ja palata tarvittaessa aikaisempiin tiloihin. Repositorio on kuin projektille varattu kansio, johon kaikki projektin tiedostot ja muutokset tallennetaan. Se antaa mahdollisuuden seurata kaikkia muutoksia, tallentaa eri versioita ja palata tarvittaessa aikaisempiin tiloihin.

Jokainen muutos projektiin tallentuu komitteina, mikä mahdollistaa muutosten seuraamisen ja dokumentoinnin. Tämä tekee projektin kehityksestä läpinäkyvää ja hallittavaa.

Git-repositorio toimii varmuuskopiona, koska kaikki muutokset tallennetaan paikallisesti ja/tai etäpalvelimelle. Jos jokin menee pieleen, voit aina palata aikaisempiin versioihin.

Paikallisen repositorion luominen on ensimmäinen askel yhteistyön aloittamisessa muiden kehittäjien kanssa. Tämä antaa mahdollisuuden jakaa koodia ja tehdä yhteistyötä Gitin ja Githubin kautta.

Paikallisen Git-repositorion luominen tapahtuu seuraavasti:

1. Luo uusi hakemisto projektille.
2. Siirry hakemistoon.
3. Alusta uusi Git-repositorio tässä hakemistossa komennolla `git init`.

```bash
mkdir uusi_projekti # Luo uusi hakemisto projektille
cd uusi_projekti # Siirry hakemistoon
git init # Alusta uusi Git-repositorio tässä hakemistossa
```

Käytännöss komento `git init` luo uuden `.git` -hakemiston, joka sisältää kaikki versionhallinnan tarvitsemat tiedot. Tämä on paikallinen Git-repositorio, joka seuraa kaikkia muutoksia ja tallentaa ne. Tähän hakemistoon tallentuvat kaikki commitit ja muutokset.

## Repositorion kloonaaminen Githubista

GitHub on palvelu, joka tarjoaa Git-versionhallinnan pilvipalveluna. Sieltä löytyy paljon avoimen lähdekoodin projekteja, joihin voi osallistua ja tehdä yhteistyötä muiden kehittäjien kanssa. GitHub tarjoaa myös mahdollisuuden kloonata olemassa olevia projekteja paikallisesti.

Kloonaaminen tarkoittaa projektin kopioimista GitHubista paikalliseen koneeseen. Tämä antaa mahdollisuuden tehdä muutoksia ja päivityksiä paikallisesti ja synkronoida ne GitHubiin.

Kloonaaminen on helppoa ja nopeaa. Se tapahtuu seuraavasti:

1. Mene GitHubiin ja valitse haluamasi projekti.
2. Kopioi projektin URL.
3. Kloonaa projekti paikallisesti komennolla `git clone <URL>`.

```bash
git clone <URL> # Kloonaa projekti paikallisesti
```

Käytännössä komento `git clone` luo uuden hakemiston, joka sisältää kloonatun projektin tiedostot ja muutokset. Tämä on paikallinen kopio GitHub-projektista, jota voit muokata ja päivittää paikallisesti.

Kloonaaminen on hyödyllistä, kun haluat osallistua muiden projekteihin, tehdä muutoksia ja päivityksiä sekä synkronoida ne GitHubiin. Se antaa mahdollisuuden tehdä yhteistyötä muiden kehittäjien kanssa ja jakaa koodia avoimesti.

## Harjoitus

1. Luo uusi Git-repositorio paikallisesti.
2. Kloonaa olemassa oleva Git-repositorio GitHubista.
