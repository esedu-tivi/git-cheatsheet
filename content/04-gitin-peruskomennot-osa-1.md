# Gitin peruskomennot - Osa 1

Tässä osiossa tavoitteena on oppia, miten käyttää Gitin peruskomentoja paikallisesti. Käymme läpi yleisimmät komennot: `git add` ja `git commit`.

## git add

`git add` -komento lisää muutokset seurantaan. Se valmistelee muutokset seuraavaa commitia varten. Voit lisätä yksittäisiä tiedostoja tai kaikki muutokset kerralla.

```bash
git add tiedosto.txt # Lisää yksittäinen tiedosto seurantaan
git add . # Lisää kaikki muutokset seurantaan
git add -A # Lisää kaikki muutokset seurantaan
git add -u # Lisää muokatut ja poistetut tiedostot seurantaan
```

## git commit

`git commit` -komento tallentaa muutokset pysyvästi. Se luo uuden commitin, joka sisältää kaikki lisätyt muutokset. Voit myös lisätä viestin commitiin, joka kertoo mitä muutoksia on tehty.

```bash
git commit -m "Lisätty uusi toiminnallisuus" # Tallentaa muutokset commitiin
```

Jos unohdat lisätä viestin, Git avaa tekstieditorin, jossa voit kirjoittaa viestin. Tallenna ja sulje tiedosto tallentaaksesi commitin. Oletuseditori on yleensä Vim, mutta voit vaihtaa sen haluamaasi editoriin. Hyvä muistaa, että Vim-editorissa tarvitset pikanäppäimiä tallentaaksesi ja sulkeaksesi tiedoston. Ne ovat:

- Tallenna ja sulje: `:wq`
- Peruuta ja sulje: `:q!`

Näppäimella `insert` voit siirtyä insert-tilaan ja kirjoittaa viestin. Painamalla `ESC` pääset takaisin normaalitilaan, jolloin voit antaa tallenna- ja sulje-komennot.

Voit myös vaihtaa oletuseditorin seuraavasti:

```bash
git config --global core.editor "nano" # Vaihtaa oletuseditorin Nanoksi
```

```bash

## Harjoitus

1. Luo uusi Git-repositorio paikallisesti.
2. Lisää tiedostoja ja muutoksia seurantaan `git add` -komennolla.
3. Tallenna muutokset pysyvästi `git commit` -komennolla.

## Yhteenveto

Gitin peruskomennot ovat olennainen osa versionhallinnan käyttöä. Ne mahdollistavat muutosten seuraamisen, tallentamisen ja hallinnan. Opi käyttämään `git add` ja `git commit` -komentoja tehokkaasti paikallisesti.
