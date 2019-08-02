# Javascript

- Convert an hex string to ASCII:
```javascript
unescape();
```

- To desobfuscate a string in js, check the end of it and erase the eventual '()'. Then, append:
```javascript
str.toString();
```