## összegzés

### összes km

Futóversenyre edzünk. Szakaszokban futunk, a szakaszok között rövid pihenővel.
A szakaszok hosszai
- 2 km
- 1 km
- 2 km
- 1 km

Számítsuk ki, hogy összesen hány km-t tettünk meg.

### vízállás

Követni akarjuk a vízállást. Ismerjük a víz magasságát a kiinduló napon és utána
minden nap feljegyeztük hogyan változott.
- kezdetben 40 cm
- +3 cm
- -5 cm
- -2 cm
- +1 cm
- +2 cm

Mekkora a vízállás az utolsó méréskor?


## keresés

### hirtelen fékezés

Állapítsuk meg, hogy volt-e hirtelen fékezés egy busz sebesség adatai alapján.
Másodpercenként 3 mérési adatunk van. Ha egy másodperc alatt 20%-ot csökken a
sebesség, akkor hirtelen fékezés történt.

Sebesség mérések
- 60
- 61
- 60
- 58
- 60  itt történt hirtelen fékezés
- 57
- 53
- 47
- 35
- 32
- 30
- 30
- 32

### Ackack

Aliens are attacking Earth. We are in control of the Tsar Bomb.

Write a program, that targets the alien mothership.

Extract the mothership coordinates from the array.

**Example:**

```js
// output: "40.5, 48.4"
let data = [
  ["F14", [23.12, 21.6]],
  ["MIG24", [22.1, 24.5]],
  ["Mothership", [40.5, 48.4]],  
  ["Gripen", [19.2, 16.5]]
]
```

### Stolen car

Our car (`AAA-007`) was stolen from a garage. We have the data of the license plates that
have been seen passing through the 2nd exit.

Check if the car was seen passing through the 2nd exit. If yes, display the
**position** of the car in the order the cars passed. If not, display the message:
"out of luck".

**Examples:**

```js
// 4
let data = ['ABC-123', 'LSD-050', 'THC-444', 'AAA-007'];
```

```js
// 1
let data = ['AAA-007', 'ABC-123', 'LSD-050', 'THC-444'];
```

```js
// out of luck
let data = ['ABC-123', 'LSD-050', 'THC-444'];
```