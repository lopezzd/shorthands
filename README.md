# Shorthands

```javascript

// longhand

  let y = 3;
  let x = 4;
 
// shorthand

  let [y, x] = [3, 4];

  /* Output: 3 - 4 */
```
```javascript

// longhand

  let y = 3;
  let x = 4;
  let z = y;

  y = x;
  x = z;

// shorthand

  let y = 3;
  let x = 4;

  [y , x] = [x , y];

  /* Output: 4 - 3 */
```
```javascript

// longhand

  function eraseSpaces(x){
    return x.trim()
  }

// shorthand

  const eraseSpaces = (x) => x.trim();

```
```javascript

// longhand

  let countries = ["Brazil","Canada","Spain"]

  countries = countries.concat("China")

// shorthand

  let countries = ["Brazil","Canada","Spain"]

  countries = [...countries, "China"]

  /* Output: [ 'Brazil', 'Canada', 'Spain', 'China' ] */

```
