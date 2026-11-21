# Portfolio — Valentina Russo

Sito web portfolio personale dedicato a marketing, comunicazione, strategia digitale e design, con presentazione del profilo, progetti svolti e modulo di contatto.

## Link al sito pubblicato

- **Sito live:** [https://ValentinaRusso02.github.io/](https://ValentinaRusso02.github.io/)

## Tecnologie utilizzate

- **HTML5**
- **Bootstrap 5**
- **Sass (SCSS)** (architettura modulare con `@use`, variabili, mixin e partial in `assets/scss/`)
- **EmailJS** (invio messaggi dal modulo contatti)
- **GitHub Pages** (hosting e pubblicazione)

## Compilazione del Sass

I file sorgente si trovano in `assets/scss/` (`style.scss` come punto di ingresso e i partial `_variables.scss`, `_mixins.scss`, `_base.scss` e `_components.scss`), mentre il foglio di stile compilato viene salvato in `assets/css/style.css`.

### Con estensione Live Sass Compiler (VS Code)

1. Apri il progetto in Visual Studio Code.
2. Apri `assets/scss/style.scss` e avvia **Watch Sass** dalla barra in basso (oppure salva il file se la compilazione automatica è attiva).
3. Verifica che `assets/css/style.css` risulti aggiornato.

### Da terminale (con Sass CLI)

```bash
sass assets/scss/style.scss assets/css/style.css --watch
```
