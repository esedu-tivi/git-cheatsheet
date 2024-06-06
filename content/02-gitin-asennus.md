    # Gitin asentaminen ja perusasetukset

## Asennus

Gitin asentaminen on helppoa, ja se on saatavilla useimmille käyttöjärjestelmille. Alla on ohjeet asennukseen eri käyttöjärjestelmille:

### Windows

1. Mene osoitteeseen [git-scm.com](https://git-scm.com/).
2. Lataa ja asenna Git.
3. Avaa Git Bash ja suorita seuraava komennot:

```bash
git --version
```

Tässä joitakin suositeltavia asetuksia, joita voit harkita:

- `main`-oletushaaran nimeksi
- Git-bashin asennus

### Mac

1. Asenna [Homebrew](https://brew.sh/), jos sitä ei ole asennettu.
2. Avaa Terminal ja suorita seuraavat komennot:

```bash
brew install git
git --version
```

### Linux

#### Ubuntu

```bash
sudo apt update
sudo apt install git
git --version
```

#### Fedora

```bash
sudo dnf install git
git --version
```

#### Debian

```bash
sudo apt-get update
sudo apt-get install git
git --version
```

## Perusasetukset

Kun Git on asennettu, sinun kannattaa määrittää perusasetukset, kuten käyttäjänimi ja sähköpostiosoite. Voit tehdä tämän suorittamalla seuraavat komennot:

```bash
git config --global user.name "Etunimi Sukunimi"
git config --global user.email "mail@mail.com"

```

Lopuksi asetusten tarkistuksen voi tehdä komennolla:

```bash
git config --list
```

## SSH-avaimen luominen

Anna terminaaliin komento:

```bash
ssh-keygen -t ed25519 -C "sahkoposti@esimerkki.com"
```

Seuraa ohjeita ja tallenna avain oletuspolkuu
