# Branchien käyttö

Branchit eli haarat ovat hyödyllisiä, kun halutaan kokeilla uusia ominaisuuksia tai korjauksia ilman, että ne vaikuttavat muihin projektin osiin. Kun uusi ominaisuus on valmis, se voidaan yhdistää muihin branchiin. Kun esimerkiksi halutaan testata jotain uutta ominaisuutta, on turvallisinta tehdä se omassa branchissaan, jotta muut eivät vahingossa käytä keskeneräistä koodia.

Uuden branchin luominen tapahtuu komennolla:
```shell
git branch testing-feature
```

Uuden branchin olemassaolo voidaan tarkistaa komennolla:
```shell
git branch
* main
  testing-feature
```

Tähdellä merkitty branch on se, jossa ollaan tällä hetkellä. `testing`-branchiin siirtyminen tapahtuu komennolla:
```shell  
git checkout testing-feature
```

Yhdistäminen toiseen branchiin
```shell
git merge testing-feature
```
```


