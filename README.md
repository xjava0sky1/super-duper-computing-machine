# Osobní landing page (statický web)

Moderní osobní landing page v češtině postavená jen na HTML + CSS. Projekt je
vhodný pro nasazení na GitHub Pages (bez build kroku a bez backendu).

## Co stránka obsahuje

- Hero
- About
- Interests (cards)
- Projects (3 cards)
- Contact
- Footer

## Struktura repozitáře

- `index.html` – hlavní stránka
- `assets/css/styles.css` – styly stránky
- `assets/` – statické soubory (obrázky, ikony, další assety)

## Lokální spuštění

```bash
python3 -m http.server 4173
```

Pak otevři: <http://127.0.0.1:4173>

## GitHub Pages deploy

Web je čistě statický, takže je kompatibilní s GitHub Pages bez dalších úprav.

1. V GitHub repozitáři otevři **Settings → Pages**.
2. V sekci **Build and deployment** nastav **Source: Deploy from a branch**.
3. Zvol branch (typicky `main`) a root složku (`/`), protože `index.html` je v rootu.
4. Ulož nastavení; GitHub stránku nasadí automaticky.

## Lint/validace

Repo obsahuje konfiguraci pro `html-validate` a `stylelint`.

```bash
npm install
npm run lint
```
