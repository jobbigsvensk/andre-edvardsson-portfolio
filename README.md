# André Edvardsson – Portfolio

En enkel, responsiv portfoliosida med fokus på tillgänglighet, tydlig struktur och modern HTML/CSS. Innehåller sektionerna: Om mig, CV/erfarenheter och Varför jag vill plugga cybersäkerhet.

## Struktur
- `index.html`: huvudfil med markup och grundläggande stil (inline CSS i `<style>`).
- `assets/profilbild.jpg`: profilbild som används på sidan.
- `assets/style.css`: separat CSS-fil om du vill bryta ut/styla vidare (lägg till `<link>` i `index.html` om du vill använda den).

## Kom igång
- Öppna `index.html` direkt i webbläsaren, eller kör en enkel utvecklingsserver för korrekta ankarlänkar och cache:
  - Python: `python -m http.server 8000` och gå till `http://localhost:8000`
  - VS Code: installera tillägget “Live Server” och välj “Open with Live Server” på `index.html`

## Utveckling och anpassning
- Ändra texter och innehåll direkt i `index.html` under respektive sektion.
- Byt ut `assets/profilbild.jpg` mot din egen bild. Uppdatera ev. `width`/`height`-attribut om dimensionerna skiljer sig mycket.
- Vill du använda extern CSS, lägg till i `<head>`:
  ```html
  <link rel="stylesheet" href="assets/style.css">
  ```

## Tillgänglighet
- Skip‑länk, tydliga fokusmarkeringar och semantiska element används för bättre WCAG‑stöd.
- Bilder har `alt`‑texter. Testa gärna med tangentbordsnavigering och hög kontrast.

## Publicera (GitHub Pages)
1. Skapa ett GitHub‑repo och koppla det som `origin`.
2. Push:a upp koden till `main`.
3. På GitHub: `Settings` → `Pages` → `Source`: “Deploy from a branch”, Branch: `main` (rotmapp).
4. Vänta någon minut tills sidan är publicerad på den URL GitHub visar.

## Git (snabbstart)
```
# initiera repo (om inte redan gjort)
git init
git branch -M main

# lägg till och committa
git add .
git commit -m "Initial portfolio + cybersäkerhet"

# lägg till remote (byt URL till ditt repo)
git remote add origin https://github.com/<användarnamn>/<repo>.git

git push -u origin main
```

## Licens
Ingen licens angiven. Lägg till en licens om du planerar att dela koden offentligt.
