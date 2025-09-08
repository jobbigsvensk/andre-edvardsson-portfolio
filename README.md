# André Edvardsson – Portfolio

En enkel, responsiv portfoliosida med fokus på tillgänglighet och tydlig struktur. Innehåller sektioner för Om mig, CV och Varför jag vill plugga cybersäkerhet.

## Struktur
- `index.html` – huvudsidan med all stil (inline CSS) och innehåll
- `assets/` – bilder och övriga statiska resurser
  - `profilbild.jpg` – profilbilden

## Köra lokalt
Öppna `index.html` direkt i webbläsaren – eller kör en enkel server om du vill testa ankarlänkar/headers korrekt:

- Python: `python -m http.server 8000`
- VS Code: installera "Live Server" och välj "Open with Live Server" på `index.html`

Gå till `http://localhost:8000` om du kör Python-servern.

## Publicera till GitHub Pages
1. Skapa ett repo på GitHub och koppla det som `origin`.
2. Push:a upp koden till `main`.
3. På GitHub: Settings → Pages → Source: `Deploy from a branch`, Branch: `main` (rot).
4. Sidan blir tillgänglig på den URL som GitHub visar (kan ta någon minut).

## Git-kommandon (snabbstart)
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

## Anpassning
- Ändra texter i respektive sektion i `index.html`.
- Bilddimensioner för `profilbild.jpg` är satta till faktiska 4000×3000 för minimal layout‑shift. Byter du bild — uppdatera `width`/`height`.
- Vill du flytta sektioner, ändra ordningen i `<main>`.

## Licens
Inget specifikt licensvillkor angivet. Lägg till om du planerar att dela vidare koden offentligt.
