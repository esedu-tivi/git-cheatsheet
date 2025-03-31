# Uuden repositoryn luominen Githubissa

Tässä osiossa tavoitteena on oppia, miten luodaan uusi Git-repositorio Githubissa. Repositorion luominen Githubissa antaa mahdollisuuden jakaa koodia ja tehdä yhteistyötä muiden kehittäjien kanssa. Tämä on tärkeä osa projektin hallintaa ja kehitystä.

## Repositorion luominen Github-sivustolla

Github tarjoaa mahdollisuuden luoda uusia Git-repositorioita suoraan verkkosivustolla. Tämä on helppo tapa aloittaa uusi projekti ja jakaa koodia muiden kanssa. Repositorion luominen tapahtuu seuraavasti:

1. Mene Githubiin ja kirjaudu sisään tilillesi.
2. Valitse sivun oikeasta yläkulmasta `+` -painike ja valitse `New repository`.
3. Anna uudelle repositoriolle nimi ja kuvaus.
4. Valitse repositorion näkyvyys: public tai private.
5. Valitse repositorion alustus: README, .gitignore ja lisenssi.
6. Paina `Create repository` luodaksesi uuden repositorion.

Tämän jälkeen voit kloonata uuden repositorion paikallisesti ja alkaa työskennellä sen parissa. Voit lisätä uusia tiedostoja, tehdä muutoksia ja tallentaa ne Githubiin.

## Paikallisen repositorion linkittäminen Github-repositorioon

Kun olet luonut uuden repositorion Githubissa, voit linkittää sen paikalliseen repositorioon. Tämä antaa mahdollisuuden synkronoida muutokset paikallisen ja etävaraston välillä. Linkittäminen tapahtuu seuraavasti:

1. Kopioi Github-repositorion URL.
2. Siirry paikalliseen repositorioon komentorivillä.
3. Lisää Github-repositorion URL etävarastoksi komennolla `git remote add origin <URL>`.
4. Tarkista linkitys komennolla `git remote -v`.

```bash
git remote add origin <URL> # Lisää Github-repositorion etävarastoksi
git remote -v # Tarkista linkitys
```

Tämän jälkeen voit synkronoida muutokset paikallisen ja etävaraston välillä käyttämällä `git push` ja `git pull` -komentoja. Voit lähettää muutokset Githubiin `git push` -komennolla ja päivittää paikallisen repositorion Githubista `git pull` -komennolla.
