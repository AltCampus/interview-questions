# Interview Questions

## JavaScript

1. What will be the output of the code below?

```js
function foo() {
  let x = (y = 0);
  x++;
  y++;
  return x;
}

console.log(foo(), typeof x, typeof y);
```
