
`valtozok-zsargon-szintaxis`

1. Deklarálj egy `foo` nevű változót `42` értékkel!
1. Hozz létre egy `bar` változót!
1. Legyen `baz` `"hello"`!
1. Inicializálj egy `a` változót `55` értékkel!
1. Vezess be egy `b` inicializálatlan változót!
1. Külön-külön utasításban
   - deklarálj egy `c` változót
   - adj egy tetszőleges szám típusú értéket
1. Külön-külön utasításban
   - deklarálj egy `d` változót
   - adj egy tetszőleges szöveg típusú értéket

`valtozok-kifejezesek`

1. Írj egy kifejezést a megadott változók használatával, ami a várt értéket produkálja!

   ```js
   let a = 42;
   
   ? // 43
   ? // 84 
   ```

   ```js
   let b = "hello";

   ? // "hello world"
   ? // "hello hello"
   ```

   ```js
   let a = 42;
   let b = "hello";

   ? // "hello 42"
   ? // "hello 42 hello 42"
   ? // "hello 42 hello 43"
   ```

1. Mit kell a megjelölt részhez írni, hogy a várt eredményt írjuk ki? Használd a megadott változókat!

```js
let nev = "Alice";
let kor = 42;

// felhasználónak írjuk ki
? // Alice
? // 42
? // Alice eletkora 42
? // Alice eletkora 43

// konzolra írjuk ki
? // Alice eletkora 42
? // Alice eletkora 43
```

`valtozok-adat-mutacio`

1. Mikor mi lesz a változó értéke?

   ```js
   let a = 42;

   a // ?

   a = a + 1;

   a // ?

   a + 1;

   a // ?

   a = a + "1"

   a // ?

   a = a + 1

   a // ?
   ```

`valtozok-undefined`

1. Melyik kifejezés értéke micsoda?

   ```js
   "foo" + undefined    // ?
   42 + undefined       // ?
   "foo" + "undefined"  // ?
   42 + "undefined"     // ?
   ```

   ```js
   let a = 42;
   let b = "foo";
   let c;

   a + b                // ?
   c + a                // ?
   b + c                // ?
   c + c                // ?
   ```

`valtozok-kod-dedukcio`

1. Melyik változó értéke micsoda?

   ```js
   a + b   // "hello world undefined"
   
   a       // ?
   b       // ?
   ```

   ```js
   a + b   // NaN

   a       // ?
   b       // ?
   ```

   ```js
   a + b   // NaN
   b + c   // "undefined world"

   a       // ?
   b       // ?
   c       // ?
   ```

`valtozok-ertek-masolasa`

1. ```js
   ```

`szoveges-instrukciok`

1. Hozz létre egy `foo` változót `"hello"` kezdőértékkel!
1. Írd ki 