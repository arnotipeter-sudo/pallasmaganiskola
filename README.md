# Pallas Magániskola Bt. – Nyelvtanfolyamok (GitHub starter)

Ez egy egyszerű kezdőcsomag a **Pallas Magániskola Bt.** nyelvtanfolyamos honlapjához,
amit könnyen feltölthetsz a GitHubra, és GitHub Pages segítségével közzétehetsz.

## Mappastruktúra

- `index.html` – a teljes, kész egyoldalas honlap
- `README.md` – ez az ismertető
- `.gitignore` – alap beállítások (pl. IDE fájlok ignorálása)
- `LICENSE` – MIT licenc (opcionális, ha nyíltan szeretnéd megosztani a kódot)

## Lépések – új GitHub repó létrehozása

1. Lépj be a GitHub-ra és hozz létre egy új repót (pl. `pallas-nyelviskola` néven).
2. A most letöltött ZIP-et csomagold ki a gépeden.
3. A kicsomagolt fájlokat másold be az új repó mappájába.
4. Nyisd meg a mappát Git-ből (pl. VS Code vagy parancssor):
   ```bash
   git init
   git add .
   git commit -m "Kezdő honlap feltöltése"
   git branch -M main
   git remote add origin git@github.com:SAJAT_FELHASZNALO/SAJAT_REPO.git
   git push -u origin main
   ```

## GitHub Pages bekapcsolása

1. A GitHub weboldalon nyisd meg a repót.
2. Menj a **Settings** fülre.
3. Oldalt válaszd a **Pages** menüpontot.
4. A **Source** résznél válaszd: `Deploy from a branch`.
5. Branch: `main`, Folder: `/ (root)`.
6. Mentsd (**Save**).
7. Pár perc múlva elérhető lesz a honlapod egy ilyen címen:
   `https://SAJAT_FELHASZNALO.github.io/SAJAT_REPO/`

Ezt a linket akár be is teheted később a névjegykártyáidra, Facebook oldalra stb.
