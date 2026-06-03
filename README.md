# lp-recruiting-report-2026-landwirtschaft

Landingpage für den GreenCareers Recruiting-Report 2026 — **Landwirtschaft Edition**.

**Live:** https://recruiting-report-2026-landwirtschaft.green-careers.de/
(GitHub Pages + Custom Domain via IONOS CNAME → `frdlnk-gc.github.io`)

## Inhalt

| Datei | Zweck |
|---|---|
| `index.html` | Landingpage mit Quiz-Formular → Lead an Make (`MAKE_WEBHOOK_URL`) |
| `Download-Seite/index.html` | Download-Seite + Termin-Anfrage-Formular (`TERMIN_WEBHOOK_URL`) |
| `recruiting-report-2026-landwirtschaft.pdf` | 32-Seiten Report (Feldgrün/Weizen-Gold, Landwirtschaft-spezifisch) |
| `hero-images/hero-landwirtschaft-web.jpg` | Hero-Foto (Landwirtschaft-Motiv) |
| `logo-*.png` / `favicon-*.png` | GreenCareers Brand Assets |
| `CNAME` | Custom Domain für GitHub Pages |

## Farbschema
Eigene "Ernte"-Palette (klar unterscheidbar von GaLaBau=Grün, Tiefbau=Orange):
Feldgrün-Basis (`#3E4A2B`) + Weizen-Gold-Akzent (`#E0A500` / Glow `#F4C430`).

## Meta-Pixel
Geteilte GreenCareers Pixel-ID `634469765867935`.
`LANDINGPAGE_ID = 'recruiting-report-2026-landwirtschaft'`.

## Make-Webhooks (live)

| Datei | Variable | Webhook |
|---|---|---|
| `index.html` | `MAKE_WEBHOOK_URL` | `https://hook.eu1.make.com/2r2x9ghuvwvv4617aqlm2v45eptzh3ck` |
| `Download-Seite/index.html` | `TERMIN_WEBHOOK_URL` | `https://hook.eu1.make.com/lkagvx8f9nis7wyvftfd19n31illt6rt` |

**Source-Tags** zur Filterung in Make/Supabase:
- LP-Lead: `source = 'recruiting-report-2026-landwirtschaft'`
- Termin: `source = 'download-page-termin-anfrage-landwirtschaft'`

## Deployment
1. Neues GitHub-Repo `lp-recruiting-report-2026-landwirtschaft` unter `frdlnk-gc` anlegen.
2. Ordnerinhalt pushen (`main`-Branch).
3. GitHub Pages auf `main` aktivieren.
4. IONOS: CNAME `recruiting-report-2026-landwirtschaft` → `frdlnk-gc.github.io` (erledigt).
