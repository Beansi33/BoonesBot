# De Glimlachfabriek — website

Statische website (HTML, CSS, een beetje JavaScript). Geen build-stap nodig.

## Structuur
- `index.html` — homepage
- `dagelijkse-hoop.html`, `verhalen.html`, `praktische-hulp.html`, `blog.html` — inhoud
- `vzw-gids.html` — gids om een VZW op te starten
- `contact.html`, `steun-ons.html`, `remix*.html` — contact, steun en wedstrijd
- `privacybeleid.html`, `cookiebeleid.html` — juridische pagina's
- `css/styles.css` — stijl (incl. donkere modus)
- `js/main.js` — thema-knop, menu, cookiebanner, dagelijkse tekst
- `_data/daily.json` — wordt elke dag door de workflow vernieuwd
- `scripts/rotation_generate.mjs` — genereert `daily.json`

## Openstaand
- Privacybeleid: verwerkingsverantwoordelijke, rechtsgrond en bewaartermijnen invullen.
- Formspree-ID in `remix-submit.html` invullen.
- Ontbrekende pagina's aanmaken of linken: `verhalen.html`, `praktische-hulp.html`, `cookiebeleid.html`, `manifest.json`.
