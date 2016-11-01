# liukliuk.github.io

> Luca Pianella's personal website

## Come fare

### Per cambiare l'immagine in homepage

L'immagine in homepage rappresenta l'opera piu' importante, si puo' cambiare dalla
configurazione.
Editare il file [_config.yml] e nella variabile `homepageImage` mettere il path dell'immagine
scelta, a meno dell'estensione, ad esempio

```yaml
homepageImage: opere/ombre/Ombre-3-2012-matita-su-carta-50x60
```

**Importante**: assicurarsi che l'immagine scelta soddisfi i requisiti elencati nella sezione [Immagini](#immagini).

### Per generare un'anteprima da una foto

Si puo' fare in automatico con [ImageMagick]

```bash
convert Ruggine-1-2009-matita-su-carta-58x50.jpg -resize 10% Ruggine-1-2009-matita-su-carta-58x50-anteprima.jpg
```

## Immagini

Tutte le immagini sono in formato [JPEG] e devono avere l'estensione `.jpg`.

Le immagini delle opere sono nella cartella *opere*.
Quelle da non visualizzare, se non nella lista **All works**, iniziano con il carattere `_`.

Tutte le immagini devono avere un anteprima che deve avere il suffisso `-anteprima`.

[ImageMagick]: http://www.imagemagick.org/
[JPEG]: https://it.wikipedia.org/wiki/JPEG
[_config.yml]: https://github.com/liukliuk/liukliuk.github.io/blob/master/_config.yml
