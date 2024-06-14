A következő feladatokban a változók kezdőértékeit a felhasználótól kérd be!

## `if`

1. `zsaner`

   Bob meglátta az utcán Alicet, aki a zsánere. Régóta szeretné megszólítani,
   de mindig felmegy a pulzusa és nem tud megszólalni.

   Vizsgáld meg, hogy Bob pulzusa `120` felett van-e és, ha igen, írd ki, hogy
   `nyugodj meg, attól megnyugszol`!

1. `alkohol`

   Bob három sört tud meginni, mielőtt vállalhatatlan lesz. Ha többet ivott
   ennél, írd ki, hogy `ideje hazamenni`!


## `if-else`


1. `szabadsag`

   Alice szabadságra szeretne menni. Kérd be, hogy hány napja van és, hogy
   hány napra szeretne menni. Ha nincs elegendő napja, írd ki, különben
   állítsd be a megmaradt napok számát a megfelelő értékre!


1. `randi`

   Alice és Bob randevúra mennek. Ha esik az eső, akkor moziba mennek,
   ha nem, akkor kirándulni.

   Kérd be a felhasználótól, hogy esik-e az eső és írd ki, hogy mi lesz
   a program a randevún!

1. `katze`

   Bob a macskás lányokat szereti, ezért az ismerkedés során megkérdezi,
   hogy szeretik-e a macskákat. Ha igen, akkor a randevú folytatódik,
   ha nem, akkor az ismerkedésnek vége.

1. `terv`

   Alice a hetét tervezgeti. Ha átmegy a JavaScript vizsgán, akkor a
   pénteki program buli lesz, ha nem, akkor tanulás. A vizsga teljesítéséhez
   `80` százalékot kell elérni.

   Kérd be Alice vizsgaeredményét és írd ki, hogy mi lesz a program!

## `else-if`

1. `felveteli`

   Az egyetemre 110 ponttól vesznek fel. A pontszámítás során bizonyos feltételek 
   esetén plusz pontokat kapunk.

   - emelt szintű érettségi: 10 pont
   - középfokú nyelvvizsga: 5 pont
   - felsőfokú nyelvvizsga: 10 pont
   - diákolimpiai bronz: 5 pont
   - diákolimpiai ezüst: 7 pont
   - diákolimpiai arany: 7 pont
   - apuci a dékán: 120 pont

   Az alap pontszám az érettségi százalékos eredménye.

   Kérd be az érettségi százalékos eredményét, majd kérdezz rá az egyes
   plusz pontokra.

   Számítsd ki az összepontszámot és írd ki, hogy felvettek-e vagy sem.

   A kérdéseket így tedd fel:

   - Érettségi százalék
   - Nyelvvizsga
     - Ha van, szint
   - Diákolimpia
     - Ha van, helyezés
   - Apuci dékán-e

1. `kave`

   Kérdezd meg a felhasználót, kér-e kávét. Ha igen, kérdezd meg, kér-e bele tejet,
   majd kérdezd meg, kér-e bele cukrot. Ha nem kért kávét, írd ki, hogy `nem kért kávét`.
   Ha kért, akkor a válaszoktól függően írd ki, hogy
   - `kávé`
   - `kávé, tej`
   - `kávé, cukor`
   - `kávé, tej, cukor`

## `logikai-operatorok`

1. `ruha`

   Ruhát vásárolunk. A kedvenc színünk a zöld, a méretünk 34-es.

   Ha a ruha zöld és a méretünk vagy nem a méretünk, de 33-as vagy 35-ös és zöld, akkor megvesszük.

1. `mozi`

   Moziba szeretnénk menni a partnerünkkel. Egyetlen időpont jó csak, úgyhogy el 
   kell dönteni, hogy az abban időpontban vetített film megfelel-e a feltételeknek.

   Mi scifit akarunk nézni, ő westernt. A mi kedvenc színészünk Alice Alisson, az
   övé Bob Robertson. Az ő által legjobban utált színész Cecil Cecilianus, a miénk
   Dean Delorean.

   Ha a film scifi vagy western vagy szerepel benne valamelyikünk kedvenc színésze,
   megnézzük.

   Ha szerepel benne olyan színész, akit utálunk, nem nézzük meg, akkor sem, ha minden más kritériumnak megfelel a film.

1. `fagyi`

   Egyféle fagylalt van: vanília. Két gombóc van belőle. Kérd be a
   felhasználótól, hogy mi a kedvenc fagylaltja.
   - Ha nem vaníliát írt be, írd ki, hogy "nincs szerencséd".
   - Ha vaníliát írt be, kérdezd meg, hány gombócet kér.
   - Ha kettőnél többet kért, írd ki, hogy "nincs elég gombóc".
   - Különben azt, hogy "kedves egészségedre" 