# es6/7 for python developers

---

## modules

> Namespaces are one honking great idea -- let's do more of those!

 * js has been without modules for longer than i've been programming

```
pi.js
export var PI = 3.14;

app.js
import {PI} from './pi.js';
```

---

## classes: a _consistent_ way of defining object types

> There should be one-- and preferably only one --obvious way to do it.

```
class Tree extends Plant {
  constructor(location) {
    super(location);
    // do some stuff
  }

  quack() {
    console.log("Trees don't quack");
  }
}
```

---

## Argument Rest/Spread & Defaults

 * sorta like *args
 * sorry no kwargs but at hey at least we get defaults

---

## Template Strings: a sucky version of string formatting

> In the face of ambiguity, refuse the temptation to guess.

 * Just pulls in from any variable declared in the scope

---

## Unicode

 * Todo

---

## Iterators, Generators

> If the implementation is hard to explain, it's a bad idea.

 * Don't bother?

> im sure they could have made the syntax more opaque and clunky, they didnt try hard enough

 * but wait there's more...

---

## Comprehensions

 * Both array & generator comprehensions!
 * Format is for-if-statement, rather than statement-for-if

```
var someArray = [
  for (thing of things)
    if (thing.quack)
      thing.quack()
];

// as a generator:
var someArray = (
  for (thing of things)
    if (thing.quack)
      thing.quack()
);
```

---

## Decorators

 * todo

---

## async/wait

 * todo

---

## And more!

 * Arrow functions
 * Constants
 * 
