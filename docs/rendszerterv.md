# Rendszerterv  

## A rendszer célja !!!TÜNDE!!!
A weboldal célja segíteni a középiskolai diákokat az ötven óra közösségi szolgálat teljesítésének lehetőségeivel kapcsolatos tájékozódásban és adminisztratív feladataik digitalizálásában. Ezáltal könnyedén megtalálhatják és jelentkezhetnek a számukra érdekes és megfelelő szolgálati lehetőségekre. Emellett a rendszer lehetőséget biztosít az órák nyilvántartására és leigazolására, valamint a szolgáltatókkal való kommunikációra, mindezt egy felhasználóbarát, online platformon keresztül. A cél az, hogy a diákoknak és az intézményeknek egyszerűbb és hatékonyabb legyen az adminisztrációs folyamatok kezelése, és hogy mindez a hagyományos, papíralapú módszerekhez képest időt és erőforrásokat takarítson meg.


## Projektterv !!!TÜNDE!!!
### Elvégzendő feladatok
A rendszer elkészítésének lépései: 
    
**1. Rendszertervezés:** 
    
- Funkcionális és nem-funkcionális követelmények kidolgozása
- Adatbázis felépítésének megtervezése
- Felhasználói felület kialakítása
        
**2.Fejlesztés:**
- Adatbázis létrehozása a megtervezett séma alapján
- Frontend és backend rész kódolása
- Felhasználói felület fejlesztése és funcionalitások implementálása

**3. Tesztelés:**
- Az alkalmazás tesztelése különböző környezetekben és eszközökön
- A tesztelés során azonosított hibák kijavítása
- Az alkalmazás teljesítményének optimalizálása és javítása

**4. Dokumentáció:**
- A kész projekt részletes dokumentálása

### Felelősségi körök ????
### Mérföldkövek
Projekt megfontosab mérföldkövei: 
 - A projekt kezdeti tervezése és célok meghatározása
 - Funkcionális és nem-funkcionális követelmények kidolgozása és jóváhagyása
 - Adatok begyűjtése
 - Adatbázis felépítése
 - Felhasználói felület tervezése és prototípusának elkészítése
 - Weboldal kódjának megírása, hozzá tartozó adatbázis létrehozása
- Elkészült projekt tesztelése, hibák javítása
- Webalkalmazás telepítése és konfigurálása a kiszolgálón
- Projekt zárása, végleges dokumentáció elkészítése
### Ütemterv ????

## Üzleti folyamatok modellje !!!TÜNDE!!!

#### Üzleti szereplők

- **Diákok:** A középiskolás diákok, akik keresik és jelentkeznek a közösségi szolgálati lehetőségekre
- **Iskolák:** Diákok adatainak kezelése, a ledolgozott órák számának nyilvántartása az adatbázisban
- **Szolgáltatók:** Azok a szervezetek vagy intézmények, amelyek közösségi szolgálati lehetőségeket kínálnak a diákoknak, és kezelik a jelentkezéseket, valamint leigazolják az elvégzett órákat
- **Adminisztrátorok:** Azok a felhasználók, akiknek adminisztratív feladatokat kell ellátniuk a rendszerben, például új iskolák és szolgáltatók hozzáadása, felhasználói fiókok kezelése stb.

#### Üzleti folyamatok 
- **Regisztációs folyamat:** Különböző szerepkörnek megfelelően tudnak regisztrálni a rendszerben a diákok, iskolák, szolgáltatók. 
- **Büngészés és szűrés:** A feltöltött munkák között lehet szűrni  megye, település és kategória szerint
- **Jelentkezési folyamat:** A diákok keresik és jelentkeznek a rendszerben elérhető közösségi szolgálati lehetőségekre, a szolgáltatók pedig elfogadják vagy elutasítják a diákok jelentkezéseit.
- **Ledolgozott órák leigazolása:** A közösségi szolgálat elvégzése után a szolgáltató leigazolja a rendszerben a ledolgozott órákat, amit továbbítani tud az iskolának
- **Kommunikáció:** A diákok, iskolák és szolgáltatók közötti kommunikáció lehetőségei a rendszeren belül, például üzenetküldés, értesítések stb.


## Követelmények !!!TÜNDE!!!
### Funkcionális követelmények

> **Regisztráció és bejelentkezés**
- Ahhoz, hogy a rendszert használni tudják a felhasználók, beleértve a diákokat, iskolákat és szolgáltatókat,  regisztrálniuk kell az oldalra..
- A regisztráció során a felhasználóknak meg kell adniuk az alapvető információkat attól függően milyen szerepkörrel akarnak regisztrálni
- A már regisztrált felhasználók képesek lesznek bejelentkezni a rendszerbe az e-mail címük és jelszavuk segítségével
- A bejelentkezés után a felhasználók hozzáférnek a rendszer funkcionalitásaihoz, attól függően, hogy milyen szerepkörrel rendelkeznek

> **Szűrés és keresés**
- A felhasználók lehetőséget kapnak a közösségi szolgálati lehetőségek szűrésére és keresésére a rendszeren belül.
- A szűrés és keresés lehetőségei közé tartozik a kategória, megye, város szemponjai.

> **Jelentkezési folyamat**
- A diákok, a feltöltött munkák közzül kiválasztják a számukra legrelevánsabb munkát és azután tudnak rá jelentkezni
- A jelentkezés megérkezik a szolgáltatóhoz, aki el tudja fogadni vagy akár utasítani is a jelentkezést a rendszeren belül 

> **Kommunikáció** 
- A rendszer lehetőséget biztosít a felhasználók közötti kommunikációra, közvetlen üzenetet tudnak küldeni egymásnak, ami megkönnyíti a közvetlen kapcsolattartást és együttműködést

> **Automatikus email** 
- A rendszer automatikusan értesítéseket küld a felhasználóknak az aktuális eseményekről és változásokról, például új lehetőségek megjelenéséről, jelentkezés elfogadásáról, beérkező üzenetekről

> **Teljesítés igazolása**
- A szolgáltatók képesek lesznek az elvégzett közösségi szolgálati órák leigazolására a rendszeren belül, amit tovább tudnak küldeni az iskoláknak
- A diákok hozzáférhetnek az általuk elvégzett órákhoz, és az igazolás számukra is elérhető lesz letölthető pdf formátumban.

> **Adminisztrátori felület**
-Az adminisztrátoroknak külön felhasználói felületet biztosít a rendszer, amely lehetővé teszi az adminisztratív feladatok végrehajtását, például felhasználók kezelése, vagy új lehetőségek hozzáadása

### Nem-funkcionális követelmények

> **Biztonság**
-  A weboldalnak megfelelő biztonsági intézkedéseket kell biztosítania a felhasználói adatok védelme érdekében
- Ideális esetben a jelszavakat biztonságosan kell tárolni és az adatokat titkosítani kell, továbbá a jogosultságokat szigorúan kell kezelni az adatokhoz való hozzáférés tekintetében

> **Teljesítmény**
- A rendszernek gyors és hatékony működést kell biztosítania, még akkor is, ha egyidejűleg nagy mennyiségű felhasználó használja
- A rendszernek hatékonyan kell működnie, akár több száz vagy több ezer felhasználó esetén is

> **Rugalmasság**
- A webalkalmazás könnyen bővíthető és frissíthető kell legyen, hogy alkalmazkodjon a jövőbeli igényekhez és technológiai változásokhoz
- Rugalmasan kell kezelnie az új funkciók hozzáadását és a meglévő funkciók fejlesztését

> **Platformfüggetlenség**
- A honlapnak platformfüggetlenül kell működnie, azaz a felhasználók bármilyen eszközön és böngészőben hozzáférhetnek hozzá, legyen az számítógép, mobiltelefon vagy táblagép, és legyen az Windows, macOS, vagy Linux operációs rendszer
> **Felhasználóbarát Felület**
- A rendszernek könnyen használható felhasználói felülettel kell rendelkeznie mind a diákok, mind az intézmények számára. Az interfésznek intuitívnak és ergonomikusnak kell lennie, hogy a felhasználók könnyen megtalálják és használják a rendszer funkcionalitásait

> **Szerver Paraméterek**
- A rendszer működéséhez megfelelő szerverparaméterekre van szükség, amelyek lehetővé teszik a webalkalmazás gyors és stabil futását
- Ezek a paraméterek magukban foglalhatják a szükséges processzor teljesítményt, memóriát, adatbázis konfigurációt és hálózati kapcsolatokat

### Törvényi előírások, szabványok
Mivel a felhasználók személyes adatait kezelni fogja a rendszer (pl. diákok személyes adatai, intézményi kapcsolattartók elérhetőségei stb.), fontos biztosítani, hogy az adatkezelés mindenben megfeleljen az EU GDPR előírásainak, vagyis az Európai Unió Általános Adatvédelmi Rendeletének.


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
- Felhasználó: Az alkalmazásba regisztrált személy, aki jelentkezhet közösségi szolgálatra
- Szolgáltató: Olyan szervezet vagy személy, amely közösségi szolgálati lehetőségeket kínál diákok számára
- Közösségi szolgálat: Olyan tevékenység, amelyet a diákok önkéntesen vállalnak, általában közhasznú szervezetek vagy intézmények számára


### Absztrakt komponensek, ezek kapcsolatai
#### Absztrakt komponensek:
- Felhasználói adatbázis: Az alkalmazás által kezelt felhasználók és azok adatai, beleértve a diákokat, tanárokat és szolgáltatókat.
-Diák adatbázis: A diákokhoz kapcsololódó adatbázis, melyben szerepel az összes szükséges adat
- Iskolai adatbázis: Az iskolákhoz kapcsolódó adatokat kezelő adatbázis, ideértve az iskolai profilokat és az iskolákhoz tartozó diákokat
- Szolgáltatói adatbázis: A szolgáltatókhoz kapcsolódó adatokat kezelő adatbázis, ideértve a szolgáltatói profilokat és a szolgáltatásokat, ideértve a munkaleírásokat és a jelentkezési folyamatot is

#### Kapcsolatok:
- A felhasználói adatbázis kapcsolódik az iskolai adatbázishoz és a szolgáltatói adatbázishoz, hogy tárolja és kezelje a felhasználók adatait és szerepköreit
- Diák adatbázis kapcsolódik a szolgáltató adatbázishoz, hogy jelentkezni tudjon a közösségi munkára, valamint, hogy le tudja igazolni a ledolgozott órákat. 
- Az iskolai adatbázis kapcsolódik a szolgáltatói adatbázishoz, hogy listázza és kezelje a diákok ledolgozott óráit.



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
