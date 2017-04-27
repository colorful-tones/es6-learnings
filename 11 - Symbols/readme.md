### Symbols
A new primitive data type has been added = symbol.

Primitive data types:

1. number
2. string
3. boolean
4. null
5. undefined
6. object
7. symbol (new in ECMAScript 6)

Symbols will always be absolutely unique, which helps in avoiding naming collisions.

#### Syntax
```
Symbol([description])
```

##### Parameters
`description` (optional) - Optional, string. A description of the symbol which can be used for debugging but not to access the symbol itself.

##### Code examples

* [Symbols](https://github.com/colorful-tones/es6-learnings/blob/master/11%20-%20Symbols/11-38-symbols.html#L10)

#### Further Reading

* "[Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)" - Mozilla Developer Network (MDN)
