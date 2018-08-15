# Multimap

> Multimap - a [Map] of [Set]s.

This is the implementation used in [Puppeteer](https://github.com/GoogleChrome/puppeteer/).

### Multimap

```
const Multimap = require('Multimap');
const map = new Mutlimap();
map.set('foo', 1);
map.set('foo', 2);
console.log(map.get('foo')); // Set{1, 2}
```

#### multimap.set(key, value)
- `key` <[K]>
- `value` <[V]>

#### multimap.get(key)
- `key` <[K]>
- returns: <![Set]<[V]>>

#### multimap.has(key)
- returns: <[boolean]>

#### multimap.hasValue(key, value)
- `key` <[K]>
- `value` <[V]>
- returns: <[boolean]>

#### multimap.size
- returns: <[number]>

#### multimap.delete(key, value)
- `key` <[K]>
- `value` <[V]>
- returns: <[boolean]>

#### multimap.deleteAll(key, value)
- `key` <[K]>

#### multimap.firstValue(key)
- `key` <[K]>
- returns: <?[V]>

#### multimap.firstKey()
- returns: <?[K]>

#### multimap.valuesArray()
- returns: <![Array]<[K]>>

#### multimap.keysArray()
- returns: <![Array]<[K]>>

#### multimap.clear()


[number]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Number_type "Number"
[Set]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set "Set"
[Map]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map "Map"
