title: fjs.isFunction
description: fjs.isFunction returns true if the argument is a function, otherwise false.
---

## fjs.isFunction

fjs.isFunction returns true if the argument is a function, otherwise false.

### Usage

```js
fjs.isFunction(arg);
```

### Example

```js
fjs.isFunction(fjs.reduce(function (arg1, arg2) {
    return arg1 * arg2;
})); // => true
```
