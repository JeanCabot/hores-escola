# Hores d’escola: Espanya, Europa i el món

Web informativa sobre el temps que passem a l’escola obligatòria: hores de classe a Espanya, comparació europea i mundial, separació per sexe i temps de treball dels docents.

## Com publicar-la a GitHub Pages

1. Crea un repositori nou a GitHub (per exemple, `hores-escola`).
2. Puja-hi **el contingut** d’aquesta carpeta (no la carpeta mateixa): `index.html`, `img/`, `dades/`, `.nojekyll` i aquest `README.md`.
3. Ves a **Settings → Pages**. A *Source*, tria **Deploy from a branch**, la branca `main` i la carpeta `/ (root)`. Desa.
4. En un o dos minuts, la web serà a `https://<el-teu-usuari>.github.io/hores-escola/`.

## Què funciona i què no fora de Claude

Funciona tot (gràfics, calculadora, preguntes d’«endevina», pestanyes, etiquetes) **excepte els resultats compartits de la classe**. Aquests depenien de la base de dades de Claude i a GitHub Pages simplement no apareixen: cada alumne veu la seva pròpia resposta comparada amb la real.

Per tenir resultats de classe fora de Claude caldria connectar la pàgina a un servei extern (per exemple, un formulari o una base de dades com Supabase o Firebase).

## Carpeta `dades/`

Fitxers CSV amb les dades de la web, preparats per importar a la base de dades del projecte. La columna `tipus_dada` distingeix les xifres oficials de les calculades o declarades.

## Imatges

- `img/escola-del-bosc-1914.jpg`: Escola del Bosc de Montjuïc, Barcelona, cap al 1914. Autor desconegut. Domini públic (Wikimedia Commons, `File:Escola-Bosc.jpg`).
- `img/rosa-sensat-1912.jpg`: Rosa Sensat i Vilà, *La Il·lustració Catalana*, núm. 464, 1912. Domini públic (Wikimedia Commons, `File:Rosa_Sensat_i_Vilà.jpg`).
- `img/terra-apollo17-1972.jpg`: *The Blue Marble*, NASA, Apol·lo 17, 1972. Domini públic.
- El dibuix de la façana amb portes separades és original i està inclòs dins `index.html`.

## Fonts

Totes les fonts de les dades estan enllaçades a l’apartat «Fonts» de la mateixa web. Dades consultades l’octubre de 2026.
