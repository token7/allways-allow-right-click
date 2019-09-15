# allways-allow-right-click

allways proppagate js context event.

```js
document.addEventListener('contextmenu', function (e) {
  e.stopPropagation();
}, true);
```
`
