# liukliuk.github.io

> my personal website

Le immagini delle opere sono nella cartella *opere*.
Quelle da non visualizzare, se non nella lista **All works**, iniziano con il carattere `_`.

Per generare i fogli di stile, con [sass]

```bash
sass styles/main.scss # da completare
```

Tutte le immagini devono avere un anteprima che deve avere il suffisso `-anteprima`.
Per generare un' anteprima da una foto, con [ImageMagick]

```bash
convert Ruggine-1-2009-matita-su-carta-58x50.jpg -resize 10% Ruggine-1-2009-matita-su-carta-58x50-anteprima.jpg
```

[sass]: http://sass-lang.com/
[ImageMagick]: http://www.imagemagick.org/
