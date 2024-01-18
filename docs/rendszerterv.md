# Rendszerterv  

## A rendszer célja !!!TÜNDE!!!



## Projektterv !!!TÜNDE!!!
### Elvégzendő feladatok
### Felelősségi körök
### Mérföldkövek
### Ütemterv
#### Programozáshoz kötődő feladatok ütemterve
### Programozáshoz nem kötődő feladatok ütemterve



## Üzleti folyamatok modellje !!!TÜNDE!!!



## Követelmények !!!TÜNDE!!!
### Funkcionális követelmények
### Nem-funkcionális követelmények
### Törvényi előírások, szabványok



## Funkcionális terv 
### Felhasználói felület
A felhasználói felület egy weblap, amin a felhasználó bejelentkezés nélkül korlátozott tartalmat kap. Bejelentkezésnél három szerepkör közül tud választani, annak függvényében, hogy melyikhez tartozik.
A weblapok között egy navigációs menü segítségével válthatunk.

#### Nem bejelentkezett felhasználók lapja
##### Kezdő oldal
###### Funkciòk
- Bejelentkezés
- Regisztráció

A fő oldalon egy tájékoztató szöveget olvashatunk el. 
Bejelentkezés nélkül semmilyen adatot nem jelenít meg az oldal.
A navigációs menüben a bejelentkezésre kattintva tudunk bejelentkezni, vagy regisztrálni.

#### Diák felhasználó
##### Kezdő oldal
###### Funkciòk
- Közösségi szolgálati munkák megjelenítése
- gyors kereső
- részletes keresés
- kijelentkezés

![Diák kezdő oldal](img/diak-kezdo-kereso.png)
A megjelenített adatok dinamikusan, mindig az adatbázis jelenlegi állapotát tükrözik.
A gyors keresővel kulcs szavakra tudunk rákeresni.
A részletes keresővel tudunk szűrni településre, megyére vagy kategóriára.A keresés gombbal a felhasználó által választott kritériumokkal szürt eresményeket listázza ki.
A menüben lévő kijelentkezés gombbal tudunk kijelentkezni a profilunkból.

##### profil oldal
###### Funkciòk
- profil szerkesztése
- mentés
- Saját válalt munkák megtekintése
- üzenet írás/ megtekintés
- kijelentkezés

A profil oldalon egy navigációs menüben kiválaszthatjuk mit szeretnénk.
A profil szerkesztésénél megtekinthetjük azt adatainkat és szerkeszthetjük őket. A mentés gombbal elmenthetjük a változtatásokat.
A diákok megtudják tekinteni a munkákban szerzett óráik számát és ennek dokumentumát kitudják nyomtatni pdf formátumban.
A menüben lévő kijelentkezés gombbal tudunk kijelentkezni a profilunkból.

#### Szervezet felhasználó
##### Kezdő oldal
###### Funkciòk
- a szervezet által feltöltött munkák megjelenítése
- gyors kereső
- részletes keresés
- új közösségi szolgálati munka oldal megnyitása
- kijelentkezés

A gyors és a részletes keresővel tudunk szűrni a munkákra.
A menüben lévő kijelentkezés gombbal tudunk kijelentkezni a profilunkból.

##### új kösösségi szolgálat
###### Funkciòk
- mentés

Ezen az oldalon az új munka adatait lehet beírni és elmenteni.

##### Profil oldal
###### Funkciòk
- adatok szerkesztése és mentése
- jelenléti ívek szűrese
- jelenléti ív megtekintése/ szerkesztése /pdf nyomtatása
- üzenet küldés/ fogadás
- kijelentkezés

A szervezetnek van lehetősége szerkeszteni és elmenteni az adatait.
A jelenléti iveket a szervezet meghírdetett munkái szerint kitudja listázni. A diák nevére kattintva tudja a jelenléti ívet módosítani, elmenteni és kinyomtatni.
Az üzeneteknél a diákok által írt leveleket tudják megtekinteni,visszaírni.
A diákok jelentkezését a munkára a szolgáltatók levél formátumban kapják meg amit eltudna utanítani és elfogadni.

#### Iskola

##### Kezdő oldal
###### Funkciók
**hianyzik**


### Adatbázis kezelő
Az adatbázis kezelő felelős az adatbázissal való közvetlen kommunikációért.
Elvégzi a lekérést, majd továbbitja az adatokat.
Az összes adatbázis az adatbázis kezelőn keresztül érhető el.

#### Adatbázis kezelő funkciói
Az adatbázis kezelő lekérdezést az egész adatbázishoz biztosít.
![Adatbázis kezelő](img/adatbazis-kezelo.png)

### Backend
A backend feladata összekötni a weblapot, az adatbázis kezelőt.

A backend a felhasználói felületen beállítottak szerint jelzi az adatbázis kezelőnek milyen adatokra van szükség, majd a kapott adatokat megjeleníti a weblapon.


## Fizikai környezet
A fizikai környezet részei a webes front-end, ami megjeleníti az adatokat, a php backed, ami biztosítja az adatbázis elérését, az sql adatbázisok, amik az adatok tárolásáért és lekéréséért felelősek.
### Webes felület
A webes felület felelős az adatok megjelenítéséért a felhasználó számára, ezért fontos, hogy könnyen átlátható, könnyen kezelhető és bármilyen eszközről megjeleníthető legyen.
#### Felépítés
A webes felület kialakításához a Vue.js 3 JavaScript keretrendszert alkalmazzuk.

#### Reszponzivitás
A reszponzivitás megvalósításához bootstrap-et használunk, mivel a bootstrap egy elterjedt és jól bevált technológia. 

### Backend-program
Összeköti a komponenseket. A weboldal backendjét php nyelven írjuk.

### Adatbázis
SQL adatbázisok felelősek az adatok tárolásáért.

### A megvalósítandó alkalmazás
A megvalósítandó alkalmazás egy webalkalmazás. Vagyis bármilyen webböngészővel rendelkező eszközről elérhető és használható. A reszponzivitás megvalósításával eszközmérettől függően változik a megjelenítés így tovább növelve az elérhetőségét.


## Absztrakt domain modell !!!TÜNDE!!!
### Domain specifikáció, fogalmak
#### Fogalmak:
### Absztrakt komponensek, ezek kapcsolatai
#### Absztrakt komponensek:
#### Kapcsolatok:



## Architekturális terv !!!BOGI!!!
### Egy architekturális tervezési minta 
### Az alkalmazás rétegei, fő komponensei, ezek kapcsolatai
#### Alkalmazás rétegei:
#### Rétegek és komponensek közötti kapcsolat:
### Változások kezelése
### Rendszer bővíthetősége
### Biztonsági funkciók


## Adatbázis terv !!!BOGI!!!
**Megjegyzés - Ez még nem a végleges tervünk az adattárolásra. Terveink az alkalmazás fejelsztése alatt változhatnak, és ezt ezen pont frissítésével jelezni fogjuk.**
Terveink szerint az alkalmazásunk egy adatbázist fog alkalmazni ahhoz, hogy megfelelően működjön minden. Ehhez 4 külön táblára lesz szükségünk:

Diák
Iskola
Szervezet
Munka

### A Diák adatbázis felépítése
Ez a tábla tartalmazza azokat a diákok adatait. Ezen adatok a következők:
- diak_id (int) - Az adatok azonosítója. Elsődleges kulcs, amely egyedi minden egyes adatsorhoz. Ezt az adatbázis generálja.
- diak_keresztnev (string) -

### A Iskola adatbázis felépítése
### A Szervezet adatbázis felépítése
### A Munka adatbázis felépítése



## Tesztterv !!!BOGI!!!



## Telepítési terv !!!BOGI!!!
### Előfeltételek
