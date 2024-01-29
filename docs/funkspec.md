# Funkcionális specifikáció
 
## Jelenlegi helyzet leírása
 A mai középiskolások számára elengedhetetlen az 50 óra közösségi szolgálat teljesítése az érettségi megszerzéséhez. A rohanó világban szeretnénk minél egyszerűbben hozzáférni a kívánt információkhoz és mindent digitalizálni. Sok közösségi szolgálatot nyújtó szervezet nehezen tudja elérni a diákokat, hogy tájékoztassák a náluk lévő lehetőségekről ****, valamint a diákoknak nehézséget okoz információt szerezni a lehetőségeikről. 
Webalkalmazásunk célja, hogy segítsük a diákokat tájékoztatni a különböző közösségi szolgálatok lehetőségeiről ******. A diákok tudnak szűrni a közelükben lévő lehetőségekről*****, fel tudják venni a kapcsolatot a szervezet koordinátorával, tudnak üzenetet küldeni, valamint automatikus üzenetet kapnak, ha megjelenik egy új lehetőség. 

## A rendszer céljai és nem céljai 
### A rendszer céljai

- Egy olyan rendszer létrehozása, amelyet könnyű minden felhasználónak használnia, megértenie
- A rendszer gyors működésének biztosítása
- A felhasználók személyes adatainak védelme
- Bármilyen gépi eszközön működjön a webes alkalmazás, internetes kapcsolat feltétele mellett
- A felhasználót tájékoztassa az aktuális közösségi szolgálati munkákról
- Lehetővé tenni a diákok számára, hogy keressenek közösségi szolgálati munkákat megye, kategória és város alapján
- Lehetővé tenni a szervezet számára, hogy online igazolja a diákok által elvégzett ötven órás közösségi szolgálati munkát***

### Nem céljai

- A rendszer nem tervezett olyan funkciókat támogatni, amelyek kereskedelmi célú közösségi szolgálati munkákra vonatkoznak


## Vágyálomrendszer leírása
A weboldalunk célja a jelenlegi közösségi szolgálati folyamatok egyszerűsítése és digitalizálása. Lehetővé szeretnénk tenni a diákoknak, hogy könnyebben megtalálják és kiválasszák a számukra megfelelő közösségi szolgálatot. A szervezetnek, hogy hírdesse a náluk lévő lehetőséget, valamint könnyen kezelheti a tanulók jelentkezését és az órák leigazolását.


## Jelenlegi üzleti folyamatok leírása
Napjainkban igyekszünk mindent a leghatákonyabban, leggyorsabban megoldani. A közösségi szolgálati folyamatok jelenlegi állapota hagyományos és papíralapú módszereket alkalmaz, amelyek nehezen kezelhetők, követhetők mind a diákok, mind az iskolák és szolgáltatók számára. Az informatikai megoldásunk célja, hogy ezeket a folyamatokat hatékonyabbá, gyorsabbá és átláthatóbbá tegyük.

## Igényelt üzleti folyamatok leírása
Azért, hogy egyszerűbbé tegyük a diákok, a tanárok és a szolgáltatók
feladatát, létrehozunk egy weboldalt, ami a mai kornak megfelelően
helyt tud állni az elektronikai világban. A szolgáltatóknak egyszerűbb lesz,
mert a náluk végezhető közösségi munka több diákhoz jut el a webalkalmazás
segítségével, és az adminisztrációs feladatok könnyebben elvégezhetők.
A diákoknak is sokkal jobb, mert egyszerűbben tudnak tájékozódni az aktuális közösségi munkákról és a leigazoló dokumentumokkal is kevesebb feladatuk van.
Mivel minden adminisztrációs feladat online mūködik, így sok időt sporolunk meg vele, és emellett nem kell nyomtatásokat végezni, amivel a környezetünkre is odafigyelünk.


## Használati esetek 

### 1. Felhasználók és szerepek

#### 1.1 Admin
- Létrehozhat és kezelhet iskolákat, diákokat, és szolgáltatókat
- Felhasználói fiókokat tud kezelni és szükség esetén letiltani

#### 1.2 Iskola
- Hozzáférhet a diákjaihoz és kezelheti az adatait


#### 1.3 Diák
- Keresési lehetőség a szolgáltatások között város, megye, kategória  alapján
- Megtekintheti az elérhető szolgáltatásokat és jelentkezhet rájuk
- Láthatja a saját iskolája által jóváhagyott szolgáltatásokat
- Saját profil kezelése és követése
- Kapcsolatfelvétel a szolgáltatóval direkt üzenet formájában.

#### 1.4 Szolgáltató
- Hirdethet közösségi szolgálati munkákat
- Kezelheti a jelentkezéseket és elfogadhat vagy elutasíthat diákokat
- Leigazolhatja az elvégzett órákat 


### 2. Leigazoló nyilatkozat


#### 2.1 Ötven óra leigazolása
- A szolgáltató online folyamatosan tudja leigazolni az órákat a munka végzése közben
- Záró igazolás kiállítása ötven óra elvégzése után


### 3. Keresés és szűrés
![Tanuló adatbázis lekérdezése](img/lekerdezes.png)

#### 3.1 Szolgáltatások keresése

- Megye szerint
- Település szerint
- Iskola  partnerei szerint
- Kategória szerint


### 4. Felhasználói fiók kezelése

#### 5.1 Fiók létrehozása/bejelentkezés

- Minden felhasználó képes létrehozni egy fiókot és bejelentkezni
- Felhasználók a következő információkat adják meg a regisztráció során:
  Diák:
  Iskola:
  Szolgáltató: 
- A jelszónak megfelelő erősségűnek kell lennie
- Az alkalmazásnak ellenőriznie kell az e-mail cím formátumát és egyediségét a rendszerben
- Regisztrált felhasználók bejelentkezhetnek az alkalmazásba a megadott e-mail cím és jelszó segítségével.

#### 5.2 Elfelejtett jelszó funkció

-A felhasználók elfelejtett jelszó esetén kérhetnek jelszó-visszaállítási e-mailt

### 6. Biztonság és adatvédelem

- Az alkalmazásnak megfelelő biztonsági intézkedéseket kell biztosítania a felhasználói adatok védelme érdekében. Ideálisan a jelszavakat biztonságosan kell tárolni és az adatok titkosítását kell alkalmazni.

## Követelménylista


### Funkcionális követelmények
|     | Követelmény                              | Leírás |
|----------|-------------------------------|------------------------------------------------------------------------------------------------------------------------|
| 1        | **Regisztráció és bejelentkezés** | Külön regisztrációs és bejelentkezési felület a diákoknak, iskolai személyzetnek, és közösségi szolgálatot biztosítóknak. A diákoknak kötelező megadni az alapvető információkat, beleértve az iskolai adatokat és elérhetőségeket. A szolgáltatók munkaajánlatukat itt tölthetik fel. |
| 2        | **Szűrés és keresés**             | A diákok böngészhetnek az elérhető szolgálati lehetőségek között település, kategória és tevékenységi kör alapján. Az alkalmazás ajánlásokat ad a diákoknak a lakóhelyük közelében elérhető intézményekről.                                |
| 3        | **Jelentkezési folyamat**         | A diákok az oldalon keresztül jelentkezhetnek a kiválasztott munkára, ahol a szolgáltató el is fogadhatja a jelentkezést.                                                               |

| 4        | **Kommunikáció**                  | A diákoknak lehetőségük van direkt üzenetek küldésére a szolgáltatónak, amivel egyszerűbb a kapcsolatfelvétel és kapcsolattartás.                                                       |
| 5        | **Automatikus email**             | A rendszer minden bejövő üzenetről értesítést küld a felhasználónak az oldalra regisztrációkor megadott email címre.                                                                |
| 6        | **Teljesítés igazolása**          | A weboldalon történik meg a diákok legdolgozott óráinak leigazolása, amely letölthető PDF formátumban is.                                                                         |
| 7        | **Adminisztrátori felület**        | Az adminnak saját felhasználói felülete van, aki minden jogosultsággal rendelkezik a rendszer adminisztrációjához.                                                                |

### Nem-funkcionális követelmények ***
|  | Követelmény               | Leírás                                                                                                                     |
|----------|-------------------------|----------------------------------------------------------------------------------------------------------------------------|
| 8        | **Biztonság**        | Felhasználói adatok biztonságának védelme, beleértve a GDPR-megfelelőséget. Jogosultságkezelés a különböző szerepkörű felhasználók (diák, tanár, adminisztrátor) számára.    |
| 9        | **Teljesítmény**     | Gyors és hatékony szolgáltatások biztosítása.  Az alkalmazásnak megfelelően kell működni, ha egyidejűleg akár 1000 diák és 50 intézmény is használja.    |
| 10        | **Rugalmasság**      | Könnyen frissíthetőnek és rugalmasnak kell lennie a honlapnak, hogy alkalmazkodjon a jövőbeli igényekhez.           |
| 11        | **Platformfüggetlenség**    | A weboldalnak platformfüggetlenül kell működnie, hogy a felhasználók bármilyen eszközön hozzáférhessenek.    |
| 12        | **Felhasználóbarát Felület** | Egyszerű és felhasználóbarát felület mind a diákok, mind az intézmények számára.   |         
| 13       | **Szerver Paraméterek**     | A webhelynek megfelelően kell működnie a megadott szerver paraméterekkel.                                              |



#### A tanuló adatbázis követelményei

A megfelelően működő weboldalhoz ezek szükséges  adatbázis követelmények:

Felhasználói adatok tárolása: Az adatbázisnak tárolnia kell a diákok és intézmények regisztrációs adatait. Ide tartoznak az alapvető információk (nevük, email címük, jelszavuk stb.), az iskolai adatok (iskola neve, OM azonosító, IKSZ koordinátor neve és elérhetősége).

Szolgálati lehetőségek tárolása: Az adatbázisnak rögzítenie kell  szolgálatot kínáló intézmények adatait, az alapinformációkat, a programleírásokat, a kapcsolattartók elérhetőségeit.

Teljesítési adatok kezelése: Az adatbázisnak nyomon kell követnie a diákok által végzett közösségi munka teljesítéséhez kapcsolódó információkat.

Jogosultságkezelés: Az adatbázisnak támogatnia kell a felhasználók különböző jogosultságait, különböző jogosultsággal rendelkezik a diák, iskola, szolgáltató és az admin.

Értesítési rendszer: Az adatbázisnak támogatnia kell az automatikus értesítéseket, hogy a diákok és intézmények időben értesüljenek a szolgálati lehetőségekről vagy beérkező üzenetekről.

Rugalmas fejleszthetőség: Az adatbázisnak lehetővé kell tennie a könnyű bővítést és frissítést a jövőbeli igényekhez való alkalmazkodás érdekében.

Teljesítmény: Az adatbázisnak hatékonyan kell működnie, különösen olyan időkben, amikor akár ezer diák és ötven intézmény is aktív lehet az alkalmazásban. 

Adatbiztonság: Az adatbázisnak megfelelő biztonsági intézkedéseket kell tartalmaznia, például jelszóvédelmet, adatbázis titkosítást és hozzáférési jogok szigorú kezelését a GDPR követelmények teljesítése érdekében.



## Képernyőtervek 
**Megjegyzés - Ez még nem a végleges képernyőtervünk. Terveink az alkalmazás fejelsztése alatt változhatnak, és ezt ezen pont frissítésével jelezni fogjuk.**

### Kezdő oldal
A kezdő oldalon bejelentkezés nélkül egy tájékoztató szöveget kapunk az oldalról.
Nem bejelentkezett felhasználó semmilyen adatot nem tud lekérni az oldalról.
A menüsávban látható az oldal neve, logója és a bejelentkezés gomb.
![Kezdő oldal](img/kezdo-oldal.png)
### Bejelentkezés
A bejelentkezésre kattintva felúszik egy ablak.
Betudunk jelentkezni diák, tanár vagy szoláltatóként.
Elfelejtett jelszó esetén az emailunkra küld egy jelszó emlékeztetőt.
Amennyiben nem vagyunk még regisztrálva az oldalon abban az esetben a regisztrációs fülre kattintva megtehetjük.
![Bejelentkezés](img/bejelentkezes.png)

### Regisztráció
Regisztrációnál három felhasználó típus közül tudunk választani.
Mindegyiknél más adatokat kér be. Nem helyes vagy hiányos formátumnál nem engedi regisztrálni.
![Regisztráció](img/regisztracio.png)

### Diákok által kezelt oldal
Amennyiben diákként sikeresen bejejelntekett a következő oldal látható.
Az összes munka felsorolva látható. 
Tud a diák kulcsszóra keresni vagy választhatja a részletes keresést.
A menüsávban megtalálja a profil megtekintését és a kijelentkezést.
![Diák oldal](img/diak-oldal.png)

### Keresés

Lehetősége van a felhasználónak szűrni megyére, városra és kategóriára.
Keresés gomb megnyomásával a keresési feltételeinknek megfelelő találatokat kapjuk.
![Részletes keresés](img/kereses.png)

### Munka megtekintése
Egy kiválasztott munka megtekintésénél láthatjuk a munka címét és leírását.
Emellett tudunk küldeni üzenetet a szolgáltatónak.

![Munka leírása és jelentkezés](img/munka-leiras-jelentkezes.png)

### Profil
A profilra kattintva egy oldalsó menüsávból választhatunk.
Tudjuk a profilunkat szerkeszteni de vannak olyan adatok amik nem változtathatóak.
Mentés gobbal a változtatásokat eltudjuk menteni.
![Profil szerkesztése](img/profil-szerkesztes.png)

A munka fül kiválasztásánál láthatjuk a munkáinkat.
Abban az esetben,ha még nincs egyse, egy gomb megnyomásával a munka kereséshez vezet.
A munkáink egymás alatt felvan sorolva és mellette megnyitható a hozzá kapcsolósó igazoló lap amit a diák nem tud szerkeszteni.
A lap alján egy összesítő, hogy mennyi van meg az ötvenből.
![Profil szerkesztése](img/profil-munka.png)

A menünkből az üzeneteket kiválasztva látjuk a neveket. 
Ezt kiválasztva megtudjuk nézni az üzenetet és tudunk választ küldeni
Ide érkeznek a rendszerüzenetek is mint például: munka elfogadva, az iskolád megkötötte a szerződést... .
Új üzenet eszetén a fő menüsávban a profil mellett egy piros boriték jelzi, hogy üzenetet kaptunk és a
meg nem nyitott üzenetek megvannak különböztetve.
![Profil szerkesztése](img/profil-uzenet.png)


