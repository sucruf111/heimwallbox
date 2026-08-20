# heimwallbox

Statische Website für [heimwallbox.de](https://heimwallbox.de). HTML und CSS, ohne Framework.

Die öffentlichen Dateien liegen in `public/`. Später bei Cloudflare Pages als Stammverzeichnis `public` ausliefern.

## Seiten

- `/` — 11 kW oder 22 kW
- `/installation` — Anmeldung und Elektriker
- `/mieter` — Mieter und WEG
- `/impressum` — Impressum
- `/datenschutz` — Datenschutz

## Lokal ansehen

```bash
python3 -m http.server 8080 --directory public
```

Dann <http://127.0.0.1:8080/> öffnen.
