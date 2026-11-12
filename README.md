# HangyaHolding weboldal

A HangyaHolding (Polgár) ipari csomagolási megoldásokat bemutató weboldala, V2 változat.

## Felépítés

- `index.html` – a teljes oldal egy fájlban (HTML, CSS, JavaScript)
- `assets/img/` – képek (JPG, WebP és kivágott PNG változatok)

Az oldal statikus, build lépés nincs. Az `index.html` böngészőben megnyitva azonnal működik.

## Oldalak és nyelvek

Hat oldal: Főoldal, Így dolgozunk, Termékeink, Környezetvédelem, Projektjeink, Kapcsolat.

Öt nyelv: magyar, angol, német, francia, spanyol.

Az oldalak és nyelvek között az URL `#` része vált, például `#hu-home`, `#en-products`, `#de-contact`.

## Külső függőségek

- Google Fonts (Barlow, Barlow Condensed, IBM Plex Mono)
- Az ajánlatkérő űrlap a látogató levelezőprogramját nyitja meg (`mailto:`), szerveroldali feldolgozás nincs.
