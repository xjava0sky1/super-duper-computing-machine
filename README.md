# Osobní web (HTML + CSS)

Jednoduchá osobní stránka v češtině s moderním tmavým designem.

## Struktura repozitáře

- `index.html` – hlavní stránka
- `assets/css/styles.css` – styly stránky
- `.github/pull_request_template.md` – PR checklist pro web změny
- `.github/workflows/web-quality.yml` – CI kontrola HTML/CSS kvality na PR

## Lokální spuštění

```bash
python3 -m http.server 4173
```

Otevři: <http://127.0.0.1:4173>

## Lokální validace/lint

```bash
npm install
npm run lint
```
