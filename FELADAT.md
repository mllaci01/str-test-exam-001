# Gyakorló feladatok

## JS-task/task01-algorithm
### Tesztek
- Értelmezze a __test__ mappában található teszteket.
- A munkáját manuálisan is tesztelheti, ha indít egy live-server -t 
az index.html fájlra.
- Az automata tesztet az `npm test` paranccsal indíthatja.

### Kezdő lépések
- Klónozza ezt a repository -t a saját gépére.
- A VSCode gyökere a JS-task mappa legyen.
- Telepítse a függőségeket.

### 1. Feladat
- A main.js fájlban talál egy függvényt cityFilter néven.
- A következőképpen kell működnie a függvénynek:
- három paramétert vár: városok listája, populáció, terület
- azoknak a városoknak a nevét (CSAK A NEVÉT) kell visszaadnia egy tömbben, 
amelyek populációja kisebb a megadottnál, de területe nagyobb a megadottnál.

### 2. Feladat
- A main.js fájlban talál egy függvényt citySorter néven.
- A következőképpen kell működnie a függvénynek:
- kettő paramétert vár: városok listája, rendezés kulcsa
- a teljes kapott listát vissza kell adnia, a kulcs (key) 
szerint rendezve növekvő sorrendben.

### 3. Feladat
- A main.js fájlban talál egy függvényt citySlicer néven.
- A következőképpen kell működnie a függvénynek:
- kettő paramétert vár: városok listája, darabszám (limit)
- először a kapott listát rendezi név szerint a citySorter meghívásával,
- majd annyi elemet ad vissza a rendezett listából, amennyit a második 
paraméterben meghatároztak.

--------------------------
### 4. Feladat
- Hozzon létre egy Angular alkalmazást tetszőleges helyen (nem kötött a név).
- Legyen benne három réteg: class -> service -> component.
- Az élő json szerverről jelenítse meg a termékeket.
- A szerver elérhetősége: `https://nettuts.hu/jms/<githubname>/products` 
(a <githubname> helyére kerüljön az ön github user -neve)
- Értelmezze a szerveren elérhető termékeket és azok alapján hozza létre a 
szükséges osztályokat.
- Készítsen egy teljes értékű CRUD -ot (getAll, get, create, update, delete) 
egy megfelelő service -ben.
- Az adatokat táblázatos formában jelenítse meg a főoldalon.
- Legyen egy űrlap, ahol fel lehet venni új entitást (most Product).
- Minden sorhoz tartozzon módosítás és törlés gomb.
- A módosítás egy új űrlapra navigáljon, ahol módosíthatóak a kiválasztott 
entitás adatai.
- A törlés törölje az adott sort majd frissítse a listát.
- Alkalmazzon szabványos Angular Routing -ot az oldalak váltására.

### 5. Feladat
- A kész Angular alkalmazást publikálja a saját Github oldalán. 
`https://<githubname>.github.io`
