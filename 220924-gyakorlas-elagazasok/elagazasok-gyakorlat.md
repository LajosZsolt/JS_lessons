`if-szintaxis`

1. Írj egy elágazást, ami kiírja a konzolra, hogy `42`, ha `2` kisebb, mint `3`!
1. Írj egy elágazást, ami kiírja a konzolra, hogy `42`, ha egy `a` változó értéke kisebb, mint `3`!
1. Írj egy tetszőleges elágazást, ami mindig lefut!
1. Írj egy tetszőleges elágazást, ami sosem fut le!
1. Mi fog kiíródni?

   ```js
   if (3 < 2)
     console.log("hello");
     console.log("vilag");
   ```

   ```js
   if (2 < 3)
     console.log("hello");
     console.log("vilag");
   ```

   ```js
   if (2 < 3) {
      console.log("hello");
      console.log("vilag");
   }
   ```

   ```js
   if (3 < 2) {
      console.log("hello");
      console.log("vilag");
   }
   ```

   ```js
   if (2 < 3) {;
      console.log("hello");
      console.log("vilag");
   }
   ```

   ```js
   if (2 < 3) {
      console.log("hello");
      console.log("vilag");
   };
   ```

   ```js
   if (2 < 3); {
      console.log("hello");
      console.log("vilag");
   }
   ```

`if-egyenlosegvizsgalat`

1. Kérj be két értéket! Írd ki értesítőablakban, hogy `megegyeznek`, ha megegyeznek.
1. Kérj be két értéket! Írd ki értesítőablakban, hogy `nem egyeznek meg`, ha nem egyeznek meg!
1. Megjelenik-e az értesítőablak?

   ```js
   let a = 2;
   if (a = 3) {
     alert("hello");
   }
   ```


`if-szigoru-vs-megengedo-egyenloseg`


1. Mi lesz a kifejezés értéke?

   ```js
   let a = "42";
   if (a == 42) {
     a = a + 1;
   }
   a    // ?
   ```

   ```js
   let a = "42";
   if (a === 42) {
     a = a + 1;
   }
   a    // ?
   ```

   ```js
   let a = prompt();  // beírjuk: 42
   if (a == 42) {
     a = a + 1;
   }
   a    // ?
   ```

   ```js
   let a = prompt();  // beírjuk: 42
   if (a === 42) {
     a = a + 1;
   }
   a    // ?
   ```

1. Egészítsd ki a kódot a `Number()` használatával úgy, hogy az elágazás lefusson!

   ```js
   let a = prompt();  // beírjuk: 42
   if (a === 42) {
     // ...
   }
   ```

`if-elagazas-iras`

1. Kérj be egy értéket! Ha nem szám, írd ki, hogy számot
   kell megadni!

1. Kérdezd meg a felhasználót, hogy mi a baj! Ha nem ír be semmit,
   írd ki, hogy `néma gyereknek anyja se érti a szavát`!

1. Kérj be egy testsúlyt. Ha nem pozitív szám, írd ki, hogy csak
   pozitív szám lehet.

1. Kérj be két számot. Ellenőrizd le, hogy az összegük szám-e az
   `isNaN()` függvénnyel. Ha nem szám, írd ki, hogy az eredmény
   érvénytelen.

`if-else-ketteagazas`



1. Kérj be egy számot! Ha nagyobb, mint nulla, írd ki, hogy `fizz`,
   máskülönben azt, hogy `buzz`.

1. Kérj be egy számot. Ha nagyobb, mint nulla, írd ki, hogy `fizz`,
   ha kisebb, azt, hogy `buzz`, máskülönben azt, hogy `fizzbuzz`.


1. Kérj be egy számot! Ha a szám negatív, írd ki, hogy a szám nem lehet
   negatív, különben írd ki a szám kétszeresét!


1. Kérdezd meg a felhasználót, hogy kávét vagy teát kér-e. Ha ezen
   két opción kívül bármi mást válaszol, írd ki, hogy a lehetséges
   opciók közül válasszon.

1. Kérj be két számot. Ellenőrizd le, hogy az összegük szám-e az
   `isNaN()` függvénnyel. Ha nem szám, írd ki, hogy az eredmény
   érvénytelen.


<!--
`if-else-ellentetes-feltetel-egyszerusites`
- egymást kizáró, ellentétes if feltételek if-else alakra alakítása
- észrevenni, mikor alakítható át
`if-else-atiras-alapertelmezett-ertek`
- if-else egyszerűsítése alapértelmezett érték + if használatára
`else-if-tobbfeleagazas`
-->



## `logikai-operatorok`

1. Kérdezd meg a felhasználót, hogy kávét vagy teát kér-e. Ha ezen
   két opción kívül bármi mást válaszol, írd ki, hogy a lehetséges
   opciók közül válasszon.
1. Kérj be egy ruha méretet (szám) és egy színt (szöveg). Ha a szín
   zöld

### `if-else` elágazás


### `if-elseif-else` többfelé ágazás

1. Kérd be, hogy hány óra van, 24 órás alakban. 18 óra után írd
   ki, hogy `jó estét`, 18 óra előtt, hogy `jó napot`, 10 óra előtt
   pedig, hogy `jó reggelt`.
