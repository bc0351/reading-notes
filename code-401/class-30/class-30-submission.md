Implementation: Hash Tables
===========================

## JavaScript Map as HashMap

I've been using JavaScript's built-in Map Object when needing to implement a hashmap. Hashmap's are great when they can be implemented for a given problem domain because of it's speed in fetching key-value pairs (i.e. `O(1)`).

Reference: [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)

You can create a hash function prior to setting if required, e.g. obfuscating clear-text, but if security is not a concern, there is no need. Every time `set()` is used to enter a key-value pair, if the key exists, the value is replaced with the new value.

You can mimic collision behavior with something like:

```javascript
function addValue(key, value) {
  if(hashMap.has(key)) {
    let existingValue = hashMap.get(key);
    if (typeof existingValue !== 'array') {
      existingValue = [existingValue];
    } else {
    existingValue.push(value)
    hashMap.set(key, existingValue);
  }
```
