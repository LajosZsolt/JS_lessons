# while-loop

Ahol a feladat külön nem kéri, ott eltekintetünk a hibakezeléstől, input
ellenőrzéstől.

Minden feladatban `while` ciklust kell használnod, nem elég közvetlenül kiírni
a kért elemeket.

A megoldásodat alternatív adatokkal is teszteld, pl:
- üres tömb
- olyan tömb, amiben csak a feltételeknek megfelelő elemek vannak
- olyan tömb, amiben nincs a feltételeknek megfelelő elem
- olyan tömb, amiben csak egy feltételnek megfelelő elem van
- olyan tömb, amiben több feltételnek megfelelő elem is van
- olyan tömb, amiben több feltételnek megfelelő elem is van

__Ne csak a fentiek alapján tesztelj.__ Légy kreatív, gondold meg, hogy a feladat
alapján milyen érdekes esetek fordulhatnak elő és nézd meg, hogy azokra is helyesen
működik-e a program. Ha nincs specifikálva, hogy hogy kell viselkednie a programnak
egy adott esetben, akkor a kiírás alapján gondold meg, kérdezz rá, beszéljétek meg,
hogy mi tűnik logikusnak.


Tekintsük az alábbi tömböket:

```js
let t = [42, 55, 123];
let u = [91, 23, 0, 45, 78];
let v = [1, 1, 0, 1, 0, 1, -1, 0, -1, 0];
let hallgatok = [
  { vezeteknev: "Almasi", keresztnev: "Alice", pont: 76},
  { vezeteknev: "Bagosi", keresztnev: "Bob", pont: 68},
  { vezeteknev: "Copfos", keresztnev: "Cecil", pont: 73}
];
```

## sorozat generálás

1. Írd ki az első 5 pozitív egész számot.
    ```js
    1
    2
    3
    4
    5
    ```
1. Írd ki az első 5 nemnegatív számot.
    ```js
    0
    1
    2
    3
    4
    ```
1. Írd ki az első 5 negatív számot.
    ```js
    -1
    -2
    -3
    -4
    -5
    ```
1. Írd ki a pozitív számokat 1-től 10-ig kettesével
    ```js
    1
    3
    5
    7
    9
    ```
1. Írd ki az első hat nemnegatív számot kettesével
    ```js
    0
    2
    4
    6
    8
    ```

### sorozat generálás + user input

1. Kérj be egy `n` pozitív egész számot. Írd ki a pozitív számokat 1-től n-ig.
    ```js
    // n == 4
    1
    2
    3
    4
    ```
1. Kérj be egy `n` tetszőleges egész számot. Írd ki az első `5` egész számot `n`-től
  kezdve.
    ```js
    // n == -3
    -3
    -2
    -1
    0
    1
    ```
1. Kérj be egy `n` tetszőleges egész számot. Írd ki az első `n` egész számot 0-tól
   kezdve.
   ```js
   // n == 4
   0
   1
   2
   3
   ```
1. Kérj be egy `n` és egy `m` egész számot. Írd ki az első `n` egész számot `m`-től kezdve.
    ```js
    // n == 4, m == 3
    3
    4
    5
    6
    ```
1. Kérj be egy `n`, egy `m` és egy `k` egész számot. Írd ki az első `n` egész számot `m`-től kezdve, `k` lépésközzel.
    ```js
    // n == 4, m == 3, k == 3
    3
    6
    9
    12
    ```


## tömb bejárás


1. Írd ki `t` elemeit, balról jobbra.
   ```
   42
   55
   125
   ```
1. Írd ki `t` elemeit, jobbról balra.
   ```
   125
   55
   42
   ```
1. Írd ki `u` első 4 elemét.
    ```js
    91
    23
    0
    45
    ```
1. Írd ki `u` utolsó 3 elemét
    ```js
    0
    45
    78
    ```
1. Írd ki `u` középső 3 elemét.
    ```js
    23
    0
    45
    ```
 1. Írd ki `u` minden második elemét az elsőtől kezdve.
    ```js
    91  // u[0]
    0   // u[2]
    78  // u[4]
    ```
### tömb bejárás + user input

  1. Kérj be egy `n` számot. Írd ki `u`  elemeit az `n` indextől.
      ```js
      // n == 2
      0    // u[2]
      45
      78
      ```
  1. Kérj be egy `n` számot. Írd ki `u`  elemeit az `n` indexig.
      ```js
      // n == 2
      91
      23
      0    // u[2]
      ```
  1. Kérj be egy `n` és egy `m` számot. Írd ki `u` elemeit `n` indextől az `m`
     indexig.
      ```js
      // n == 1, m == 3
      23    // u[1]
      0
      45    // u[3]
      ```


## tömb feldolgozás

1. Írd ki `t` elemeinek a dupláját.
    ```js
    84
    110
    246
    ```
1. Írd ki `t` elemeinek a tömb végétől való távolságát. 
    ```js
    4
    3
    2
    1
    0
    ```
1. Írd ki `t` elemeit zárójelek között.
    ```js
    "(42)"
    "(55)"
    "(123)"
    ```
1. Írd ki, hogy `t` melyik indexén milyen érték van. 
    ```js
    "t[0]: 42"
    "t[1]: 55"
    "t[2]: 123"
    ```
1. Írd ki `t` elemeinek első számjegyét.
    ```js
    "4"
    "5"
    "1"
    ```

### tömbelemek közötti összefüggés

1. Írd ki `u` elemeinek a megelőző elemmel vett összegét.
    ```js
    91    // nincs megelőző elem
    114
    23
    68
    123
    ```
1. Írd ki `u` elemeinek a megelőző elemmel vett különbségét. 
    ```js
    0    // nincs megelőző elem
    -68
    -23
    45
    33
    ```


## tömb módosítás

1. Cseréld ki `t` elemeit arra a sztringre, hogy "foo". Írd ki a tömböt előtte és utána.
    ```js
    "42, 55, 123"
    "foo, foo, foo"
    ```
1. Cseréld ki `t` elemeit az indexükre. Írd ki a tömböt előtte és utána.
    ```js
    "42, 55, 123"
    "0, 1, 2"
    ```
1. Duplázd meg `t` elemeit. Írd ki a tömböt előtte és utána.
    ```js
    "42, 55, 123"
    "84, 110, 246"
    ```
1. Szorozd meg meg `t` elemeit a tömbben elfoglalt pozíciójukkal. Írd ki a tömböt
   előtte és utána.
    ```js
    "42, 55, 123"
    "42, 110, 369"
    ```
1. Add hozzá `t` elemeihez a megelőző elem értékét. Írd ki a tömböt
   előtte és utána.
    ```js
    "42, 55, 123"
    "42, 97, 220"
    ```

## sztring bejárás

1. Írd ki a "hello" sztring betűit.
    ```js
    "h"
    "e"
    "l"
    "l"
    "o"
    ```
1. Írd ki az angol ábécé első 5 betújét.
    ```js
    "a"
    "b"
    "c"
    "d"
    "e"
    ```

1. Írj ki minden második betűt az angol ábécéből.
    ```js
    "b"
    "d"
    "f"
    "h"
    "j"
    "l"
    "n"
    "p"
    "r"
    "t"
    "v"
    "x"
    "z"
    ```

## nem számlálós ciklusok

1. Írd ki `v` elemeit, amíg `-1` elem nem jön.
    ```js
    1
    1
    0
    1
    0
    1
    // -1 jön, de azt már nem írjuk ki
    ```
1. Írd ki `v` elemeit az első negatív elemig.
    ```js
    1
    1
    0
    1
    0
    1
    // -1 jön, de azt már nem írjuk ki
    ```

1. Írd ki `v` elemeit az első negatív elemig bezárólag.
    ```js
    1
    1
    0
    1
    0
    1
    -1  // első negatív elem
    ```


### nem számlálós ciklusok + user input

1. Tölts fel egy tömböt felhasználótól bekért számokkal. Addig kérd be a számokat, amíg a felhasználó 0-t nem ad meg. Írd ki a tömböt a végén.
    ```js
    // > 5
    // > 3
    // > 8
    // > 0
    "5, 3, 8"
    ```
1. Tölts fel egy tömböt felhasználótól bekért számokkal. Kérj be egy számot és kérdezd meg, akar-e még számot megadni. Írd ki a megadott számokat.
    ```js
    // > 5
    // > igen, kér még
    // > 3
    // > igen, kér még
    // > 8
    // > igen, kér még
    // > 0
    // > igen, kér még
    // > 3
    // > nem, nem kér többet
    "5, 3, 8, 0, 3"
    ```

## ciklusba ágyazott elágazás

1. Írd ki a `v` pozitív elemeit.
    ```js
    1
    1
    1
    1
    ```
1. Írd ki a `v` pozitív elemeit.
    ```js
    1
    1
    1
    1
    ```
1. Írd ki a `hallgatok` tömbből azon hallgatók neveit, akiknek a pontszáma legalább
   `70`
    ```js
    "Almasi Alice"
    "Copfos Cecil"
    ```

### ciklusba ágyazott elágazás + user input

1. Kérj be `3` számot egy tömbbe. Miután bekértél egy számot, kérdezz rá, hogy akarjuk-e
   megcserélni az előjelet. Ha igen, akkor úgy tároljuk el, hogy megcseréltük az
   előjelet. Írd ki a tömböt a végén.
   ```js
   // > 3
   // csere
   // 5
   // nincs csere
   // -8
   // csere
   "-3, 5, 8"
   ```

1. Kérj be `3` számot egy tömbbe. Miután bekértél egy számot, kérdezz rá, hogy
  biztosan ezt a számot akarjuk-e beírni. Ha nem, akkor kérjünk be egy új számot
  helyette. Másodjára nem kérdezünk vissza. Írd ki a tömböt a végén.
    ```js
    // > 3
    // biztos
    // > 5
    // nem biztos
    // > 4
    // 8
    // biztos
    "3, 4, 8"
    ```


## tömb másolása






