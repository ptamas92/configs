# Adatvédelmi irányelvek – Spendoid

A Spendoid alkalmazás nem gyûjt semmilyen személyazonosításra alkalmas adatot (például nevet, e-mail címet vagy telefonszámot).

A felhasználók minden funkciót regisztráció nélkül, teljesen anonim módon használhatnak.  
Az adatok alapértelmezetten kizárólag a felhasználó eszközén, a telefon memóriájában kerülnek tárolásra.

A PRO alkalmazáson belüli vásárlás aktiválásakor, az alkalmazás létrehoz egy egyedi belsõ azonosítót (`purchaseId`), és ehhez kapcsolódóan:
- menti a vásárlási adatokat (`purchase`),
- valamint idõszakosan biztonsági mentést készít a felhasználó által létrehozott adatokból egy Firebase felhõalapú adatbázisba.

Ennek célja, hogy a PRO csomagot megvásárló felhasználók, egy esetleges újratelepítést követõen:
- egyszerûen igazolni tudják korábbi vásárlásukat (a `purchaseId` vagy `transactionId` alapján),
- és automatikusan visszakapják a korábban használt adataikat (pl. beállítások, ismátlõdõ kiadásaikat, várható költségeiket stb.).

A mentett adatok kizárólag a PRO funkciók visszaállítása érdekében kerülnek tárolásra.  
Írásuk és olvasásuk hash-alapú, biztonságos azonosítókkal történik.  
**Az adatokat nem továbbítjuk harmadik félnek, nem használjuk marketing célokra, és nem végezzük azok analitikai elemzését.**

A tárolt adatok nem alkalmasak a felhasználók azonosítására, és kizárólag az alkalmazás mûködéséhez szükséges minimális információkat tartalmazzák.

Amennyiben az adatkezelési gyakorlat megváltozik, ezen az oldalon tesszük közzé a frissített irányelveket.