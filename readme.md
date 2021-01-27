Feladat 3. :
==============

Írjunk programot Delphiben amely csatlakozik az `b2_teszt` Oracle adatbázishoz és 
lekérdezi a string tábla elsõ 20 sorát, majd megjeleníti egy rlcdbgrid komponensen!

- az adatbázis-mûveletekzhez használjuk a RMDB fülön lévõ komponenseket
- a connection string legyen a következõ: `Provider=OraOLEDB.Oracle.1;Password=varju;Persist Security Info=True;User ID=b2_teszt;Data Source=RAMAORALINUX`
- a provider: `OraOLEDB.Oracle.1`
- a tábla neve `string`, az oszlopok nevét és az egyéb tudnivalókat plsql developer segítségével nézd meg 


TIPP:
- elõször írd meg és próbáld ki a szükséges lekérdezést plsql developerben
