# Sandnes Tattoo Convention — v2

Denne versjonen er endret etter tilbakemeldingen:
- Hero/header-GIF er heldekkende over hele skjermen (`object-fit: cover`).
- Bruker de seks GIF-filene som ble lastet opp i samtalen, lagret lokalt i `assets/`.
- Visuell retning er mørk, filmatisk og høy-kontrast, med store displayoverskrifter.
- Støtte for fonten **SAN ANDREAS** er klargjort via `@font-face`.

## Viktig om SAN ANDREAS-fonten
Fontfilen er ikke inkludert, fordi den ikke ble lastet opp. Legg en lisensiert fontfil i `assets/fonts/SanAndreas.woff2` (opprett mappen `fonts` om nødvendig), så vil nettsiden bruke den automatisk. Uten fontfil faller overskriftene tilbake til Impact/Arial Narrow.

## Opplasting
Pakk ut ZIP-filen og last opp alle filene og `assets/`-mappen til rotmappen i GitHub-repositoriet. `index.html` må ligge i rotmappen. Commit endringene, og Vercel vil bygge/deploye prosjektet som statisk nettside.

## Nøyaktighet
Dette er en oppdatert rekonstruksjon, ikke en verifisert piksel-perfekt kopi av Squarespace-originalen. Den originale logoen lastes fortsatt fra Squarespace-CDN. Men de opplastede GIF-ene er nå inkludert lokalt i ZIP-filen.
