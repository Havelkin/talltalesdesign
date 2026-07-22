# Tall Tales Design — Galerie

Jednoduchá statická galerie pro projekt Tall Tales Design, nasazená přes GitHub Pages na doméně [talltalesdesign.com](https://talltalesdesign.com).

## Struktura

- `index.html` — hlavní stránka s galerií
- `assets/style.css` — styly (minimalistický design)
- `assets/script.js` — jednoduchý lightbox po kliknutí na obrázek
- `assets/img/` — obrázky galerie (aktuálně placeholdery, nahraď vlastní grafikou)
- `CNAME` — nastavení custom domény pro GitHub Pages

## Jak přidat vlastní grafiku

1. Nahraj obrázky do `assets/img/` (doporučeno JPG/WebP, šířka cca 1200–1600px kvůli rychlosti načítání).
2. V `index.html` uprav `src` u jednotlivých `<figure>` položek tak, aby ukazovaly na nové soubory, a uprav i `<figcaption>` popisky.
3. Commitni a pushni změny — GitHub Pages se automaticky přebuildí během chvíle.
