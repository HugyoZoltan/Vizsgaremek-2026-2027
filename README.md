 Személyes Pénzügyi Asszisztens

Egy modern, letisztult webalkalmazás a mindennapi pénzügyek, bevételek és kiadások nyomon követésére és elemzésére. (Szakmai vizsgaremek)

 A projekt célja

A FinTrack célja, hogy segítsen a felhasználóknak a mindennapi pénzügyeik átlátható kezelésében. A szoftver lehetővé teszi a bevételek és kiadások gyors rögzítését, egyedi kategóriákba sorolását, valamint vizuális statisztikák (diagramok) segítségével elemzi a költési szokásokat.

 Főbb funkciók

 Felhasználók számára (User)

Biztonságos azonosítás: Regisztráció és JWT/Session alapú bejelentkezés.

Interaktív Vezérlőpult (Dashboard): Aktuális egyenleg, e-havi költések összesítése és legutóbbi tranzakciók áttekintése.

Tranzakciók kezelése (CRUD): Bevételek és kiadások felvitele, szerkesztése és törlése.

Kategorizálás: Tranzakciók logikus csoportosítása (pl. Élelmiszer, Rezsi, Szórakozás).

Vizuális statisztikák: Kör- és oszlopdiagramok a költési szokások elemzéséhez.

Exportálás: Pénzügyi adatok letöltése CSV/PDF formátumban.

 Adminisztrátorok számára (Admin)

Felhasználói fiókok kezelése (listázás, tiltás, törlés).

Rendszerszintű, alapértelmezett kategóriák karbantartása.

 Alkalmazott technológiák (Stack)

Ezt a részt a ténylegesen választott technológiákra kell módosítani!

Frontend: [React.js / Vue.js / HTML-CSS-JS]

Backend: [C# .NET / Node.js Express / Python Django / Java Spring]

Adatbázis: [MySQL / PostgreSQL]

Egyéb eszközök: Git, [Diagram könyvtár, pl. Chart.js]

 Adatbázis architektúra

A rendszer egy relációs adatbázisra épül, az alábbi főbb entitásokkal:

Users: Felhasználói adatok és jogosultságok (User/Admin).

Categories: Tranzakció kategóriák (Bevétel/Kiadás típusok).

Transactions: Konkrét pénzügyi mozgások (összekötve a felhasználóval és a kategóriával).

Goals (Opcionális): A felhasználók által kitűzött megtakarítási célok.

 Fejlesztési ütemterv (Roadmap)

[x] Mérföldkő 1: Tervezés (Specifikáció, Adatbázis modell, UI Wireframe).

[ ] Mérföldkő 2: Adatbázis inicializálása, Backend szerver és API végpontok fejlesztése.

[ ] Mérföldkő 3: Frontend alapok (Autentikáció, Routing, CRUD űrlapok).

[ ] Mérföldkő 4: Rendszerek integrációja, Diagramok és Export funkciók implementálása.

[ ] Mérföldkő 5: Hibakeresés (Bugfix), Végfelhasználói tesztelés és Dokumentáció elkészítése.

 Telepítés és futtatás helyi környezetben

Ezek az utasítások jelenleg vázlatosak, a projekt elkészülte után pontosítandók.

Klónozd a repozitóriumot:

git clone https://github.com/felhasznaloneved/fintrack.git


Lépj be a mappába:

cd fintrack


Adatbázis beállítása:

Importáld a database/init.sql fájlt a lokális szervereden.

Ne felejtsd el módosítani a csatlakozási adatokat a .env fájlban!

Backend indítása:

# Parancs a backend indítására, pl: npm run start / dotnet run


Frontend indítása:

# Parancs a frontend indítására, pl: npm run dev


Készítette: [Kajdel Bence] - Szakmai Vizsgaremek tervezt 2026.10.16.
