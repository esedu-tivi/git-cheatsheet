# Gitin peruskomennot - Osa 2

Tässä osiossa tavoitteena on oppia, miten seurata muutoksia Gitissä. Käymme läpi yleisimmät komennot: `git status`, `git log` ja `git diff`.

## git status

`git status` -komento näyttää muutosten tilan. Se kertoo, mitkä tiedostot ovat muuttuneet, lisätty seurantaan tai poistettu seurannasta. Voit käyttää tätä komentoa milloin tahansa tarkistaaksesi muutosten tilan.

```bash
git status # Näyttää muutosten tilan
```

## git log

`git log` -komento näyttää commitit historiassa. Se kertoo, mitä muutoksia on tehty ja kuka on tehnyt ne. Voit käyttää tätä komentoa tarkistaaksesi commitien historiatiedot.

```bash
git log # Näyttää commitit historiassa
```

## git diff

`git diff` -komento näyttää muutokset tiedostoissa. Se vertailee tiedostoja ja näyttää, mitä muutoksia on tehty. Voit käyttää tätä komentoa tarkistaaksesi muutokset ennen commitia.

```bash
git diff # Näyttää muutokset tiedostoissa
git diff tiedosto.txt # Näyttää muutokset yksittäisessä tiedostossa
```

## Harjoitus

1. Luo uusi Git-repositorio paikallisesti.
2. Lisää tiedostoja ja muutoksia seurantaan `git add` -komennolla.
3. Tarkista muutosten tila `git status` -komennolla.
4. Tarkista commitit historiassa `git log` -komennolla.
5. Tarkista muutokset tiedostoissa `git diff` -komennolla.
