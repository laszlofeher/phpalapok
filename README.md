# Php tanfolyam 12 alkalom

12 alkalom (12*6 óra) folyamán megismerkedünk a Php alap rejtelmeivel.  

## 1. alkalom

Az első alkalom tartalma:
 - **[XAMPP](https://www.apachefriends.org/hu/index.html)**  (XAMPP kapcsán keresztül a PHP verziók és felfutásának rövid ismertetése) -
 - **[Netbeans](https://netbeans.apache.org/download/index.html)** vagy **[Viusal Studio Code](https://code.visualstudio.com/)** és **[Devsense bővítmény](https://www.devsense.com/en)** telepítés.  
	 - **[Visual Studio Code -hoz tartozó Devsense bővítményről itt lehet bővebben magyarul olvasni](https://prog.hu/hirek/6341/nagyon-komoly-ingyenes-php-tamogatas-jott-a-visual-studio-hoz)** 
 - Az alap fogalmak megismerése: **kliens-szerver** működés. **HTTP** protokoll részletezése. 
 - A **Változó** fogalmának ismertetése.  
 - **Konstans** fogalma és definiálása. 
 - Neumann elvek magyarázata a változó elhelyezése. A változóval kapcsolatban a típusok ismertetése, különbség szám és szöveg ábrázolás között. 
 - Operátorok ismertetése
- **Vezérlési szerkezetek/Flow Control** bemutatása példákon keresztül. 
	- Sor
	- Feltétel / Elágazás
	- Ismétlődő végrehajtás / Ciklus

### Diasorok 
---

|                                          |Dia / ppt file neve            |
|------------------------------------------|-------------------------------|
|Alapfogalmak	                           |`Php1_bevezeto.pptx`           |
|Xampp telepítése                          |`Xampp.pptx`		   |
|Netbeans telepítése                       |`Netbeans.pptx`                |
|Változók, vezérlési szerkezetek           |`Php1.pptx`                    |

#### Házi feladat: 
>Egy 10*10 táblázat kiírása, php nyelven. 

## 2. alkalom
### Alapvető programozási tételek
- Összegzés
- Eldöntés
- Kiválasztás

A fentiek bemutatása a PHP -ban, és a kész PHP függvényekkel összevetés mivel ezek az algoritmusok készen vannak a PHP nyelvben. 
Tömbök fogalma és használata, tömbök bejárása, ezekhez kapcsolodó PHP függvények.  
Szöveg kezeléssel kapcsolatos feladatok. 

#### Házi feladat: 
>Palindrom vizsgálat (indul a görög aludni szöveget lehet-e vissza felé olvasni.) 
>Banki számlaszám ellenőrző kódjának vizsgálata. 
>Taj szám ellenőrző kódjának vizsgálata. 

## 3. alkalom

**\$_POST**, **\$_GET** rendszertömbök ismertetése. HTML űrlap és a php kapcsolata. Egyszerű belépés oldal készítése (valódi bejelentkeztetés nélkül) . Regisztrációs űrlap php oldali ellenőrzése.  File feltöltés **\$_FILES** rendszertömb használata. 
#### Házi feladat: 
> Űrlapon keresztül küldjön be egy egyismeretlenes egyenletet (pl.: x+5= x-2) és írja ki a megoldás lépéseit. Az egyenlet helyességét nem kell ellenőrizni, illetve feltételezzük, hogy mindig ilyen jellegű egyenlet lesz beírva. 
## 4. alkalom

File kezelés a PHP nyelv keretein belül. GD, IMAGICK könyvtárak használata a képek módosításához. Egy galéria elkészítése, amely egy könvytárban lévő összes képet felolvassa és megjeleníti. 
#### Házi feladat: 
> Az órán ekészített galériához feltöltö felület készítése

## 5. alkalom

Az adatbázis kezelés alapjai. Relációs adatmodell ismertetése. Normalizálás lépései. MySQL/MariaDB alapok. Adatbázis kapcsolat a PHP nyelven keresztül. Adatbázishoz kliensként csatlakozik a Php. 
#### Házi feladat: 
> Egy blog adatmodelljének elkészítése
> 
## 6. alkalom

**SQL** nyelv **DDL** (Data Definitions Language), **DML** (Data Manipulations Language). A SELECT utasítás részletezése. SQL feladatok megoldása példákon keresztül. SQL -ben használatos függvények. Aggregált (összegző) függvények. **WHERE , GROUP BY , ORDER BY,  JOIN** példák. 

#### Házi feladat: 

> A blog adatmodelhez kapcsolodó SELECT lekérdezések megírása. Feltöltött példa adatokon keresztül. Összes cikk lekérdezése és időrendben állítása. Témakörönként csoportosítva. Évre és hónapra csoportosítva. 

## 7. alkalom

Blog elkészítése hagyományos módon, keretrendszer nélkül. Admin felület a cikk feltöltésekhez. Login kezelése **\$_SESSION** rendszertömb megismerése. 

## 8. alkalom

OOP a Php nyelvben. Osztályok, öröklés, egységbe zárás és más OOP fogalmak tisztázása. Példák elkészítése. 
#### Házi feladat: 
> Abstract osztály készítése, egy általános művelet absztrakt osztály, és az összeadás, kivonás osztály létrehozása a művelet osztályon keresztül. 

## 9. alkalom

////

## 10. alkalom

**Codeigniter** keretrendszerben a Blog elkészítése. A 7. alkalom során elkészített blog **Codeigniter framework**be átültetése. 

## 11. alkalom

////

## 12. alkalom

////

## 13. alkalom

Egy összefoglaló dolgozat elkészítése. Vizsga munka megbeszélése.

# Összefoglaló feladatok
#### Egy lehetséges vizsgasor 

- Írd le mi a különbség a szerveroldali és a kliensoldali szkriptek közt!
- Adott egy tömb:
  ```
  $allatok = ['Kutya','Cica','Egér','Papagáj','Pók']
  ```
   Készíts egy ciklust, amivel kiíratod mindet egy H1 elemben!
 - Tekintsd az alábbi függvényt:
	  ```
	  function (int $x){
			echo $x; 
	}
	  ```
	Írd le, hogy mit jelent a zárójelben szereplő int $x!
- Készíts egy 5 elemű asszociatív tömböt, amiben a kulcsok az abc betűi, az értékek pedig egy-egy, az adott betűvel kezdődő név.
- Készíts egy függvényt, ami kiszámolja egy egész szám faktoriálisát!
- Mi a különbség az = , == , === jelek között a PHP nyelvben.
- Használd a vizsgához mellékelt PHPVizsgaSQL.sql fájlt, majd válaszolj a kérdésekre: 
  A SELECT utasításokat is írd le!
  -	Hány fejlesztő van?
  - Hány magyar fejlesztő van?
  - Hogy hívják a magyar fejlesztőket?
  - Mely országokban laknak Alana nevű fejlesztők?
-  Készíts egy classt, ami az előző felhasználóhoz hozzáad téged.  Legyen külön classban az SQL kapcsolat, tőle örökölje a kapcsolatot a class.
> Ilyen és ehhez hasonló feladatokra kell felkészülni. 2,5 óra időtartam alatt. 15 darab hasonló kérdésre kell válaszolni. A válaszokat egy egybe csomagolt zip file-ban kell küldeni. A vizsga elején megadott email címre. A levél tartalmából egyértelműen derüljön ki a feladó kiléte. 


# Vizsga munka követelményei
- Írja le a követelményeit/elvárásait a programmal szemben. Követelményspecifikáció.  
- Készítsen egy adatmodellt, az adatmodell legalább 3 táblából álljon.
- A programban legyen egy útvonalválasztó, amely kezeli a beérkező kéréseket. **.htaccess**-t használjon. 
  GET "/", továbbá, 
  GET 'admin/uj-adat" az elérések természetesen szabadon választhatóak. 
  Az új adatok beírásához, módosításához, törléséhez POST üzeneteket használjon.
- A projekt álljon egy legalább egy oldalból, amely adatbázisból szedi az adatait.
- A projektben legyen egy bejelentkezés. Admin felület.
- A projektben a bejelentkezés után képesek legyünk, valamilyen adatot módosítani, amely változást a főoldalon látni lehet. Admin felület.
  
#### Felhasznált PowerPoint sablon 
**[Sablon](https://www.slidescarnival.com/gaoler-free-presentation-template/9122)**
#### Felhasznált Grafikák
**[Leírás](https://uxplanet.org/isometric-free-isometric-illustrations-for-any-projects-27af857e6ad0)**
**[Grafikák](https://isometric.online/)**
