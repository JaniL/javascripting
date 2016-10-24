Taulukon alkioihin pääsee käsiksi niiden indeksiluvuilla.

Indeksiluvut alkaa nollasta ja päättyy taulukon kokoon miinus yksi.

Tässä esimerkki:


```js
var lemmikit = ['kissa', 'koira', 'rotta'];

console.log(lemmikit[0]);
```

Yllä oleva koodi tulostaa `lemmikit`-taulukon ensimmäisen alkion - merkkijonon `kissa`.

Taulukon yksittäisiin alkioihin pääsee käsiksi ainoastaan hakasulje-notaatiolla.

Piste-notaatio ei toimi.

Validi notaatio:

```js
console.log(lemmikit[0]);
```

Epävalidi notaatio:
```
console.log(lemmikit.1);
```

## Haaste:

Luo tiedosto `taulukon-arvojen-lukeminen.js`.

Kyseisessä tiedostossa määritä taulukko `ruoka` :
```js
var ruoka = ['omena', 'pizza', 'kikherne'];
```


Käytä funktiota `console.log()` tulostaaksesi taulukon `toisen` alkion arvon terminaaliin.

Tarkista että ohjelmasi toimii oikein ajamalla tämä komento:

```bash
javascripting verify taulukon-arvojen-lukeminen.js
```
